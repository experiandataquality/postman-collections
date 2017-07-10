# Experian Data Quality - Postman Collections

A series of Postman collections for Experian Data Quality's Contact Data Management APIs.

Full API documentation can be found at [edq.com/documentation/apis](http://edq.com/documentation/apis).

Postman is a GUI REST client. By importing the collections you can explore our APIs and get a better understanding of the requests and responses.

## Getting Started

You will need an authentication token to make any requests. For existing customers, you can get your token from our [Self Service Portal](https://portal.experianmarketingservices.com/). If you're not an existing customer, visit [edq.com](http://edq.com) for more information about our products and how to contact us.

To get started with the Postman collections you will need to download the Postman tool from [getpostman.com/postman](https://www.getpostman.com/postman).

With Postman installed, you can clone this repository or download the individual files. You can then import the files into Postman and start making your requests.

The collections are configured to authenticate using a global **Auth-Token** variable that is sent with the request header. You will need to set this variable by clicking the eye icon in the top right corner of the Postman client. You can then add a new entry with Auth-Token as the key and your token as the value.

## REST APIs

Our real-time REST APIs give you flexibility and customization when verifying and enriching your contact data before it hits your database.

### Global Intuitive

Global Intuitive is a fast and efficient REST API for capturing validated global addresses.

### Address Validate REST

Address Validate API provides a REST interface for accessing address searching and verification functionality for USA, UK and Canada.

### Email Validate

Email Validate quickly and accurately identifies whether or not an email address is valid and deliverable. It also offers suggestions for a correct address enabling users to select a more accurate and verified e-mail.

### Phone Validate

Phone Validate allows you to validate full 10-digit numbers and identifies phone type in real time. 

> USA and Canada only.

### Global Phone Validate

Global Phone Validate is a web service that allows you to validate phone numbers and obtain additional information related to those numbers.

### Phone Validate V2

Phone Validate v2 allows you to validate phone numbers and obtain additional information related to those numbers.

> Currently supports mobile numbers for United States, Canada, United Kingdom, Ireland, Australia, Singapore, and France. 
For the United States and Canada, the coverage extends to landline numbers as well.

### Reverse Phone Append

Reverse Phone Append allows you to validate phone data and returns different types of phone information. This API can also link phone numbers with the person's name and postal address information, in real time. 

> USA and Canada only.

## SOAP APIs

### Address Validate SOAP

Address Validate SOAP provides an interface for global address searching and validation. We currently support over 160 countries.

> Despite being a SOAP API, this Postman collection allows you to make requests via the REST client. You won't be able to use any of the code generation functionality with this collection.






