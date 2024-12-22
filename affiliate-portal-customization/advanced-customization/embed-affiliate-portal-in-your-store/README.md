# Embed Affiliate Portal In Your Store

Usually, the affiliate portal is loaded up on a separate domain. However, you can choose to embed the affiliate portal in your store.&#x20;

#### You can do this by following the steps given below:

* In your Shopify control panel, click on **Online Store**, after this click on the **Pages** tab.&#x20;
* Now to create a new page click on the **Add page** button

![Add Page](<../../../.gitbook/assets/Annotation 2019-12-17 021419.png>)

* In the **Add page** window, click on the code input mode (**Show HTML**) in the editor.

![Click on Show HTML button ](<../../../.gitbook/assets/Annotation 2019-12-17 021952.png>)

* Here write the following code in the editor:

```markup
<iframe src="https://helloworld.goaffpro.com" 
        id="affiliate_page"></iframe>
<script type="text/javascript" src="https://static.goaffpro.com/embed.js"></script>
```

{% hint style="info" %}
You must change the **src** property of **iframe** with a link to your affiliate portal. i.e. change [https://helloworld.goaffpro.com](https://helloworld.goaffpro.com/create-account) with your own affiliate portal's link in the code above.
{% endhint %}

* After writing the code, click on **Save** to save the page.

![Write Code and Save](<../../../.gitbook/assets/Annotation 2019-12-17 022318.png>)
