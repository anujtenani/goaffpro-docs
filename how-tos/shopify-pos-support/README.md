# Shopify POS Support

**GoAffPro** is compatible with the Shopify Point of Sale (POS) system. If you are operating a POS counter, you can utilize any of the following options to make the POS system work with our app:

### Use Order Tags

* When creating the order via the POS system, ask the customer for the affiliate's referral code, name, or email address.
* After that, you can write any of these as the **order tag** while creating the customer's order in the POS system.&#x20;
* Our system will automatically pick up the order and assign it to the affiliate.&#x20;

### Use Order Notes

* When creating the order via the POS system, ask the customer for the affiliate's referral code.
* After that, add the affiliate's referral code in the order notes while creating the customer's order in the POS system.
* Our system will automatically attribute the order to the affiliate.

### Use Customer-Affiliate Connect

* Before creating the order via the POS system, ask the customer for the affiliate's referral code, name, or email address.
* Use that to connect the customer's email address/account to the affiliate's account within our app.&#x20;
* After that, the order you create for the customer will automatically get attributed to the connected affiliate.&#x20;

**Here is the guide for creating a customer-affiliate connection in our app:**

{% content-ref url="../../program-settings/extra-settings/create-customer-affiliate-connection/" %}
[create-customer-affiliate-connection](../../program-settings/extra-settings/create-customer-affiliate-connection/)
{% endcontent-ref %}

### Assign Sale to Affiliate

* When creating the order via the POS system, you can ask the customer for the affiliate's referral code, name, or email address.
* After creating the order, you can open our app, go to the Sales > All Sales section, and click on **Create new sale manually**.
* Here, select the order number and the affiliate. Finally, click on Assign Order.

**Here is the guide for assigning the sale to the affiliate in our app:**

{% content-ref url="../../program-management/manage-sales/assign-sale-to-an-affiliate.md" %}
[assign-sale-to-an-affiliate.md](../../program-management/manage-sales/assign-sale-to-an-affiliate.md)
{% endcontent-ref %}

### Use Discount Codes

* When creating orders via the POS system, ask the customer if they have a discount code.
* After that, you can apply the discount code to the order.
* If the discount code belongs to an affiliate, the sale will automatically get attributed to them.

**Here is the guide for generating discount codes for affiliates automatically:**&#x20;

{% content-ref url="../../affiliate-coupons/setup-referral-coupons/automatically-generate-coupons/" %}
[automatically-generate-coupons](../../affiliate-coupons/setup-referral-coupons/automatically-generate-coupons/)
{% endcontent-ref %}

### Use User/Location IDs of POS Machine

#### POS Machine User ID for Order Mapping

* Every Shopify POS machine has user accounts. These user accounts have a unique user ID. You can map this **user ID** to the affiliate ID in the program.&#x20;
* Go to Settings > Advanced > Referral Link section and enable the Multiple Referral Codes option. Next, enter this user's ID as an additional referral code in their affiliate account.
* After that, whenever this user creates an order in the POS machine, it will automatically be attributed to their affiliate account.

**Here is the guide for setting the POS machine user ID as an additional referral code for the affiliate:**&#x20;

{% content-ref url="../../program-settings/referral-link-configuration/enable-multiple-referral-codes-for-affiliates/set-multiple-referral-codes.md" %}
[set-multiple-referral-codes.md](../../program-settings/referral-link-configuration/enable-multiple-referral-codes-for-affiliates/set-multiple-referral-codes.md)
{% endcontent-ref %}

#### POS Machine Location ID for Order Mapping

* If you have multiple retail locations, each with POS machines. You can map the **location ID** of the POS machine to the affiliate in the program.&#x20;
* Go to the Commissions > Royalty Commissions > Rule based tracking section. Here, create the rule with "Point of sale Source ID" option > set the location ID as the matching value, and select the affiliate.&#x20;
* After that, any sale made using that location's POS system will automatically be attributed to the affiliate.&#x20;

**Here is the guide for creating rule based tracking to map the POS machine location ID to the affiliate:**&#x20;

{% content-ref url="../../affiliate-commissions/advanced-settings/setup-rule-based-tracking-for-sales/" %}
[setup-rule-based-tracking-for-sales](../../affiliate-commissions/advanced-settings/setup-rule-based-tracking-for-sales/)
{% endcontent-ref %}
