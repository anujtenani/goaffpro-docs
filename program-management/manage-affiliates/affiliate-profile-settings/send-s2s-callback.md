# Send Postback/S2S Callback to the Affiliate

**GoAffPro** provides you with the option to send Postback/S2S callback to the affiliate when they get a new order.

To send Postback/S2S callback to the affiliate, go to the **All Affiliates** section in the **Affiliates** tab of the GoAffPro admin panel.

<figure><img src="../../../.gitbook/assets/image (3520).png" alt=""><figcaption><p>Affiliates > All Affiliates</p></figcaption></figure>

Here, click on the **affiliate's name.**

<figure><img src="../../../.gitbook/assets/Screenshot 2026-09-03 001148 (2).png" alt=""><figcaption><p>Click on the affiliate's name</p></figcaption></figure>

This will open the affiliate's profile.

<figure><img src="../../../.gitbook/assets/image (3943).png" alt=""><figcaption><p>Affiliate Profile</p></figcaption></figure>

Now, go to the **Settings** tab.

<figure><img src="../../../.gitbook/assets/Screenshot 2026-09-03 001157 (2).png" alt=""><figcaption><p>Settings tab</p></figcaption></figure>

Here, go to the S2S Callback (Postbacks) section.

<figure><img src="../../../.gitbook/assets/image (3947).png" alt=""><figcaption><p>S2S Callback (Postbacks)</p></figcaption></figure>

Now, click on the **callback**.

<figure><img src="../../../.gitbook/assets/Screenshot 2026-09-03 013618.png" alt=""><figcaption><p>Click on the callback</p></figcaption></figure>

This will open the setup callback window.

<figure><img src="../../../.gitbook/assets/image (3949).png" alt=""><figcaption><p>Setup callback window</p></figcaption></figure>

After this, select the HTTP method and enter the URL.&#x20;

{% hint style="info" %}
You can select either GET or POST.
{% endhint %}

<figure><img src="../../../.gitbook/assets/Screenshot 2026-09-03 01363242.png" alt=""><figcaption><p>Select the HTTP method > Enter the URL</p></figcaption></figure>

Finally, click on **Submit**.

<figure><img src="../../../.gitbook/assets/Screenshot 2026-09-03 013647.png" alt=""><figcaption><p>Click on Submit</p></figcaption></figure>

The newly set S2S callback will be saved.

<figure><img src="../../../.gitbook/assets/image (3950).png" alt=""><figcaption><p>S2S Callback saved</p></figcaption></figure>

<details>

<summary>Formatting the Postback URL for Affiliate Tracking</summary>

Postback URLs enable you to receive real-time notifications whenever an order is tracked. You can add dynamic variables to your URL, ensuring that each postback contains valuable order and click data. Below are the supported variables and examples on how to use them:

**Supported Variables:**

The order number: \{{order.number\}}&#x20;

Total order amount: \{{order.amount\}}&#x20;

Commission generated for the order: \{{order.commission\}}&#x20;

Query parameter from the referral link (replace "param" with your chosen parameter name): \{{link.query.param\}}

Link hash parameter: \{{link.hash\}}&#x20;

Link path parameter: \{{link.path\}}&#x20;

Link sub\_id parameter: \{{link.sub\_id\}}&#x20;

**Examples:**

1. **Basic Postback URL (Send order number & amount)**

https://yourpostback.com?number=\{{order.number\}}\&amount=\{{order.amount\}}

2. **Include commission generated**

https://yourdomain.com/postback?order=\{{order.number\}}\&amt=\{{order.amount\}}\&comm=\{{order.commission\}}

3. **Send a custom query parameter from the referral link**

If your affiliate link looks like: https://yourstore.com/?campaign=summer

You can capture it using:

https://yourpostback.com/?order=\{{order.number\}}\&campaign=\{{link.query.campaign\}}

4. **Using Sub ID tracking**

https://track.me/postback?order=\{{order.number\}}\&subid=\{{link.sub\_id\}}

5. **Send all available data**

https://yourpostback.com?\
order=\{{order.number\}}\
\&amount=\{{order.amount\}}\
\&commission=\{{order.commission\}}\
\&subid=\{{link.sub\_id\}}\
\&hash=\{{link.hash\}}\
\&path=\{{link.path\}}

**Notes:**

* Ensure that your URL is properly URL-encoded if you include any special characters.
* Variables are automatically replaced with actual values before the postback is fired.

</details>

{% embed url="https://www.youtube.com/watch?v=DC0tPa4POBY" %}
Send S2S Callback to the Affiliate
{% endembed %}
