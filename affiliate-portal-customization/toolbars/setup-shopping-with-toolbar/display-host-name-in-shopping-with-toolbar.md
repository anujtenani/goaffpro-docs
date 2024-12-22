# Display Host Name in Shopping-With Toolbar

### To display the host's name in the Shopping-with Toolbar:

You can use the template tag \{{host\}} to display the host name in the shopping-with toolbar.&#x20;

To set it up, go to the Look and Feel > Toolbars > Shopping-with Toolbar > Click on **Customize**. Here, paste the following in the content field:

You are shopping with the \{{affiliate\_name\}} \{{#host\}} and the event host \{{name\}}\{{/host\}}

{% hint style="info" %}
The \{{#host\}} block is conditional. The text inside it is displayed only for party events.
{% endhint %}

<figure><img src="../../../.gitbook/assets/Screenshot 2024-07-09 163150.png" alt=""><figcaption><p>Display the affiliate and host name</p></figcaption></figure>

Example: If the affiliate's name is John and the host's name is Dan.

When opened as a regular link, it will display:\
**You are shopping with John**

When opened as a party link, it will display: \
**You are shopping with John and the event host Dan**

<figure><img src="../../../.gitbook/assets/image (3572).png" alt=""><figcaption><p>You are shopping with Affiliate name and Host name</p></figcaption></figure>

#### If you want to display either the name of the affiliate or the name of the host, you can set it to:

You are shopping with {^host\}}\{{affiliate\_name\}}\{{/host\}}\{{#host\}}\{{name\}}\{{/host\}}

<figure><img src="../../../.gitbook/assets/Screenshot 2024-07-09 163150 (1).png" alt=""><figcaption><p>Display the affiliate name or host name</p></figcaption></figure>

With the regular link, it displays:\
**You are shopping with John**

With the party link, it displays:\
**You are shopping with Dan**

<figure><img src="../../../.gitbook/assets/image (3573).png" alt=""><figcaption><p>You are shopping with Host name</p></figcaption></figure>
