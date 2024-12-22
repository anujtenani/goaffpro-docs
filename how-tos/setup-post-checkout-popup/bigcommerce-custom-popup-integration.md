---
description: For Advanced Users Only
---

# BigCommerce Custom Popup Integration

#### If the Post Checkout Popup is not appearing in the thank you page of the store, follow the steps given below for the custom integration of the popup script:

Go to the **Advanced** section of the **Settings** tab in the GoAffPro admin panel.

![Settings > Advanced](<../../.gitbook/assets/image (884).png>)

Here, go to the Third Party Tracking section.

![Third Party Tracking](<../../.gitbook/assets/image (1779).png>)

Now, copy the tracking code.

![Copy the tracking code](<../../.gitbook/assets/Annotation 2020-07-06 163117.png>)

Change the code (by replacing: **https://api.goaffpro.com/loader.js** with **https://api.goaffpro.com/checkout\_widget.js**)

**From tracking script:**

```
<script type="text/javascript" src="https://api.goaffpro.com/loader.js?shop=example "></script>
```

**To popup script:**

```
<script type="text/javascript" src="https://api.goaffpro.com/checkout_widget.js?shop=example"></script>
```

After this, add the popup script in the Advanced Settings > Web Analytics > Affiliate Conversion Tracking > Conversion Tracking Code box in the BigCommerce panel. Finally, click on **Save**.

{% hint style="info" %}
Also, make sure that the third party tracking script is added in the Conversion Tracking Code box.
{% endhint %}

![](<../../.gitbook/assets/Annotation 2020-07-06 133556 (2).png>)
