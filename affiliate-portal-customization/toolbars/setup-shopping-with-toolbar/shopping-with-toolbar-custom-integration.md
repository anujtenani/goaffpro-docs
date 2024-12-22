# Shopping-with Toolbar Custom Integration

**GoAffPro** provides you with the option of custom integration of the Shopping-with Toolbar in the store.

To use custom integration of the Shopping-with Toolbar, go to the **Online Store** section in the Shopify dashboard.

![Online Store](<../../../.gitbook/assets/Annotation 2020-04-17 105815.png>)

Here, go to the Themes tab.

![Themes](<../../../.gitbook/assets/Annotation 2020-04-17 110440.png>)

Now, click on **Actions** and select **Edit code** in the Current theme section.

![Current theme > Actions > Edit code](<../../../.gitbook/assets/Annotation 2020-04-17 110341.png>)

This will open up the Edit code section

![Edit code](<../../../.gitbook/assets/image (2839).png>)

Now, open up the theme.liquid section and embed the following code wherever you want the Shopping-with Toolbar to appear:

```
 <div id="gfp_affbar"></div>
```

After this, click on **Save**.&#x20;

![theme.liquid](<../../../.gitbook/assets/Annotation 2020-04-17 112212.png>)

#### For Example:

By default, the Shopping-with Toolbar gets displayed at the top of the store.

![Shopping-with Toolbar](<../../../.gitbook/assets/image (2799).png>)

Here we want the Shopping-with Toolbar to appear below the main menu section.

Now, embed the following code in the theme.liquid section accordingly:

```
 <div id="gfp_affbar"></div>
```

![Embed the code](<../../../.gitbook/assets/Annotation 2020-04-17 114759.png>)

Click on **Save.**

![Click on Save](<../../../.gitbook/assets/Annotation 2020-04-17 114759 (2).png>)

After this, the Shopping-with Toolbar will appear below the main menu section.&#x20;

![](<../../../.gitbook/assets/Annotation 2020-04-17 115215.png>)
