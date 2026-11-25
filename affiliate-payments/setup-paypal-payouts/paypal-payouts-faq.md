---
hidden: true
---

# PayPal Payouts FAQ

## My PayPal Payouts Integration is not working:

In the case that your PayPal Payouts integration is not working. Check the following:

* Your PayPal account is a business account&#x20;
* You are using **Live** credentials and not Sandbox credentials.

<figure><img src="../../.gitbook/assets/Screenshot 2024-01-15 1340356.png" alt=""><figcaption><p>Use Live Credentials</p></figcaption></figure>

### ERROR TROUBLESHOOTING

#### PayPal Payouts IP Requirement

If you are having difficulties making payments to affiliates using PayPal payouts? The PayPal team now requires a fixed IP address to process payouts.

You can submit a support ticket with PayPal for issues with the Payouts API and provide them with the following two IP addresses:

* 2a01:4ff:f0:9b54::1&#x20;
* 5.161.205.57

#### AUTHORIZATION\_ERROR

Your PayPal account does not appear to be authorized to use Payouts API. You'll need to ask PayPal customer support to activate PAYOUTS API on your account (only PayPal can do this from their end).

#### INSUFFICIENT\_FUNDS

Your PayPal account balance does not have sufficient funds for sending money to affiliates. You need to add money to your PayPal account balance for the payments to work.&#x20;
