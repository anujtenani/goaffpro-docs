---
description: For Shopify Merchants Only
---

# Advanced Customization for Embedding

You can make the portal look better integrated by adding a new theme asset, with a few more tweaks to your Shopify page.

* Firstly, open the **Themes** tab in the Shopify control panel. Here select the **Edit Code** in the **Actions** drop-down menu.

![Themes > Actions > Edit Code](<../../../.gitbook/assets/Annotation 2019-12-17 024312.png>)

* After this select **Add a new template**.

![Add a new template](<../../../.gitbook/assets/Annotation 2019-12-17 024906.png>)

* Here select the **page** and name it **goaffpro.** After this click on the **Create template** button.

![page > goaffpro > Create template](<../../../.gitbook/assets/Annotation 2019-12-17 025214.png>)

* You will now replace the code of the new template with the following code. After doing so, you will click on **Save** to save the template.

```markup
<section style="min-width:'100%'">{{page.content}}</section>
```

![Write Code > Save](<../../../.gitbook/assets/Annotation 2019-12-17 025823.png>)

* After this, open your newly created page in the **Pages** tab of the Shopify control panel.

![Pages tab > Affiliate Portal Page ](<../../../.gitbook/assets/Annotation 2019-12-17 030549.png>)

* Here change the page's template to **page.goaffpro**. Click on **Save** to save the changes.

![Template > page.goaffpro > Save](<../../../.gitbook/assets/Annotation 2019-12-17 031032.png>)
