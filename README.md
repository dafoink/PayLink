PayLink Overview
=======

PayLink is part of PayFabric Service consists of several API calls. The below steps are a classic workflow that work with PayLink Service:

1. Merchant is ready to collect credit card payment from his/her customer.
2. Merchant populate a new "PayLink" by calling api "POST /api/document".
3. PayLink service populate database record and send an email/sms to customer.
4. Customer loads the payment page by clicking the link url in email/sms on pc or mobile device.
5. Once paid, customer is redirected back to PayLink system to finish those post operation, such as integrating cash receipt record back to in-house ERP system.

Who Benifit From PayLink
=======

1. Web Developers who create payment applications for ERP/CRM.
2. Mobile Developers who create payment apps.

Configurations
=======

Before you start with PayLink, you are merchant and must register a PayFabric account. You can visit [PayFabric]() to learn more how to work with PayFabric. Once you get ready, PayLink service requires some more configurations as below:

* [How to Notify Customers](https://github.com/PayFabric/PayLink/wiki#turn-on-emailsms)
* [Customize Notify Email](https://github.com/PayFabric/PayLink/wiki#notification-email-template)
* [Customize Payment Response]()


APIs
=======

* [Generate a new PayLink](https://github.com/PayFabric/PayLink/wiki#generate-a-new-paylink)
* [Update PayLink](https://github.com/PayFabric/PayLink/wiki#update-paylink)
* [Get SMS Notification Templates](https://github.com/PayFabric/PayLink/wiki#get-sms-notification-templates)
* [Get PayLink](https://github.com/PayFabric/PayLink/wiki#get-paylink)
* [Cancel PayLink](https://github.com/PayFabric/PayLink/wiki#cancel-paylink)
* [Get All Documents](https://github.com/PayFabric/PayLink/wiki#get-all-documents)
* [Get Specified Document](https://github.com/PayFabric/PayLink/wiki#get-specified-document)
* [Delete PayLink](https://github.com/PayFabric/PayLink/wiki#delete-paylink)
* [Resend Email](https://github.com/PayFabric/PayLink/wiki#resend-email)
* [Resend Sms](https://github.com/PayFabric/PayLink/wiki#resend-sms)
* [Search by oData Query](https://github.com/PayFabric/PayLink/wiki#search-by-odata-query)


