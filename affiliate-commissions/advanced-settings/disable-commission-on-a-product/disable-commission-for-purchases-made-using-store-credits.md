# Disable Commission on Store Credit Purchases

**GoAffPro** provides you with the option to disable the commission for sales made using store credits.&#x20;

To disable commission on sales made using store credits, go to the **Commission Modifiers** section in the **Commissions** tab of the GoAffPro admin panel.

<figure><img src="../../../.gitbook/assets/image (202) (1).png" alt=""><figcaption><p>Commissions > Commission modifiers</p></figcaption></figure>

Here, click on **Add new modifier**.

![Click on Add new modifier](<../../../.gitbook/assets/Screenshot 2020-12-22 193418.png>)

Now, select the "Payment gateway matches" rule.

![Select the "Payment gateway matches" rule](<../../../.gitbook/assets/Screenshot 2020-12-22 193544.png>)

After this, set the "matches" value to Store Credits.

{% hint style="info" %}
You can set the value to any payment gateway for which you want to disable the commission.&#x20;

For example, if you want to prevent commissions on sales made with gift cards, you can set the matching value as "**gift\_card**" which is the technical name for the gift card payment gateway in Shopify. Similarly, to prevent commissions on sales made using Shopify store credits, you can set the matching value as "**shopify\_store\_credit**"
{% endhint %}

![Set the "matches" value to store credits](<../../../.gitbook/assets/Screenshot 2020-12-22 193731.png>)

Now, set it to "adjust commission by" -100%.

![Set it to "adjust commission by" -100%](<../../../.gitbook/assets/Screenshot 2020-12-22 193935.png>)

Finally, click on **Add Modifier**.

![Click on Add Modifier](<../../../.gitbook/assets/Screenshot 2020-12-22 194058.png>)

The newly set commission modifier will prevent commissions from being calculated on sales made using store credits.&#x20;

![](<../../../.gitbook/assets/image (2198).png>)

{% embed url="https://www.youtube.com/watch?v=_dJYh-zbQAk" %}
Disable Commission for Purchases made with Store Credits
{% endembed %}
