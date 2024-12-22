# E-Junkie Integration

#### To integrate E-Junkie with GoAffPro SDK integration:

Add the general tracking code of the thank you page in E-Junkie:

```
<script type="text/javascript" src="https://api.goaffpro.com/loader.js?shop=your-unique-store-public-key"></script>
```

{% hint style="info" %}
Please make sure to replace the <mark style="background-color:blue;">your-unique-store-public-key</mark> from the code, with the public key from your account (from the Settings > Advanced > Third Party Tracking section).
{% endhint %}

After this, add the following conversion tracking code (below the general tracking code):

```
<script type="text/javascript">
var goaffproOrder = {
    id:'[%txn_id%]', 
    number:'[%ej_txn_id%]', 
    total: '[%gross%]',
    subtotal: '[%total%]', 
    tax: '[%tax%]',
    shipping: '[%shipping%]',
    currency:'[%currency%]',
    customer: { 
        first_name:'[%first_name%]',
        last_name:'[%last_name%]',
        email:'[%payer_email%]'
    },
    status:"approved"
}

goaffproTrackConversion(goaffproOrder);
</script>
```
