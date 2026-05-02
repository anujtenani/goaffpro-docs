# Send Postback/S2S Callback to the Affiliate

**GoAffPro** provides you with the option to send Postback/S2S callback to the affiliate when they get a new order.

To send Postback/S2S callback to the affiliate, go to the **All Affiliates** section in the **Affiliates** tab of the GoAffPro admin panel.

<figure><img src="../../../.gitbook/assets/image (3520).png" alt=""><figcaption><p>Affiliates > All Affiliates</p></figcaption></figure>

Here, click on the **affiliate's name.**

![Click on the affiliate's name](<../../../.gitbook/assets/Annotation 2020-03-03 013129.png>)

This will open up the affiliate's profile.

![Affiliate Profile](<../../../.gitbook/assets/Annotation 2020-03-03 013817 (1).png>)

Now, go to the **Settings** tab.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-30 2021492.png" alt=""><figcaption><p>Settings tab</p></figcaption></figure>

Here, go to the S2S Callback section.

![S2S Callback](<../../../.gitbook/assets/image (2171).png>)

Now, click on **Order created callback**.

![Click on Order created callback](<../../../.gitbook/assets/Screenshot 2020-09-29 173826 (1).png>)

This will open up the Setup order created callback window.

![Order created callback](<../../../.gitbook/assets/image (822).png>)

Now, select the HTTP method.

{% hint style="info" %}
You can select either GET or POST.
{% endhint %}

![Select the HTTP method](<../../../.gitbook/assets/Screenshot 2020-09-29 174201.png>)

After this, enter the URL.

![Enter the URL](<../../../.gitbook/assets/Screenshot 2020-09-29 174433.png>)

Click on **Submit**.

![Click on Submit](<../../../.gitbook/assets/Screenshot 2020-09-29 174647.png>)

Finally, the newly set S2S callback will be saved.

![S2S Callback saved](<../../../.gitbook/assets/image (385).png>)

The same process can be followed to set the Order updated callback.

![](<../../../.gitbook/assets/Screenshot 2020-09-29 175150.png>)

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
