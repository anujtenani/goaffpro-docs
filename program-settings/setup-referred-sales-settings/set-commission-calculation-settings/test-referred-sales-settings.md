# Test Commission Calculation Settings

### To test the commission calculation settings, you can follow the steps provided below:

Go to the **General** section in the **Settings** tab of the GoAffPro admin panel.

![Settings > General](<../../../.gitbook/assets/image (2251).png>)

Here, go to the Sales section.

![Sales](<../../../.gitbook/assets/image (1513).png>)

Here, the "**Include discounts**" option is enabled and is set to adjust the commission by **discount percentage**.

![Adjust by discount percentage ](<../../../.gitbook/assets/Screenshot 2020-12-02 181211.png>)

In the test order's summary, we can see that the discount adjustment is deducting $20 from the sales commission: **$200 (sales commission) - $20 (discount adjustment) = $180 (total commission)**.&#x20;

The discount adjustment is calculated by the percentage of the discount applied (10%) on the sales commission ($200) which will be: **$20.**

{% hint style="info" %}
The commission rate of the affiliate is set to 20%.
{% endhint %}

![Order Summary](<../../../.gitbook/assets/Screenshot 2020-12-02 182623.png>)

After this, go back to the Sales section (in Settings > General) and set the "**Include discounts**" option to adjust the commission by **discount amount**.

![Adjust by discount amount](<../../../.gitbook/assets/Screenshot 2020-12-02 182915.png>)

After setting this up, the commission in the order will be adjusted by the discount amount.

![Sales settings](<../../../.gitbook/assets/Screenshot 2020-12-02 183354.png>)

Now, you will have to reprocess the order. To do that go to the Sales > All Sales table. There, click on **Reject** and **Delete** the sale. After this, re-assign the sale to the affiliate.

**You can follow the guide below to reprocess the sale:**

{% content-ref url="../../../program-management/manage-sales/reprocessing-sale/" %}
[reprocessing-sale](../../../program-management/manage-sales/reprocessing-sale/)
{% endcontent-ref %}

![Reprocess the sale](<../../../.gitbook/assets/Screenshot 2020-12-02 183600.png>)

In the test order's summary, we can see that the discount adjustment is deducting $100 from the sales commission: **$200 (sales commission) - $100 (discount adjustment) = $100 (total commission)**.&#x20;

The discount adjustment is calculated by the amount of the discount applied in the order: **10% (discount applied) of $1000 (order subtotal) = $100.**

![Order Summary](<../../../.gitbook/assets/Screenshot 2020-12-02 184904.png>)

{% hint style="info" %}
Similarly, different sales settings can be tested by enabling them and reprocessing the order to see how the commission will be calculated.&#x20;
{% endhint %}
