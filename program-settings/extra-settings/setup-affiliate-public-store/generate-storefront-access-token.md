# Generate Storefront Access Token

#### Generate the storefront access token for setting up the affiliate public store:

To generate the storefront access token, install the [Headless channel](https://apps.shopify.com/headless) from the Shopify app store.&#x20;

<figure><img src="../../../.gitbook/assets/Screenshot 2026-01-06 151125.png" alt=""><figcaption><p>Install the Headless channel from the Shopify app store</p></figcaption></figure>

This will open up the Storefronts section.

<figure><img src="../../../.gitbook/assets/image (45).png" alt=""><figcaption><p>Storefronts</p></figcaption></figure>

Here, click on **Create storefront**.&#x20;

<figure><img src="../../../.gitbook/assets/Screenshot 2026-01-06 151404.png" alt=""><figcaption><p>Click on Create Storefront</p></figcaption></figure>

To access the Storefront API, click on **Manage**.

<figure><img src="../../../.gitbook/assets/Screenshot 2026-01-06 151420.png" alt=""><figcaption><p>Storefront API > Click on Manage</p></figcaption></figure>

This will open up the Storefront API section.

<figure><img src="../../../.gitbook/assets/image (46).png" alt=""><figcaption><p>Storefront API</p></figcaption></figure>

Next, click on **Edit** to update the Storefront API permissions.

<figure><img src="../../../.gitbook/assets/Screenshot 2026-01-06 151449.png" alt=""><figcaption><p>Storefront API permissions > Click on Edit</p></figcaption></figure>

After this, enable the "unauthenticated\_read\_product\_inventory" permission.&#x20;

{% hint style="info" %}
The following Storefront API permissions need to be enabled:&#x20;

* unauthenticated\_read\_product\_listings
* unauthenticated\_read\_product\_inventory
* unauthenticated\_read\_product\_tags
* unauthenticated\_read\_customers
* unauthenticated\_write\_customers
* unauthenticated\_read\_content
* unauthenticated\_read\_checkouts
* unauthenticated\_write\_checkouts

Please note that most of these permissions are enabled by default.
{% endhint %}

<figure><img src="../../../.gitbook/assets/Screenshot 2026-01-06 151504.png" alt=""><figcaption><p>Enable the "unauthenticated_read_product_inventory" permission</p></figcaption></figure>

Finally, click on **Save**.

<figure><img src="../../../.gitbook/assets/Screenshot 2026-01-06 151516.png" alt=""><figcaption><p>Click on Save</p></figcaption></figure>

You can copy the generated storefront API access token and use it to set up the affiliate public store.&#x20;

<figure><img src="../../../.gitbook/assets/Screenshot 2026-01-06 15152942.png" alt=""><figcaption></figcaption></figure>

{% embed url="https://youtu.be/7vOPVxdIjd0" %}
Generate Storefront Access Token
{% endembed %}
