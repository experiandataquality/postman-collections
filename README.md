# Experian Data Quality - Postman Collections

A series of Postman collections for Experian Data Quality's Contact Data Management APIs.

Full API documentation can be found at [edq.com/documentation/apis](http://edq.com/documentation/apis).

Postman is a GUI REST client. By importing the collections you can explore our APIs and get a better understanding of the requests and responses.

## Getting Started

You will need an authentication token to make any requests. For existing customers, you can get your token from our [Self Service Portal](https://manage.experianaperture.io). If you're not an existing customer, visit [edq.com](http://edq.com) for more information about our products and how to contact us.

To get started with the Postman collections you will need to download the Postman tool from [getpostman.com/postman](https://www.getpostman.com/postman).

With Postman installed, you can clone this repository or download the individual files. You can then import the files into Postman and start making your requests.

The collections are configured to authenticate using a global **Auth-Token** variable that is sent with the request header. You will need to set this variable by clicking the eye icon in the top right corner of the Postman client. You can then add a new entry with Auth-Token as the key and your token as the value.

## REST APIs

Our real-time REST APIs give you flexibility and customization when verifying and enriching your contact data before it hits your database.

### Experian Address Validation

Experian Address Validation is a real-time REST API that helps you to capture validated global addresses. 

[Download file](../../raw/master/Experian%20Address%20Validation.postman_collection.json)

### Experian Email Validation

Experian Email Validation is a real-time REST API that helps you quickly determine the validity and status of email addresses at the point of collection. 

[Download file](../../raw/master/experian-email-validation.postman_collection.json)

### Experian Phone Validation

Experian Phone Validation is a real-time REST API that helps you quickly determine the validity and status of phone numbers at the point of collection.

[Download file](../../raw/master/experian-phone-validation.postman_collection.json)

### Global Intuitive

Global Intuitive is a fast and efficient REST API for capturing validated global addresses.

[Download file](../../raw/master/global-intuitive.postman_collection.json)

## SOAP APIs

### Address Validate SOAP

Address Validate SOAP provides an interface for global address searching and validation. We currently support over 160 countries.

You will need to edit the body of each request and replace the placeholders.

> Despite being a SOAP API, this Postman collection allows you to make requests via the REST client. You won't be able to use any of the code generation functionality with this collection.

[Download file](../../raw/master/address-validate-soap.postman_collection.json)






