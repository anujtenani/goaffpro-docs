# Manual BigCommerce Integration

#### Manually add the tracking code in your BigCommerce store:

Open the BigCommerce admin page.&#x20;

![BigCommerce admin page ](<../../.gitbook/assets/Annotation 2020-07-06 130623.png>)

Now, go to the Advanced Settings section.

![Advanced Settings](<../../.gitbook/assets/Annotation 2020-07-06 130931.png>)

After this, go to the Web Analytics section.

![Web Analytics ](<../../.gitbook/assets/Annotation 2020-07-06 132042.png>)

Now, check the Affiliate Conversion Tracking option.&#x20;

![Affiliate Conversion Tracking option](<../../.gitbook/assets/Annotation 2020-07-06 132623.png>)

After this, click on **Save**.

![Click on Save](<../../.gitbook/assets/Annotation 2020-07-06 133041.png>)

Copy the following code:&#x20;

```
<script type="text/javascript">window.__big = {order_id: %%ORDER_ID%%, order_amount: %%ORDER_AMOUNT%% }</script>
```

Paste the code in the Conversion Tracking Code box.

![Paste the code](<../../.gitbook/assets/Annotation 2020-07-06 133556.png>)

Finally, click on **Save**.

![Click on Save](<../../.gitbook/assets/Annotation 2020-07-06 1335562.png>)

<details>

<summary>FAQ</summary>

#### Why aren't my orders getting tracked?

If you are having issues with tracking referral sales, then you may have to manually add the tracking code in BigCommerce.

#### If the tracking issue persists even after adding the tracking code:

In the case, the referral sales are still not getting tracked, even after you have added the tracking code manually. The issue is likely to be that the tracking script is not loading your store.

You can go to Settings > Advanced > Third Party Tracking and embed the tracking code present in that section to the theme page of the store, just before the \</body> tag.

If the referral sales are still not getting tracked on your store, contact our technical team at admin@goaffpro.com&#x20;

</details>

{% embed url="https://www.youtube.com/watch?v=9A2eO5SC7t0#action=share" %}
BigCommerce Manually Add Tracking Code
{% endembed %}
