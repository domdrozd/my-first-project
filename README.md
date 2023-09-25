# Invoice finder

Building AI course project

## Summary

Poland introduces obligatory the National e-Invoice System (called "KSeF"). 
KSeF enables the issuance and sharing of structured electonic invoices. 
In the initial period, structured invoices were function in business transactions as one of the accepted forms of documenting transactions, 
next to paper invoices. 
From July 1st, 2024 Poland using KSeF will be obligatory. Each company in Polnad will have one account in KSeF. 
All cost invoices received by a given company will be in this one KSeF account - which means that on a one account the company will
have several, several hundred or thousands of invoices per month - depending on the size of the specific company..

The proposed solution will be used to link cost invoices received in KSeF account with statements from company payment cards. 
The task of the system would be to search for the appropriate invoice in KSeF and assign it to a specific item from the bank statement.

## Background

The problem is described in Summary. 

After implementing KSeF, an employee making a transaction with a company credit card will not receive a paper invoice. 
When the transaction is completed, the invoice will be electronically sent to his company's account in KSeF. 
At the end of the month, this employee will have to settle all expenses made with his company card. 
So far, this was done by matching expenses on the company card statement with the received paper invoices. 
After the implementation of KSeF, there will no longer be paper invoices. 
All invoices received by the company will be on one account in KSeF.
In order to settle expenses using a business card, it will be necessary to search the KSeF account for the expenses indicated on the 
card statement of a given employee. A limited number of people will have access to a given company's KSeF account. These people will have 
to do the tedious work of assigning an appropriate invoice to each item in the bank statement. There is currently no easy way to link 
these invoices to bank statements. Invoices are sent to KSeF directly by the company where we make the purchase, while the bank statement 
is prepared by the bank based on data received from various agents settling card payments.

A similar situation will occur in the case of cash payments. In such a case, the employee making the cash payment will have to inform 
the people handling the KSeF account in the company, who in turn will have to search for the appropriate invoice in the KSeF account.

* problem 1 - matching company bank card payments with invoices in KSeF
* problem 2 - matching cash payments with invoices in KSeF

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
