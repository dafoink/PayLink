PayLink Overview
=======

PayLink is part of PayFabric Service consists of several API calls. The basic business scenario of PayLink is as below:

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

* [How to Notify Customers]()
* [Customize Notify Email]()
* [Customize Payment Response]()


APIs
=======

* [Generate a new PayLink]()
* [Update PayLink]()
* [Delete PayLink]()
* [Resend Email]()
* [Resend Sms]()
* [Search by oData Query]()


