---
description: "Setting a TXT\_record for emailing affiliates is no longer required."
---

# Create TXT Record

### To create a TXT record in your domain provider's dashboard, use the following values:

**Host/Name:**&#x20;

```
goaffpro._domainkey
```

**Value:**&#x20;

```
v=DKIM1;k=rsa;p=MIGfMA0GCSqGSIb3DQEBAQUAA4GNADCBiQKBgQC/v7KgtRN21u5oOFRBu+cblqfp2ZLrY8RAUPPWhABb8UgEUvI2c1whPN/NMwhqERaI++N7RednhJsGXaYOnl68pDt4GpsVQyFYTCOqILhdIyd0NdSNAlUoJv9qg1ub/Xy0pq3fBcg04yBBD7wVSmBUClf5ydRQq+fF9P7cK475DwIDAQAB
```

{% hint style="info" %}
You can also follow our guide on how to set up the TXT record for different domain registrars: [https://app.goaffpro.com/settings/notifications/txt-records](https://app.goaffpro.com/settings/notifications/txt-records)

The TXT record is only required, if you plan on using the Bulk Email option.

For better email deliverability, you should set up DKIM signing (DomainKeys Identified Mail),  which allows senders to associate a domain name with an email message.
{% endhint %}
