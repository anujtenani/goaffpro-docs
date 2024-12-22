# CartX Integration

**GoAffPro** provides you with the option to integrate the CartX payment gateway.

To integrate the CartX payment gateway, embed the following code in the **Body section** of the **Thank You page** in the CartX app.&#x20;

```
<script type="text/javascript">
(function () {
            let q = [];
            if(!window.Goaffpro){
                window.Goaffpro = function(){
                    q.push(arguments);
                }
            }
            var s = document.createElement('script');
            s.type = 'text/javascript';
            s.async = true;
            s.src = 'https://static.goaffpro.com/client_sdk.js';
            s.onload = ()=>q.forEach((item)=> Goaffpro.apply(null, item))
            var x = document.getElementsByTagName('script')[0];
            x.parentNode.insertBefore(s, x);
        })();
        Goaffpro('init', 'my-storefront-token');
        Goaffpro('track-conversion', {
            id: order.id,
            number: order.name,
            total_price: order.total_price,
            subtotal_price: order.subtotal_price,
            total_discounts: order.total_discounts,
            email: order.email,
            line_items: order.order_items.map(function(item){
                return {
                    product_id: item.product_id,
                    variant_id: item.variant_id,
                    price: item.price,
                    quantity: item.quantity,
                    name: item.name,
                    total_discount: item.total_discount
                }
            })
        });
</script>
```

{% hint style="info" %}
Replace the **my-storefront-token** with your store's public token.

To generate the storefront token, go to Settings > Advanced Settings tab > API/Access Token section.
{% endhint %}
