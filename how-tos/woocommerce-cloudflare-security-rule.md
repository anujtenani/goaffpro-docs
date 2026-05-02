---
description: For WooCommerce merchants only
---

# WooCommerce Cloudflare Security Rule

### To set up a custom security rule for GoAffPro, if you are using Cloudflare:&#x20;

Open your Cloudflare dashboard and go to the Security > Security rules section.&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2025-10-08 185855.png" alt=""><figcaption><p>Cloudflare dashboard > Security > Security Rules section</p></figcaption></figure>

Now, click on **Create rule**.

<figure><img src="../.gitbook/assets/Screenshot 2025-10-08 190108.png" alt=""><figcaption><p>Click on Create rule</p></figcaption></figure>

Next, select the custom rules option.

<figure><img src="../.gitbook/assets/Screenshot 2025-10-08 190315.png" alt=""><figcaption><p>Select the custom rules option</p></figcaption></figure>

Here, set the rule name.

<figure><img src="../.gitbook/assets/Screenshot 2025-10-08 190401.png" alt=""><figcaption><p>Set the rule name</p></figcaption></figure>

Now, select the "**User Agent**" field.

<figure><img src="../.gitbook/assets/Screenshot 2025-10-08 190519.png" alt=""><figcaption><p>Select the "User Agent" field</p></figcaption></figure>

Next, select the "**contains**" operator.&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2025-10-08 190617.png" alt=""><figcaption><p>Select the "contains" operator</p></figcaption></figure>

After this, set "**goaffpro**" as the value.

<figure><img src="../.gitbook/assets/Screenshot 2025-10-08 190743.png" alt=""><figcaption><p>Set "goaffpro" as the value</p></figcaption></figure>

Now, choose the skip action.&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2025-10-08 190838.png" alt=""><figcaption><p>Select the skip action</p></figcaption></figure>

Select the following WAF components to skip:

* All remaining custom rules.
* All rate limiting rules.
* All managed rules
* All Super Both Fight Mode Rules.&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2025-10-08 190952.png" alt=""><figcaption><p>Select the WAF components to skip</p></figcaption></figure>

Finally, click on **Deploy**.

<figure><img src="../.gitbook/assets/Screenshot 2025-10-08 1909524.png" alt=""><figcaption><p>Click on Deploy</p></figcaption></figure>

The custom security rule will be created.&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2025-10-08 191051.png" alt=""><figcaption></figcaption></figure>

{% embed url="https://youtu.be/oXkudt0Gwnk" %}
WooCommerce Cloudflare Security Rule
{% endembed %}
