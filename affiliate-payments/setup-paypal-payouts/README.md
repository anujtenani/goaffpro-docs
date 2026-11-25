# Setup PayPal Payouts

**GoAffPro** provides you with the option to integrate PayPal Payouts.

{% hint style="info" %}
You can integrate PayPal Payouts with GoAffPro to conveniently make payments to affiliates from within the app.
{% endhint %}

To set up PayPal Payouts, go to the **Integrations** section in the **Settings** tab of the GoAffPro admin panel.

<figure><img src="../../.gitbook/assets/image (252) (1).png" alt=""><figcaption><p>Settings > Integrations</p></figcaption></figure>

Here, go to the PayPal Payouts section.

![PayPal Payouts](<../../.gitbook/assets/image (1468).png>)

Now, click on **Setup**.

![Click on Setup](<../../.gitbook/assets/Annotation 2020-08-19 205935.png>)

This will open up the Setup PayPal Payouts section.

![Setup PayPal Payouts ](<../../.gitbook/assets/image (1319).png>)

Here, click on the PayPal My Apps link.

![PayPal My Apps](<../../.gitbook/assets/Annotation 2020-08-19 210109.png>)

This will open up the PayPal developer dashboard.

<figure><img src="../../.gitbook/assets/Screenshot 2024-01-15 140242.png" alt=""><figcaption><p>PayPal developer dashboard</p></figcaption></figure>

Here, go to the Apps & Credentials section.

<figure><img src="../../.gitbook/assets/Screenshot 2024-01-15 1240242.png" alt=""><figcaption><p>Apps &#x26; Credentials</p></figcaption></figure>

Now, click on **View live credentials**.

<figure><img src="../../.gitbook/assets/Screenshot 2024-01-15 1403229.png" alt=""><figcaption><p>Click on View live credentials</p></figcaption></figure>

Next, click on **Create App**.

<figure><img src="../../.gitbook/assets/Screenshot 2024-01-15 1403516.png" alt=""><figcaption><p>Click on Create App</p></figcaption></figure>

Here, set the app name.

<figure><img src="../../.gitbook/assets/Screenshot 2024-01-15 140425.png" alt=""><figcaption><p>Set the app name</p></figcaption></figure>

After this, click on **Create App**.

<figure><img src="../../.gitbook/assets/Screenshot 2024-01-15 1440458.png" alt=""><figcaption><p>Click on Create App</p></figcaption></figure>

This will open up the GoAffPro Payouts app section.

<figure><img src="../../.gitbook/assets/Screenshot 2024-01-15 140607.png" alt=""><figcaption><p>GoAffPro Payouts app section</p></figcaption></figure>

Here, copy the Client ID.

<figure><img src="../../.gitbook/assets/Screenshot 2024-01-15 140638.png" alt=""><figcaption><p>Copy the client ID</p></figcaption></figure>

Now, paste it in the Setup PayPal Payouts section.

![Paste the Client ID](<../../.gitbook/assets/Annotation 2020-08-19 212750.png>)

After this, copy the secret.

<figure><img src="../../.gitbook/assets/Screenshot 2024-01-15 1420638.png" alt=""><figcaption><p>Copy the secret</p></figcaption></figure>

Paste the secret in the Setup PayPal Payouts section.

![Paste the secret](<../../.gitbook/assets/Annotation 2020-08-19 213031.png>)

Finally, click on **Save**.

![Click on Save](<../../.gitbook/assets/Annotation 2020-08-19 212605.png>)

PayPal Payouts will now be connected.

![](<../../.gitbook/assets/image (2269).png>)

<details>

<summary>FAQ</summary>

#### My PayPal Payouts Integration is not working: <a href="#my-paypal-payouts-integration-is-not-working" id="my-paypal-payouts-integration-is-not-working"></a>

In the case that your PayPal Payouts integration is not working. Check the following:

* Your PayPal account is a business account
* You are using **Live** credentials and not Sandbox credentials.

#### PayPal Error Troubleshooting

**PayPal Payouts IP Requirement:** If you are having difficulties making payments to affiliates using PayPal payouts? The PayPal team now requires a fixed IP address to process payouts.

You can submit a support ticket with PayPal for issues with the Payouts API and provide them with the following two IP addresses:

* 2a01:4ff:f0:9b54::1
* 5.161.205.57

**AUTHORIZATION\_ERROR:** Your PayPal account does not appear to be authorized to use Payouts API. You'll need to ask PayPal customer support to activate PAYOUTS API on your account (only PayPal can do this from their end).

**INSUFFICIENT\_FUNDS**: Your PayPal account balance does not have sufficient funds for sending money to affiliates. You need to add money to your PayPal account balance for the payments to work.

</details>

{% embed url="https://youtu.be/SODZ1oLMOYw" %}
Setup PayPal Payouts
{% endembed %}
