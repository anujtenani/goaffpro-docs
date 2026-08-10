# Custom SDK Integration

#### Integrate GoAffPro with your custom store:&#x20;

Create a GoAffPro merchant account: [Signup Link](https://goaffpro.com/signup?redirect=/merchant)

{% hint style="info" %}
If you already have an account, you can [login](https://goaffpro.com/login?redirect=/merchant).
{% endhint %}

![Signup Page](<../../../.gitbook/assets/image (2229).png>)

Here, click on **Add Your First Store**.

<figure><img src="../../../.gitbook/assets/Screenshot 2026-08-10 223821.png" alt=""><figcaption><p>Click on Add Your First Store</p></figcaption></figure>

Now, select the custom integration option.

<figure><img src="../../../.gitbook/assets/Screenshot 2026-08-10 224122.png" alt=""><figcaption><p>Select Custom Integration option</p></figcaption></figure>

Next, enter the store name, store URL, and click on **Create Store**.

<figure><img src="../../../.gitbook/assets/image (3924).png" alt=""><figcaption><p>Enter store name and URL> Click on Create Store</p></figcaption></figure>

After this, click on **View Integration steps**.

<figure><img src="../../../.gitbook/assets/Screenshot 2026-08-10 2300348.png" alt=""><figcaption><p>Click on View Integration Steps</p></figcaption></figure>

Here, add the general tracking code in the header section before the closing \</head> tag.

{% hint style="info" %}
This is usually pasted in the theme's layout file.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (3341).png" alt=""><figcaption><p>Add general tracking code</p></figcaption></figure>

Now, add the conversion tracking code to the conversion page or the "thank you" page.

{% hint style="info" %}
Please ensure that the goaffproOrder object in the conversion tracking code has the actual order data of the customer.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (3342).png" alt=""><figcaption><p>Add conversion tracking code</p></figcaption></figure>

Finally, click on **Get Started**.&#x20;

{% hint style="info" %}
This will open up the setup wizard for the program.&#x20;
{% endhint %}

![Click on Get Started](<../../../.gitbook/assets/Screenshot 2022-02-12 060558.png>)

{% hint style="info" %}
You can also look into the advanced integration guide: [Link](https://github.com/anujtenani/goaffpro/wiki/Custom-Integration-advanced-guide)
{% endhint %}
