---
description: Setup a custom name for your affiliate portal
---

# Custom Domain Setup

**GoAffPro** provides you with the option to set up a custom domain for your affiliate portal. Having a custom domain for your affiliate program offers a range of benefits.&#x20;

* It adds a professional touch to your program, making it look more credible and trustworthy to potential affiliates.&#x20;
* This can help you attract high-quality affiliates who are more likely to promote your products or services effectively.

> Setting a custom domain name for your affiliate portal can improve your SEO (search engine optimization) efforts. It can increase your program's visibility in search engine results and lead to more affiliates enrolling in your program.

![Custom Domain Setup](../.gitbook/assets/assets_-LdPzLtyP46oY7cyXnkw_-Ll6cuWq6Xa4X8H4NY78_-Ll6cwKRrVZHrnfo-IXg_Untitled.png)

### Set up the portal name for your affiliate portal

In the **Look and Feel** tab, go to the **Store Profile** section.

<figure><img src="../.gitbook/assets/image (3441).png" alt=""><figcaption><p>Look and Feel > Store Profile</p></figcaption></figure>

Here, in the **Affiliate Portal** section, click on **Change**.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-19 153140.png" alt=""><figcaption><p>Affiliate Portal > Click on Change</p></figcaption></figure>

This will open the change affiliate portal domain window. Here, you can select from various affiliate portal domain types:

* Subdomain of GoAffPro
* Subdomain of your shop
* Custom domain.

<figure><img src="../.gitbook/assets/image (3442).png" alt=""><figcaption><p>Change the affiliate portal domain</p></figcaption></figure>

### **Subdomain of GoAffPro**

Select the **Subdomain of goaffpro** option and set the affiliate portal domain name.&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2024-02-19 155452.png" alt=""><figcaption><p>Select the Subdomain of goaffpro option > Set the affiliate portal domain name</p></figcaption></figure>

After this, click on **Submit**.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-19 155714.png" alt=""><figcaption><p>Click on Submit</p></figcaption></figure>

### **Subdomain of your shop**

Select the **Subdomain of your shop** and set the affiliate portal domain name.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-19 155933.png" alt=""><figcaption><p>Select the Subdomain of your shop option > Set the affiliate portal domain name</p></figcaption></figure>

Add a new **CNAME record** for your domain.

#### Create a new CNAME record at your DNS registrar for your domain with the following values:

<table><thead><tr><th>Name or Host</th><th>Value or Points To</th><th data-hidden></th></tr></thead><tbody><tr><td>affiliates</td><td>partners.goaffpro.com</td><td></td></tr></tbody></table>

{% hint style="info" %}
Domain registrars have different ways of setting up CNAME records. You can find instructions to add a CNAME record at the domain registrar's website.

You can also follow our guide on how to set up the CNAME record for different domain registrars: [https://app.goaffpro.com/extras/cname\_guide/yourstore](https://app.goaffpro.com/extras/cname_guide/yourstore)
{% endhint %}

<figure><img src="../.gitbook/assets/Screenshot 2024-02-19 1558313.png" alt=""><figcaption><p>Add the CNAME record</p></figcaption></figure>

Finally, click on **Submit**.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-19 155813.png" alt=""><figcaption><p>Click on Submit</p></figcaption></figure>

### Set the affiliate portal as a custom domain

Select the **Custom Domain** option and set the affiliate portal domain.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-19 1608133.png" alt=""><figcaption><p>Select the Custom domain option > Set the affiliate portal domain </p></figcaption></figure>

Add a new **A record** for your domain.

#### **Create a new A record at your DNS registrar for your domain with the following values:**

| Name        | Value          | TTL  |
| ----------- | -------------- | ---- |
| example.com | 195.201.216.82 | 3600 |

{% hint style="info" %}
Different domain registrars have different ways of setting up Domain A records. You can find instructions to add an A record at the domain registrar's website.
{% endhint %}

<figure><img src="../.gitbook/assets/Screenshot 2024-02-19 1556413.png" alt=""><figcaption><p>Set an A record</p></figcaption></figure>

Finally, click on **Submit**.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-19 155613.png" alt=""><figcaption><p>Click on Submit</p></figcaption></figure>

{% embed url="https://youtu.be/nwWlbX_445w" %}
Custom Domain Setup
{% endembed %}
