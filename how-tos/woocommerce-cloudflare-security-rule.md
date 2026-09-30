---
description: For WooCommerce merchants only
noIndex: true
---

# WooCommerce Cloudflare Security Rule

### To allow GoAffPro to access your store API, if you are using Cloudflare:&#x20;

In your Cloudflare dashboard, open the Security section and click on the WAF option.&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2026-09-30 202526.png" alt=""><figcaption><p>Cloudflare > Security > WAF</p></figcaption></figure>

Here, go to the Tools section.&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2026-09-30 202532.png" alt=""><figcaption><p>Go to the Tools section</p></figcaption></figure>

After this, in the IP Access Rules section, add the following IP addresses with the "Allow" action:&#x20;

* 5.161.205.57
* 2a01:4ff:f0:9b54::1

Finally, click on **Add**.&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2026-09-30 202535142.png" alt=""><figcaption><p>IP Access Rules section > Add the IP addresses > "Allow" Action > Click on Add</p></figcaption></figure>
