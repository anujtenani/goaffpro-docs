---
description: For Advanced Users Only
---

# Goaffpro Custom Shopify Integration

### Integration steps <a href="#integration-steps" id="integration-steps"></a>

### All Pages <a href="#all-pages" id="all-pages"></a>

Embed the tracking script in all pages of your store. **You can find this script in the Settings -> Advanced Settings tab -> Third Party Tracking section**

```
<script type="text/javascript" async defer src="https://api.goaffpro.com/loader.js?shop=goaffprotest1.myshopify.com"></script>
```

You can add the script in the footer page of your site.

### Thank You Page <a href="#thank-you-page" id="thank-you-page"></a>

You should create your thank you page in such a manner that the following variable is exposed in global scope before the tracking script gets loaded

```
Shopify = {    checkout:{        order_id:'SHOPIFY ORDER_ID OF THE ORDER'    }}
```

### Server-Side Integration <a href="#server-side-integration" id="server-side-integration"></a>

Make an HTTP POST call to the following endpoint after the payment is processed to record the sale in the app

```
POST https://api.goaffpro.com/order_completeContent-Type: application/json​{    "ref":"the referral cookie",    "shop":"the shop identifier as found in the tracking script",    "order_id":"the shopify order id"}
```
