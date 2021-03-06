
.. _functional-guide/window/window-cash:

====
Cash
====

Process Payments and Receipts for Cash

Help
====
The Process Payments Window allows you to enter payments and reaipts for invoices.  If the payment is for a single invoice then it can be processed here.  If it is for multiple invoices or is a partial payment then it should be processed in the Payment Allocation Window.

Window Type
-----------
\ **Transaction**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Cash
----
\ **Description**\ 
 \ *Payment or Receipt*\ 
\ **Help**\ 
 \ *Enter payment or receipt for a Business Partner.  If it is for a single invoice it can be allocated directly to that invoice using this screen. You can also apply over/under payments:
You have an over-payment, if you received more money than due for a single invoice. Instead of writing the difference off (i.e. would be a gain), you can leave the amount unallocated and use it for later invoices or credit memos. Please note that the Amount is the payment amount, so you need to enter the over-payment as a negative amount.
You can also receive a partial payment (under-payment). If you decide not to write off the remaining invoice amount, enter the under-payment as a positive amount.
Note that printed payments are archived in Payment Selection (Prepared Payment).
* For Posting, the bank account organization is used, if it is not a charge.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Client
------
\ **Description**\ 
 \ *Client/Tenant for this installation.*\ 
\ **Help**\ 
 \ *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*\ 

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*\ 

Document No
-----------
\ **Description**\ 
 \ *Document sequence number of the document*\ 
\ **Help**\ 
 \ *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

Bank Account
------------
\ **Description**\ 
 \ *Account at the Bank*\ 
\ **Help**\ 
 \ *The Bank Account identifies an account at this Bank.*\ 

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 

Receipt
-------
\ **Description**\ 
 \ *This is a sales transaction (receipt)*\ 

Transaction Date
----------------
\ **Description**\ 
 \ *Transaction Date*\ 
\ **Help**\ 
 \ *The Transaction Date indicates the date of the transaction.*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Invoice
-------
\ **Description**\ 
 \ *Invoice Identifier*\ 
\ **Help**\ 
 \ *The Invoice Document.*\ 

Order
-----
\ **Description**\ 
 \ *Order*\ 
\ **Help**\ 
 \ *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Charge
------
\ **Description**\ 
 \ *Additional document charges*\ 
\ **Help**\ 
 \ *The Charge indicates a type of Charge (Handling, Shipping, Restocking)*\ 

Prepayment
----------
\ **Description**\ 
 \ *The Payment/Receipt is a Prepayment*\ 
\ **Help**\ 
 \ *Payments not allocated to an invoice with a charge are posted to Unallocated Payments. When setting this flag, the payment is posted to the Customer or Vendor Prepayment account.*\ 

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

Trx Organization
----------------
\ **Description**\ 
 \ *Performing or initiating organization*\ 
\ **Help**\ 
 \ *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*\ 

User List 1
-----------
\ **Description**\ 
 \ *User defined list element #1*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User List 2
-----------
\ **Description**\ 
 \ *User defined list element #2*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User List 3
-----------
\ **Description**\ 
 \ *User defined list element #3*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

User List 4
-----------
\ **Description**\ 
 \ *User defined list element #4*\ 
\ **Help**\ 
 \ *The user defined element displays the optional elements that have been defined for this account combination.*\ 

Payment amount
--------------
\ **Description**\ 
 \ *Amount being paid*\ 
\ **Help**\ 
 \ *Indicates the amount this payment is for.  The payment amount can be for single or multiple invoices or a partial payment for an invoice.*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Currency Type
-------------
\ **Description**\ 
 \ *Currency Conversion Rate Type*\ 
\ **Help**\ 
 \ *The Currency Conversion Rate Type lets you define different type of rates, e.g. Spot, Corporate and/or Sell/Buy rates.*\ 

Discount Amount
---------------
\ **Description**\ 
 \ *Calculated amount of discount*\ 
\ **Help**\ 
 \ *The Discount Amount indicates the discount amount for a document or line.*\ 

Write-off Amount
----------------
\ **Description**\ 
 \ *Amount to write-off*\ 
\ **Help**\ 
 \ *The Write Off Amount indicates the amount to be written off as uncollectible.*\ 

Over/Under Payment
------------------
\ **Description**\ 
 \ *Over-Payment (unallocated) or Under-Payment (partial payment)*\ 
\ **Help**\ 
 \ *Overpayments (negative) are unallocated amounts and allow you to receive money for more than the particular invoice. 
Underpayments (positive) is a partial payment for the invoice. You do not write off the unpaid amount.*\ 

Over/Under Payment
------------------
\ **Description**\ 
 \ *Over-Payment (unallocated) or Under-Payment (partial payment) Amount*\ 
\ **Help**\ 
 \ *Overpayments (negative) are unallocated amounts and allow you to receive money for more than the particular invoice. 
Underpayments (positive) is a partial payment for the invoice. You do not write off the unpaid amount.*\ 

Tender type
-----------
\ **Description**\ 
 \ *Method of Payment*\ 
\ **Help**\ 
 \ *The Tender Type indicates the method of payment (ACH or Direct Deposit, Credit Card, Check, Direct Debit)*\ 

Online Access
-------------
\ **Description**\ 
 \ *Can be accessed online*\ 
\ **Help**\ 
 \ *The Online Access check box indicates if the application can be accessed via the web.*\ 

Routing No
----------
\ **Description**\ 
 \ *Bank Routing Number*\ 
\ **Help**\ 
 \ *The Bank Routing Number (ABA Number) identifies a legal Bank.  It is used in routing checks and electronic transactions.*\ 

Account No
----------
\ **Description**\ 
 \ *Account Number*\ 
\ **Help**\ 
 \ *The Account Number indicates the Number assigned to this bank account.*\ 

Check No
--------
\ **Description**\ 
 \ *Check Number*\ 
\ **Help**\ 
 \ *The Check Number indicates the number on the check.*\ 

Micr
----
\ **Description**\ 
 \ *Combination of routing no, account and check no*\ 
\ **Help**\ 
 \ *The Micr number is the combination of the bank routing number, account number and check number*\ 

Credit Card
-----------
\ **Description**\ 
 \ *Credit Card (Visa, MC, AmEx)*\ 
\ **Help**\ 
 \ *The Credit Card drop down list box is used for selecting the type of Credit Card presented for payment.*\ 

Transaction Type
----------------
\ **Description**\ 
 \ *Type of credit card transaction*\ 
\ **Help**\ 
 \ *The Transaction Type indicates the type of transaction to be submitted to the Credit Card Company.*\ 

Number
------
\ **Description**\ 
 \ *Credit Card Number*\ 
\ **Help**\ 
 \ *The Credit Card number indicates the number on the credit card, without blanks or spaces.*\ 

Verification Code
-----------------
\ **Description**\ 
 \ *Credit Card Verification code on credit card*\ 
\ **Help**\ 
 \ *The Credit Card Verification indicates the verification code on the credit card (AMEX 4 digits on front; MC,Visa 3 digits back)*\ 

Exp. Month
----------
\ **Description**\ 
 \ *Expiry Month*\ 
\ **Help**\ 
 \ *The Expiry Month indicates the expiry month for this credit card.*\ 

Exp. Year
---------
\ **Description**\ 
 \ *Expiry Year*\ 
\ **Help**\ 
 \ *The Expiry Year indicates the expiry year for this credit card.*\ 

Account Name
------------
\ **Description**\ 
 \ *Name on Credit Card or Account holder*\ 
\ **Help**\ 
 \ *The Name of the Credit Card or Account holder.*\ 

Account Street
--------------
\ **Description**\ 
 \ *Street address of the Credit Card or Account holder*\ 
\ **Help**\ 
 \ *The Street Address of the Credit Card or Account holder.*\ 

Account City
------------
\ **Description**\ 
 \ *City or the Credit Card or Account Holder*\ 
\ **Help**\ 
 \ *The Account City indicates the City of the Credit Card or Account holder*\ 

Account Zip/Postal
------------------
\ **Description**\ 
 \ *Zip Code of the Credit Card or Account Holder*\ 
\ **Help**\ 
 \ *The Zip Code of the Credit Card or Account Holder.*\ 

Account State
-------------
\ **Description**\ 
 \ *State of the Credit Card or Account holder*\ 
\ **Help**\ 
 \ *The State of the Credit Card or Account holder*\ 

Account Country
---------------
\ **Description**\ 
 \ *Country*\ 
\ **Help**\ 
 \ *Account Country Name*\ 

Driver License
--------------
\ **Description**\ 
 \ *Payment Identification - Driver License*\ 
\ **Help**\ 
 \ *The Driver's License being used as identification.*\ 

Social Security No
------------------
\ **Description**\ 
 \ *Payment Identification - Social Security No*\ 
\ **Help**\ 
 \ *The Social Security number being used as identification.*\ 

Account EMail
-------------
\ **Description**\ 
 \ *Email Address*\ 
\ **Help**\ 
 \ *The EMail Address indicates the EMail address off the Credit Card or Account holder.*\ 

Tax Amount
----------
\ **Description**\ 
 \ *Tax Amount for Credit Card transaction*\ 
\ **Help**\ 
 \ *The Tax Amount displays the total tax amount. The tax amount is only used for credit card processing.*\ 

PO Number
---------
\ **Description**\ 
 \ *Purchase Order Number*\ 
\ **Help**\ 
 \ *The PO Number indicates the number assigned to a purchase order*\ 

Voice authorization code
------------------------
\ **Description**\ 
 \ *Voice Authorization Code from credit card company*\ 
\ **Help**\ 
 \ *The Voice Authorization Code indicates the code received from the Credit Card Company.*\ 

Original Transaction ID
-----------------------
\ **Description**\ 
 \ *Original Transaction ID*\ 
\ **Help**\ 
 \ *The Original Transaction ID is used for reversing transactions and indicates the transaction that has been reversed.*\ 

Online Process
--------------

Approved
--------
\ **Description**\ 
 \ *Indicates if this document requires approval*\ 
\ **Help**\ 
 \ *The Approved checkbox indicates if this document requires approval before it can be processed.*\ 

Result
------
\ **Description**\ 
 \ *Result of transmission*\ 
\ **Help**\ 
 \ *The Response Result indicates the result of the transmission to the Credit Card Company.*\ 

Response Message
----------------
\ **Description**\ 
 \ *Response message*\ 
\ **Help**\ 
 \ *The Response Message indicates the message returned from the Credit Card Company as the result of a transmission*\ 

Reference
---------
\ **Description**\ 
 \ *Payment reference*\ 
\ **Help**\ 
 \ *The Payment Reference indicates the reference returned from the Credit Card Company for a payment*\ 

Authorization Code
------------------
\ **Description**\ 
 \ *Authorization Code returned*\ 
\ **Help**\ 
 \ *The Authorization Code indicates the code returned from the electronic transmission.*\ 

Zip verified
------------
\ **Description**\ 
 \ *The Zip Code has been verified*\ 
\ **Help**\ 
 \ *The Zip Verified indicates if the zip code has been verified by the Credit Card Company.*\ 

Address verified
----------------
\ **Description**\ 
 \ *This address has been verified*\ 
\ **Help**\ 
 \ *The Address Verified indicates if the address has been verified by the Credit Card Company.*\ 

Document Status
---------------
\ **Description**\ 
 \ *The current status of the document*\ 
\ **Help**\ 
 \ *The Document Status indicates the status of a document at this time.  If you want to change the document status, use the Document Action field*\ 

Process Payment
---------------

Self-Service
------------
\ **Description**\ 
 \ *This is a Self-Service entry or this entry can be changed via Self-Service*\ 
\ **Help**\ 
 \ *Self-Service allows users to enter data or update their data.  The flag indicates, that this record was entered or created via Self-Service or that the user can change it via the Self-Service functionality.*\ 

Posted
------
\ **Description**\ 
 \ *Posting status*\ 
\ **Help**\ 
 \ *The Posted field indicates the status of the Generation of General Ledger Accounting Lines*\ 

Allocated
---------
\ **Description**\ 
 \ *Indicates if the payment has been allocated*\ 
\ **Help**\ 
 \ *The Allocated checkbox indicates if a payment has been allocated or associated with an invoice or invoices.*\ 

Cash Book
---------
\ **Description**\ 
 \ *Cash Book for recording petty cash transactions*\ 
\ **Help**\ 
 \ *The Cash Book identifies a unique cash book.  The cash book is used to record cash transactions.*\ 
