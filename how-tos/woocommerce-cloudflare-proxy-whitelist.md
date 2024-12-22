---
description: For WooCommerce merchants only
---

# WooCommerce Cloudflare Proxy Whitelist

### To whitelist our servers, if you are using Cloudflare proxy:

Open your Cloudflare admin panel, go to the **Websites** section, and select your domain.

<figure><img src="../.gitbook/assets/Screenshot 2024-04-29 114142.png" alt=""><figcaption><p>Cloudflare > Websites > Select Domain</p></figcaption></figure>

Here, go to the Security > WAF section.

<figure><img src="../.gitbook/assets/Screenshot 2024-04-29 114226.png" alt=""><figcaption><p>Go to the Security > WAF section</p></figcaption></figure>

Now, open the Tools section.

<figure><img src="../.gitbook/assets/Screenshot 2024-04-29 114308.png" alt=""><figcaption><p>Opens the Tools section</p></figcaption></figure>

Here, enter the IP address.

<figure><img src="../.gitbook/assets/Screenshot 2024-04-29 114423.png" alt=""><figcaption><p>Enter the IP address</p></figcaption></figure>

Now, select the "Allow" action.

<figure><img src="../.gitbook/assets/Screenshot 2024-04-29 114450.png" alt=""><figcaption><p>Select "Allow" action</p></figcaption></figure>

You also have the option to add a note.&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2024-04-29 114521.png" alt=""><figcaption><p>Add note</p></figcaption></figure>

Next, click on **Add**.

<figure><img src="../.gitbook/assets/Screenshot 2024-04-29 1145421.png" alt=""><figcaption><p>Click on Add</p></figcaption></figure>

After this, follow the same process and add all of the following IPs, to whitelist them:

* 49.12.173.137&#x20;
* 49.12.172.232
* 168.119.2.98
* 168.119.2.99
* 49.12.122.23
* 95.217.6.74

<figure><img src="../.gitbook/assets/Screenshot 2024-04-29 114644.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Here is Cloudflare's guide for whitelisting IPs: [guide](https://developers.cloudflare.com/waf/tools/ip-access-rules/create/).
{% endhint %}

{% embed url="https://youtu.be/E8HBClw1tr0/" %}
WooCommerce Cloudflare Proxy Whitelisting
{% endembed %}
