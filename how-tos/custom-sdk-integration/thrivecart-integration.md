# ThriveCart Integration

#### To integrate ThriveCart with GoAffPro SDK integration:

Open the setup wizard: [https://app.goaffpro.com/wizard](https://app.goaffpro.com/wizard)

{% hint style="info" %}
The setup wizard will open up automatically when you open the GoAffPro admin panel for the first time.
{% endhint %}

Here, select **Thrive Cart**.

<figure><img src="../../.gitbook/assets/Screenshot 2023-11-20 16125409.png" alt=""><figcaption><p>Select Thrive Cart</p></figcaption></figure>

This will open up the Thrive Cart integration steps.

<figure><img src="../../.gitbook/assets/image (304).png" alt=""><figcaption><p>Thrive Cart integration</p></figcaption></figure>

Add the following code in your store's header area:

```
<script type="text/javascript" src="https://api.goaffpro.com/loader.js?shop=your-unique-store-public-key"></script>
```

{% hint style="info" %}
Please make sure to replace the <mark style="background-color:blue;">your-unique-store-public-key</mark> from the code, with the public key from your account (from the Settings > Advanced > Third Party Tracking section).
{% endhint %}

<figure><img src="../../.gitbook/assets/image (3345).png" alt=""><figcaption><p>Add the code in your store header area</p></figcaption></figure>

Finally, add the following code in your Success/Thank you page:

```
<script type="text/javascript">
var goaffproOrder = {
    id:_thrive_order.order.id,
    number:_thrive_order.order.invoice_id,
    total: _thrive_order.order.total/100,
    tax: _thrive_order.order.tax/100,
    shipping: _thrive_order.order.shipping,
    currency:_thrive_order.order.currency,
    customer: {
        first_name: _thrive_order.customer.name,
        email:_thrive_order.customer.email
    },
}
goaffproTrackConversion(goaffproOrder);
</script>
```

<figure><img src="../../.gitbook/assets/image (3346).png" alt=""><figcaption><p>Copy &#x26; paste the code in your Success/Thank you page</p></figcaption></figure>
