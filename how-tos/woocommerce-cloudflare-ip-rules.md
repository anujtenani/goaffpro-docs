---
description: For WooCommerce merchants only
---

# WooCommerce Cloudflare IP Rules

### Allow GoAffPro's IP address in your Cloudflare firewall rules so it can access your store API:&#x20;

In your Cloudflare dashboard, go to the Security section and click on **WAF**.&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2026-09-30 202526.png" alt=""><figcaption><p>Cloudflare > Security > WAF</p></figcaption></figure>

Here, go to the Tools section.&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2026-09-30 202532.png" alt=""><figcaption><p>Go to the Tools section</p></figcaption></figure>

After this, in the IP Access Rules section, add the following IP addresses with the "**Allow**" action:&#x20;

* **5.161.205.57**
* **2a01:4ff:f0:9b54::1**

Finally, click on **Add**.&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2026-09-30 202535142.png" alt=""><figcaption><p>IP Access Rules section > Add the IP addresses > "Allow" Action > Click on Add</p></figcaption></figure>
