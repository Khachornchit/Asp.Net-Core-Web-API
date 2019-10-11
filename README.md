# Asp.Net Core Web API
Asp.Net Core Web API and Angular 7

## Technology adn Packages Stack
* Microsoft.AspNetCore.App, C#.NET
* Microsoft.EntityFrameworkCore Version 2.2.6
* Microsoft.EntityFrameworkCore.Tools Version 2.2.6
* Microsoft SQL Expression 2014

## Setup Guide
* git clone git@github.com:Khachornchit/Asp.Net-Core-Web-API.git
* cd Asp.Net-Core-Web-API
* Open the project with Visual Studio 2019
* PM> Update-Database

## CRUD
* POST		api/PaymentDetails
* GET		api/PaymentDetails
* GET		api/PaymentDetails/{id}
* PUT		api/PaymentDetails/{id}
* DELETE	api/PaymentDetails/{id}

## DATA
```
{
   "pmId": 1,
   "cardOwnerName": "John",
   "cardNumber": "1234",
   "expirationDate": "10/10",
   "cvv": "123"
}
```