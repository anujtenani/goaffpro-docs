# Test Commission Booster

### To test how a commission booster works:&#x20;

### Setup commission booster

Go to the **Commission Booster** section of the **Targets** tab in the GoAffPro admin panel and click on **Configure**.

![Targets > Commission Booster > Click on Configure](<../../.gitbook/assets/Annotation 2020-08-04 142232.png>)

Now, click on **New Boost**.

![Click on New Boost](<../../.gitbook/assets/Annotation 2020-08-04 141837.png>)

After this, set up the commission booster settings and click on **Save**.

![Set up commission booster and save](<../../.gitbook/assets/Annotation 2020-08-04 142053.png>)

The commission booster that has been set here has the following settings:

* Name: Booster One
* Time Period: This month (Current Month)
* Applies on: Sale Commission
* Minimum Value:  ₹100 (this can vary according to your currency)
* Boost: 25%

This commission booster will provide a 25% boost to the existing commission rate of the affiliate after the affiliate earns ₹100 in sales commission. The booster will only apply to the sales commission earned in the current month.&#x20;

{% hint style="info" %}
For example: If the commission rate of the affiliate is set to 10% by default, then, if the affiliate crosses the minimum value of ₹100 in sales commission in the current month. The affiliate will get a 25% commission boost on his existing commission, that is, 25% of 10% = 12.5%.&#x20;
{% endhint %}

![Commission booster](<../../.gitbook/assets/image (938).png>)

### Create a test product & order

#### Create test product

To create a test product, go to the **Products** section of the Shopify panel.&#x20;

Here, create a new product with the following values:

* Title: Product A
* Pricing: ₹1000
* Quantity: 2

![Create a test product](<../../.gitbook/assets/image (2359).png>)

#### Create test orders

To create the test orders, go to the **Orders** section of the Shopify panel. Here, create two orders with Product A as the item and mark the order as paid.

{% hint style="info" %}
For Example: we have created orders #1016 and #1017, which have product A as the item purchased.&#x20;
{% endhint %}

![Create test orders](<../../.gitbook/assets/image (846).png>)

### Assign orders to affiliate & check the commission boost:

#### Assign the sale to the affiliate

Click on **create a new sale manually**, in the **All Sales** section of the **Sales** tab in the GoAffPro admin panel.

![Click on create a new sale manually](<../../.gitbook/assets/Annotation 2020-08-04 153119.png>)

Now, select the order number #1016 and the test affiliate. After this, click on **Assign Sale**.

{% hint style="info" %}
Repeat the process for the order number #1017.&#x20;

To create a test affiliate account, follow this [guide](https://docs.goaffpro.com/how-tos/create-an-affiliate-account).
{% endhint %}

![Assign the sale to the affiliate](<../../.gitbook/assets/Annotation 2020-08-04 153301.png>)

Finally, the orders will appear in the Sales tab.&#x20;

![Test Orders](<../../.gitbook/assets/image (1884).png>)

#### Check commission boost

The sales commission for order #1016 is ₹100 (10% commission rate). This makes the affiliate eligible for the commission booster, as the affiliate has achieved the minimum value set for the commission booster (the minimum value is set as ₹100).

The commission on order #1017 is ₹125, for which the commission booster has been applied. The default commission of 10% has been boosted by 25% which makes it 12.5% (12.5% of ₹1000 = ₹125).

![Commission for the orders](<../../.gitbook/assets/Annotation 2020-08-04 160641 (1).png>)

Click on the order number #1017 to open the order summary.

![Click on the order number](<../../.gitbook/assets/Annotation 2020-08-04 160641.png>)

The order summary for order #1017 shows us that a commission boost of ₹25 has been credited to the affiliate for that sale.&#x20;

{% hint style="info" %}
The default commission of 10% has been boosted by 25% (by the commission booster) which has made it 12.5% (10% of ₹1000 + 25% of ₹100 = ₹125).
{% endhint %}

![](<../../.gitbook/assets/Annotation 2020-08-04 160935.png>)

{% embed url="https://youtu.be/aLyhr6-N_Dg" %}
Test Commission Booster
{% endembed %}
