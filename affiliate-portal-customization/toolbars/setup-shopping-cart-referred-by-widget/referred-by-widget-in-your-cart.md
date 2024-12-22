---
description: Custom Integration tutorial for "Referred By" widget in your store theme
---

# Referred By Widget Integration

### Custom integration

Normally, the "Referred by" widget gets added when you turn it on in the **Toolbars** section of the **Look and Feel** tab. However, if you are using a custom theme and the widget does not appear in your cart page, you can add it using the following guide:

Open your store's cart template file and add the following code wherever you want the widget to appear.

```markup
<div id="gfp_referred_by"></div>
```

That's it. The widget will appear now.

### Advanced Customization (for advanced users)

If you want to customize the widget as per your requirement, the widget script only requires the presence of an input field with id **gfp\_refcode\_input** for it to work.&#x20;

So instead of adding the code as shown in the custom integration you can add the following code as well:

```markup
<div>
<label>Referred By</label>
<input type="text" id="gfp_refcode_input" /> 
</div>
```

So, in effect any piece of code with:

```markup
<input type="text" id="gfp_refcode_input" /> 
```

It will be sufficient enough for the widget to work.
