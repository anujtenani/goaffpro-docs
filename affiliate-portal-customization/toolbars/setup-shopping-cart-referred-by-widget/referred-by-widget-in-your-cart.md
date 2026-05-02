---
description: Custom Integration tutorial for "Referred By" widget in your store theme
---

# Referred By Widget Integration

#### To integrate the shopping cart referred by widget in your store theme:&#x20;

Go to the Online Store section in the Shopify admin panel.&#x20;

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-23 1334341.png" alt=""><figcaption><p>Shopify admin panel > Online Store</p></figcaption></figure>

Here, go to the Themes section and click on **Customize**.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-23 133453f.png" alt=""><figcaption><p>Themes > Click on Customize</p></figcaption></figure>

Now, go to the Home page > Select the Cart option.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-23 1335263.png" alt=""><figcaption><p>Home page > Cart option</p></figcaption></figure>

Next, click on **Add section**.

<figure><img src="../../../.gitbook/assets/Screenshot 2025-07-08 215847.png" alt=""><figcaption><p>Click on Add section</p></figcaption></figure>

After this, select the **Custom Liquid** option.

<figure><img src="../../../.gitbook/assets/Screenshot 2025-07-08 215920.png" alt=""><figcaption><p>Select the Custom Liquid option</p></figcaption></figure>

Now, open the Custom Liquid section.&#x20;

<figure><img src="../../../.gitbook/assets/Screenshot 2025-07-08 220033.png" alt=""><figcaption><p>Open the Custom Liquid section</p></figcaption></figure>

Copy the following code from Look and Feel > Toolbars > Shopping Cart Referred By section:

```html
<div class="gfp_ref_input"></div>
```

<figure><img src="../../../.gitbook/assets/Screenshot 2025-07-08 220117.png" alt=""><figcaption><p>Copy the tag</p></figcaption></figure>

Next, paste the code into the Custom Liquid box.

<figure><img src="../../../.gitbook/assets/Screenshot 2025-07-08 220140.png" alt=""><figcaption><p>Paste the code into the custom liquid box</p></figcaption></figure>

Finally, click on **Save**.

<figure><img src="../../../.gitbook/assets/Screenshot 2025-07-08 220256.png" alt=""><figcaption><p>Click on Save</p></figcaption></figure>

The referred by widget will be displayed on the cart page of your store.&#x20;

<figure><img src="../../../.gitbook/assets/Screenshot 2025-07-08 222018.png" alt=""><figcaption><p>The referred by widget will be displayed</p></figcaption></figure>

#### The Shopping Cart Referred by widget has three input types:

You can go to Look and Feel > Toolbars > Shopping Cart Referred By and click on **Customize**. Here, you can choose how to display the referred-by widget input.

<figure><img src="../../../.gitbook/assets/Screenshot 2025-07-08 2201137.png" alt=""><figcaption></figcaption></figure>

**Auto-Complete/Search Input:** Customers can enter an affiliate's name to search for them.

<figure><img src="../../../.gitbook/assets/Screenshot 2025-07-08 222726.png" alt=""><figcaption><p>Auto-Complete/Search Input</p></figcaption></figure>

**Affiliate List Dropdown:** A dropdown list will appear, allowing customers to select an affiliate.

<figure><img src="../../../.gitbook/assets/Screenshot 2025-07-08 222227.png" alt=""><figcaption></figcaption></figure>

**Referral Code Input:** The customer can enter the affiliate's referral code, which is the unique code found at the end of the affiliate's referral link.

<figure><img src="../../../.gitbook/assets/Screenshot 2025-07-08 222426.png" alt=""><figcaption></figcaption></figure>

<details>

<summary>Advanced Customization</summary>

If you want to customize the widget to meet your needs, the widget script requires only an input field with the id **gfp\_refcode\_input** for it to function properly.

Instead of adding the code as shown in the custom integration, you can add the following code as well:

```markup
<div>
<label>Referred By</label>
<input type="text" id="gfp_refcode_input" /> 
</div>
```

In effect any piece of code with:&#x20;

```markup
<input type="text" id="gfp_refcode_input" /> 
```

It will be sufficient for the widget to function properly.

</details>

{% embed url="https://youtu.be/hfWHbbil2ps" %}
Referred By Widget Integration
{% endembed %}
