# Invoice finder

Building AI course project

## Summary

On July 1st, 2024 Poland introduces obligatory electronic invoice system called KSeF. Each company will have one account in KSeF. All invoices for company will be on this account. 
Currently when employee pays with company card (ex. lunch with a customer) he/she gets paper invoice and accounting can match invoice with payment. From July 1st, 2024 employee
will not receive paper invoice.

## Background

The problem is described in Summary. After introduction of KSeF companies in Poland will have accounts in KSeF, on which will be send all invoices for particular company.
In most cases it should be ease to match invoice with payment, although in case of company card payments there is no easy way to match them.

* problem 1 - matching company bank card payments with invoices in KSeF
* problem 2 - matching cash payments with invoices in KSeF

I assume that it will be very company problem in Poland after July 1st, 2024. Most of small and medium companies will have to go through each invoice and try to match it with bank card billings. As a board member of medium size company I will have to deal with this problem somehow.

## How is it used?

The solution would be used by accounting department of particular company in order to match invoices in KSeF account with cash payments and payments made by company bank cards.
An accountant responsible for verification of card statement would use proposed solution for preliminary matching of invoices with payments. 

## Data sources and AI methods

Data sources are as follows:
* invoices in xml format stored on KSeF account
* bank account / card statement in mt940 format
  
## Challenges

KSeF system is still in development phase. Although we have detailed description of invoices in xml format we do not know how it will be used by companies issuing invoices 
(a lot of fields is optional). For sure system would have to be trained on data sets in particular company (what banks it is using, how its suppliers issue invoices).
