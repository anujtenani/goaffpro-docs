# Embed Signup Page

#### To embed the signup page of the affiliate portal on your store, follow the steps given below:&#x20;

* In your Shopify control panel, click on **Online Store**, after this click on the **Pages** tab.&#x20;
* Now to create a new page click on the **Add page** button

![Add Page](<../../../.gitbook/assets/Annotation 2019-12-17 021419.png>)

* In the **Add page** window, click on the code input mode (**Show HTML**) in the editor.

![Click on Show HTML button ](<../../../.gitbook/assets/Annotation 2019-12-17 021952.png>)

* Here write the following code in the editor:

```markup
<iframe src="https://helloworld.goaffpro.com/create-account" 
        id="affiliate_page"></iframe>
<script type="text/javascript" src="https://static.goaffpro.com/embed.js"></script>
```

{% hint style="info" %}
You must change the **src** property of **iframe** with the link of your affiliate portal's signup page that changes **https://helloworld.goaffpro.com/create-account** with your own affiliate portal's signup page link in the code above.
{% endhint %}

* After writing the code, click on **Save** to save the page.

![Write Code and Save](<../../../.gitbook/assets/Annotation 2019-12-17 022318 (1).png>)
