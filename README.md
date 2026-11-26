# PaySum for Invision Community

A hosted checkout gateway for one-time Commerce invoices in Invision Community 4.7.

```sh
tar -cf paysum-invision.tar -C applications/paysum Application.php Checkout.php data extensions hooks modules
```

Install the archive in the AdminCP under **System → Applications**. Add PaySum as a Commerce payment method and enter your API key and webhook signing secret. Test an invoice before enabling the gateway for members.
