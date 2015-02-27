# EasyBill REST API

### Repository contains APIGEE Proxy connector to easybill.de 
```
Put your Easybill API Key in Custom Attributes "userkey" in your developer App
```

###Methods

####getCustomer

`GET`  /customer/{id}

Parameter    |  Value
------------ | ------------- 
id           | long 

####getCustomerByCustomerNumber

`GET`  /customerbycustomernumber

Parameter      | Value
-------------- | ------------- 
customerNumber | string 

####createCustomer

`POST`  /customer

Parameter      | type      | Usage    | Value
-------------- | --------- | ------   |-----
acquireOptions	| string	| Optional | 1, 2, 3, 4
bankAccount_1	|string	|Optional|	
bankAccountOwner_1	|string	|Optional	|
bankBIC_1	|string	|Optional|	 
bankCode_1	|string	|Optional| 
bankIBAN_1	|string	|Optional|	
bankName_1	|string	|Optional|	
birthDate	|date	|Optional	|
cashAllowance	|float	|Optional	|
cashDiscount	|float	|Optional	|
cashDiscountType	|string	|Optional	|PERCENT, AMOUNT
city	|string	|Required	
companyName	|string	|Optional	|
country	|string	|Required	||
customerNumber	|string	|Optional	|
delivery_city	|string	|Optional	|
delivery_companyName	|string	|Optional	|
delivery_country	|string	|Optional	|
delivery_firstName	|string	|Optional	|
delivery_lastName	|string	|Optional	|
delivery_personal	|integer	|Optional	|0, 1|
delivery_salutation	|integer	|Optional	|0, 1, 2, 3, 4, 5, 6|
delivery_street	string	|Optional	
delivery_suffix_1	|string	|Optional	|
delivery_suffix_2	|string	|Optional	|
delivery_zipCode	|string	|Optional	|
email	|string	|Optional	|
fax	|string	|Optional	|
firstName	|string	|Required	|
info_1	|string	|Optional	|
info_2	|string	|Optional	|
internet	|string|	Optional|	
lastName	|string	|Required	|
mobile	|string|	Optional|	
note	|string	|Optional	|
paymentOptions	|string	|Optional	|1, 2, 3, 5
personal	|integer	|Optional|	0, 1
phone_1	|string	|Optional	|
phone_2	|string	|Optional	|
postbox	|string	|Optional	|
postboxCity	|string	|Optional	|
postboxCountry	|string|	Optional|	
postboxZipCode	|string	|Optional|	
salePriceLevel	|string	|Optional	|SALEPRICE2, SALEPRICE3, SALEPRICE4, SALEPRICE5
salutation	|integer	|Required	|0, 1, 2, 3, 4, 5, 6
sepaAgreement	|string	|Optional	|BASIC, COMPANY, COR1
sepaDate	|date	|Optional	|
sepaInfo	|string	|Optional	|
sinceDate	|date	|Optional	|
street	|string	|Required	|
suffix_1	|string|	Optional	|
suffix_2	|string|	Optional	|
taxNumber	|string	|Optional	|
taxOptions|	string	|Optional	|nStb, nStbUstID, nStbNoneUstID, revc, IG, AL, sStfr
title	|string|	Optional|	
ustid	|string	|Optional	|
zipCode	|string|	Required|