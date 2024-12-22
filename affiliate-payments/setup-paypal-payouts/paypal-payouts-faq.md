# PayPal Payouts FAQ

## My PayPal Payouts Integration is not working:

In the case that your PayPal Payouts integration is not working. Check the following:

* Your PayPal account is a business account&#x20;
* You are using **Live** credentials and not Sandbox credentials.

<figure><img src="../../.gitbook/assets/Screenshot 2024-01-15 1340356.png" alt=""><figcaption><p>Use Live Credentials</p></figcaption></figure>

## The Send Money button is greyed out:

In the case that the **Send Money** button is greyed (not clickable), make sure that you have entered "confirm" in the confirmation field.

{% hint style="info" %}
This only applies to merchants who are on the old payment module.&#x20;
{% endhint %}

![Type "confirm" in the confirmation field](<../../.gitbook/assets/Screenshot 2020-10-05 220705.png>)

## Common Errors

#### Payment Errors

Make sure you have sufficient funds in your PayPal account.

#### "Your account is not authorized to use payouts" Error

You will have to contact PayPal customer service to get the Payouts API activated on your account.

<figure><img src="../../.gitbook/assets/image (3396).png" alt=""><figcaption><p>Payouts API error</p></figcaption></figure>

#### Validation Error

If you are getting a validation error, make sure that affiliates don't have their PayPal email address set up with paypal.me (PayPal Payouts does not support paypal.me email addresses).

![](<../../.gitbook/assets/Annotation 2020-08-19 221118 (2).png>)
