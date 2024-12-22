# CSS Customizations

### Here are some CSS customizations that you can make in your affiliate portal:

### Remove badges from the affiliate dashboard

To remove the badges showcasing the commission rate and the discount value of the coupon from the affiliate dashboard:

<figure><img src="../../.gitbook/assets/Screenshot 2023-03-13 130456.png" alt=""><figcaption><p>Affiliate dashboard badges</p></figcaption></figure>

Go to the Look and Feel > Affiliate Dashboard > Custom CSS section and paste the following code in there:

```css
.badge {
visibility: hidden;
}
```

After this, click on **Submit**.

<figure><img src="../../.gitbook/assets/Screenshot 2023-03-13 130530.png" alt=""><figcaption><p>Add the code and click on Submit</p></figcaption></figure>

The badges will be removed from the affiliate dashboard.&#x20;

<figure><img src="../../.gitbook/assets/image (3142).png" alt=""><figcaption></figcaption></figure>

### Remove overlay from the landing page banner

To remove the overlay from the landing page banner:

<figure><img src="../../.gitbook/assets/Screenshot 2023-03-22 003932.png" alt=""><figcaption><p>Banner overlay</p></figcaption></figure>

Go to the Look and Feel > Affiliate Dashboard > Custom CSS section and paste the following code in there:

```css
#hero_background { 
background-blend-mode: lighten !important;
 }
```

After this, click on **Submit**.

<figure><img src="../../.gitbook/assets/Screenshot 2023-03-22 004354.png" alt=""><figcaption><p>Add the code and click on Submit</p></figcaption></figure>

The overlay will be removed from the landing page banner.

<figure><img src="../../.gitbook/assets/image (2094).png" alt=""><figcaption></figcaption></figure>

### Customize the color of the affiliate portal footer

To customize the color of the footer section:

<figure><img src="../../.gitbook/assets/Screenshot 2023-04-06 235727.png" alt=""><figcaption><p>Affiliate portal footer</p></figcaption></figure>

Go to the Look and Feel > Affiliate Dashboard > Custom CSS section and paste the following code in there:

```css
.bg-light.border-top.border {
background-color: #xxxxxx !important;
}

/* Replace the #xxxxxx with the hex color of your choice */
```

<figure><img src="../../.gitbook/assets/Screenshot 2023-04-07 000615.png" alt=""><figcaption><p>Add the code and click on Submit</p></figcaption></figure>

The footer color will get set as per the color you set (in the code).

<figure><img src="../../.gitbook/assets/image (1589).png" alt=""><figcaption></figcaption></figure>

## Align the signup page heading to the center&#x20;

To align the signup page heading to the center:

<figure><img src="../../.gitbook/assets/Screenshot 2024-01-01 142006.png" alt=""><figcaption><p>Signup page heading</p></figcaption></figure>

Go to the Look and Feel > Affiliate Dashboard > Custom CSS section and paste the following code in there:

```css
.text_on_bg {
    text-align: center;
}
```

<figure><img src="../../.gitbook/assets/Screenshot 2024-01-01 1432123.png" alt=""><figcaption><p>Add the code and click on Submit</p></figcaption></figure>

The heading on the signup page will get centered.&#x20;

{% hint style="info" %}
This will also apply to the heading on the login page of the affiliate portal.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (3376).png" alt=""><figcaption></figcaption></figure>
