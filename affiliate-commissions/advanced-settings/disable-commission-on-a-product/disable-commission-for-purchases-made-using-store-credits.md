# Disable Commission on Store Credit Purchases

**GoAffPro** provides you with the option to disable the commission for sales made using store credits.&#x20;

To disable commission on sales made using store credits, go to the **Commission Modifiers** section in the **Commissions** tab of the GoAffPro admin panel.

<figure><img src="../../../.gitbook/assets/image (202).png" alt=""><figcaption><p>Commissions > Commission modifiers</p></figcaption></figure>

Here, click on **Add new modifier**.

![Click on Add new modifier](<../../../.gitbook/assets/Screenshot 2020-12-22 193418.png>)

Now, select the "Payment gateway matches" rule.

![Select the "Payment gateway matches" rule](<../../../.gitbook/assets/Screenshot 2020-12-22 193544.png>)

After this, set the "matches" value to Store Credits.

{% hint style="info" %}
You can set the value to any payment gateway for which you want to disable the commission.&#x20;

For example, if you want to prevent commissions on sales made using gift cards, you can set the matching value as **gift\_card** (which is the technical name of the gift card payment gateway in Shopify).&#x20;
{% endhint %}

![Set the "matches" value to store credits](<../../../.gitbook/assets/Screenshot 2020-12-22 193731.png>)

Now, set the "adjust commission by" percentage to -100%.

![Set adjust commission by percentage to -100%](<../../../.gitbook/assets/Screenshot 2020-12-22 193935.png>)

Finally, click on **Add Modifier**.

![Click on Add Modifier](<../../../.gitbook/assets/Screenshot 2020-12-22 194058.png>)

The newly set commission modifier will prevent commissions from being calculated on sales made using store credits.&#x20;

![](<../../../.gitbook/assets/image (2198).png>)

{% embed url="https://www.youtube.com/watch?v=_dJYh-zbQAk" %}
Disable Commission for Purchases made with Store Credits
{% endembed %}
