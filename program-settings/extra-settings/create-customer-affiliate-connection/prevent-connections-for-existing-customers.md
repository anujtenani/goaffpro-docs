# Prevent Connections for Existing Customers

**GoAffPro** provides you with the option to prevent customer-affiliate connections from getting created for existing store customers.

### Create and set up the dummy affiliate account

#### Create affiliate account

Go to the **All Affiliates** section in the **Affiliates** tab of the GoAffPro admin panel.

![Affiliates > All Affiliates](<../../../.gitbook/assets/image (792).png>)

Here, click on **Create New Affiliate**.

![Click on Create New Affiliate](<../../../.gitbook/assets/Screenshot 2021-02-02 222056.png>)

Now, enter the affiliate's name and email address.

{% hint style="info" %}
Also, uncheck the "Send Invitation Email" option.
{% endhint %}

![Enter the affiliate's name and email](<../../../.gitbook/assets/Screenshot 2021-02-02 222257.png>)

After this, click on **Create**.

![Click on Create](<../../../.gitbook/assets/Screenshot 2021-02-02 222543.png>)

Click on **Approve** to approve the affiliate account.

![Click on Approve](<../../../.gitbook/assets/Screenshot 2021-02-02 232154.png>)

#### Set commission rate of the affiliate account to zero

Go to the Commissions section.

![Commissions](<../../../.gitbook/assets/image (912).png>)

Here, click on **Change**.

![Click on Change](<../../../.gitbook/assets/Screenshot 2021-02-02 232442.png>)

Now, set the commission rate to zero.

![Set commission rate to zero](<../../../.gitbook/assets/Screenshot 2021-02-02 232652.png>)

After this, click on **OK**.

![Click on OK](<../../../.gitbook/assets/Screenshot 2021-02-02 233024.png>)

The commission rate of the dummy affiliate account will be set to zero.

![Commission Rate](<../../../.gitbook/assets/image (942).png>)

#### Uncheck the "Record Nil Sales" option (Optional)

Now, go to the **General** Section in the **Settings** tab.

![Settings > General](<../../../.gitbook/assets/image (1009).png>)

Here, uncheck the "Record Nil Sales" option.

![Uncheck the "Record Nil Sales" option](<../../../.gitbook/assets/Screenshot 2021-02-02 230510.png>)

Since the dummy affiliate's commission rate is set to zero, unchecking the "Record Nil Sales" option will prevent any sales with zero commissions from getting recorded.&#x20;

![](<../../../.gitbook/assets/image (1640).png>)

### Create connections with the dummy affiliate&#x20;

Go to the **Connections** tab.

{% hint style="info" %}
You can enable the Customer-Affiliate Connect option from the Settings > Extras section.
{% endhint %}

![Connections](<../../../.gitbook/assets/image (2625).png>)

Here, click on **bulk import**.

![Click on bulk import](<../../../.gitbook/assets/Screenshot 2021-02-02 224521.png>)

Now, click on **Browse** to upload the bulk import file.

{% hint style="info" %}
You can download the Sample CSV file to prepare the bulk import file.
{% endhint %}

![Click on Browse](<../../../.gitbook/assets/Screenshot 2021-02-02 224746.png>)

Setup the bulk import file by adding the name and email address of existing store customers with the email address of the dummy affiliate account.

![Setup the bulk import file](<../../../.gitbook/assets/Screenshot 2021-02-02 225302.png>)

After uploading the bulk import file, click on **Bulk Import**.

![Click on Bulk Import](<../../../.gitbook/assets/Screenshot 2021-02-02 225759.png>)

Finally, the customer-affiliate connections with all the existing store customers and the dummy affiliate will get created.

![](<../../../.gitbook/assets/image (710).png>)
