# Create SPF Record

**GoAffPro** provides you with the option to create an SPF record.&#x20;

{% hint style="info" %}
SPF DNS records verify the authenticity of emails from your domain, ensuring they are not marked as spam by the recipient's email provider.
{% endhint %}

To create an SPF record, go to the **Notifications** section in the **Settings** tab of the GoAffPro admin pane.

<figure><img src="../../.gitbook/assets/image (139).png" alt=""><figcaption><p>Settings > Notifications</p></figcaption></figure>

Here, go to the **From Email** section.

<figure><img src="../../.gitbook/assets/image (140).png" alt=""><figcaption><p>From Email</p></figcaption></figure>

Now, click on **SPF Record**.

<figure><img src="../../.gitbook/assets/Screenshot 2025-05-27 2320435.png" alt=""><figcaption><p>Click on SPF Record</p></figcaption></figure>

After this, you can add the following values based on your SPF record.

**If you already have an SPF TXT Record, add the following to your existing record:**

```
include:amazonses.com
```

**If you do not have an SPF TXT record, add the following as a new SPF TXT record to your domain:**

```
v=spf1 include:amazonses.com ~all
```

<figure><img src="../../.gitbook/assets/image (141).png" alt=""><figcaption><p>SPF Record</p></figcaption></figure>
