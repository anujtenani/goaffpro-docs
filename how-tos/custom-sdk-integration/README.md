# Custom SDK Integration

#### Integrate GoAffPro with your custom store:&#x20;

Create a GoAffPro merchant account: [Signup Link](https://goaffpro.com/signup?redirect=/merchant)

{% hint style="info" %}
If you already have an account, you can [login](https://goaffpro.com/login?redirect=/merchant).
{% endhint %}

![Signup Page](<../../.gitbook/assets/image (2229).png>)

Here, click on **Add app to store**.

![Click on Add app to store](<../../.gitbook/assets/Screenshot 2022-02-12 044704.png>)

Now, select the custom SDK option.

![Select Custom SDK option](<../../.gitbook/assets/Screenshot 2022-02-12 050142 (1).png>)

Next, enter the store name, store URL, and click on **Submit**.

![Enter store name and URL](<../../.gitbook/assets/image (1927).png>)

After this, click on **Integration steps**.

![Click on Integration Steps](<../../.gitbook/assets/Screenshot 2022-02-12 053746.png>)

Here, add the general tracking code in the header section before the closing \</head> tag.

{% hint style="info" %}
This is usually pasted in the theme's layout file.&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/image (3341).png" alt=""><figcaption><p>Add general tracking code</p></figcaption></figure>

Now, add the conversion tracking code to the conversion page or the "thank you" page.

{% hint style="info" %}
Please ensure that the goaffproOrder object in the conversion tracking code has the actual order data of the customer.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (3342).png" alt=""><figcaption><p>Add conversion tracking code</p></figcaption></figure>

Finally, click on **Get Started**.&#x20;

{% hint style="info" %}
This will open up the setup wizard for the program.&#x20;
{% endhint %}

![Click on Get Started](<../../.gitbook/assets/Screenshot 2022-02-12 060558.png>)

{% hint style="info" %}
You can also look into the advanced integration guide: [Link](https://github.com/anujtenani/goaffpro/wiki/Custom-Integration-advanced-guide)
{% endhint %}
