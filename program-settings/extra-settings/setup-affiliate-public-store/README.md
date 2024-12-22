# Setup Affiliate Public Store

**GoAffPro** provides you with the option to set up the affiliate public store for your affiliates.

{% hint style="info" %}
The affiliate public store option offers affiliates a one-page replicated store. Affiliates can share the public store page with their customers for placing orders.
{% endhint %}

To set up the affiliate public store for your affiliates, go to the **Extras** section in the **Settings** tab of the GoAffPro admin panel.&#x20;

<figure><img src="../../../.gitbook/assets/image (53).png" alt=""><figcaption><p>Settings > Extras</p></figcaption></figure>

Here, go to the Affiliate Public Store section.

![Affiliate Public Store](<../../../.gitbook/assets/Screenshot 2021-10-19 1316272.png>)

Now, click on **Setup**.

![Click on Setup](<../../../.gitbook/assets/Screenshot 2021-10-19 125434 (3).png>)

This will open up the Setup Affiliate public store window.

![Setup Affiliate public store](<../../../.gitbook/assets/image (1946).png>)

Enter the storefront access token.

**To generate the storefront access token, you can follow the guide below:**

{% content-ref url="generate-storefront-access-token.md" %}
[generate-storefront-access-token.md](generate-storefront-access-token.md)
{% endcontent-ref %}

![Enter the storefront access token](<../../../.gitbook/assets/Screenshot 2021-10-19 131833223.png>)

Now, set the shop domain.

{% hint style="info" %}
The shop domain should be set up as a subdomain of your store. For example, you can set it up as shop.example.com or store.example.com.&#x20;
{% endhint %}

![Set shop domain](<../../../.gitbook/assets/Screenshot 2021-10-19 132159.png>)

After this, click on **Submit**.

![Click on Submit](<../../../.gitbook/assets/Screenshot 2021-10-19 132541.png>)

Finally, create a CNAME record in your domain provider's dashboard with the following values:

<table><thead><tr><th>Name</th><th>Points to</th><th data-hidden></th></tr></thead><tbody><tr><td>shop</td><td>shop.goaffpro.com</td><td></td></tr></tbody></table>

![Create CNAME record](<../../../.gitbook/assets/Screenshot 2021-10-19 133511.png>)

The public store will now start working.

![](<../../../.gitbook/assets/image (2258).png>)
