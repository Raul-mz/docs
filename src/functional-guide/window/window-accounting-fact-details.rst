
.. _functional-guide/window/window-accounting-fact-details:

=======================
Accounting Fact Details
=======================

Query Accounting Facts

Help
====
Query the detail accounting transactions

Window Type
-----------
\ **Query Only**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Accounting
----------
\ **Description**\ 
 \ *View Accounting Fact Details*\ 

.. note::
    The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.
The Read Only indicates that this field may only be Read.  It may not be updated.

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

Accounting Schema
-----------------
\ **Description**\ 
 \ *Rules for accounting*\ 
\ **Help**\ 
 \ *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*\ 

Table
-----
\ **Description**\ 
 \ *Database Table information*\ 
\ **Help**\ 
 \ *The Database Table provides the information of the table definition*\ 

Record ID
---------
\ **Description**\ 
 \ *Direct internal record ID*\ 
\ **Help**\ 
 \ *The Record ID is the internal unique identifier of a record. Please note that zooming to the record may not be successful for Orders, Invoices and Shipment/Receipts as sometimes the Sales Order type is not known.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Period
------
\ **Description**\ 
 \ *Period of the Calendar*\ 
\ **Help**\ 
 \ *The Period indicates an exclusive range of dates for a calendar.*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Posting Type
------------
\ **Description**\ 
 \ *The type of posted amount for the transaction*\ 
\ **Help**\ 
 \ *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*\ 

Transaction Date
----------------
\ **Description**\ 
 \ *Transaction Date*\ 
\ **Help**\ 
 \ *The Transaction Date indicates the date of the transaction.*\ 

Account
-------
\ **Description**\ 
 \ *Account used*\ 
\ **Help**\ 
 \ *The (natural) account used*\ 

Sub Account
-----------
\ **Description**\ 
 \ *Sub account for Element Value*\ 
\ **Help**\ 
 \ *The Element Value (e.g. Account) may have optional sub accounts for further detail. The sub account is dependent on the value of the account, so a further specification. If the sub-accounts are more or less the same, consider using another accounting dimension.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Sales Region
------------
\ **Description**\ 
 \ *Sales coverage region*\ 
\ **Help**\ 
 \ *The Sales Region indicates a specific area of sales coverage.*\ 

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

Location From
-------------
\ **Description**\ 
 \ *Location that inventory was moved from*\ 
\ **Help**\ 
 \ *The Location From indicates the location that a product was moved from.*\ 

Location To
-----------
\ **Description**\ 
 \ *Location that inventory was moved to*\ 
\ **Help**\ 
 \ *The Location To indicates the location that a product was moved to.*\ 

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

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

User Element 1
--------------
\ **Description**\ 
 \ *User defined accounting Element*\ 
\ **Help**\ 
 \ *A user defined accounting element refers to a Adempiere table. This allows to use any table content as an accounting dimension (e.g. Project Task).  Note that User Elements are optional and are populated from the context of the document (i.e. not requested)*\ 

User Element 2
--------------
\ **Description**\ 
 \ *User defined accounting Element*\ 
\ **Help**\ 
 \ *A user defined accounting element refers to a Adempiere table. This allows to use any table content as an accounting dimension (e.g. Project Task).  Note that User Elements are optional and are populated from the context of the document (i.e. not requested)*\ 

Project Phase
-------------
\ **Description**\ 
 \ *Phase of a Project*\ 

Project Task
------------
\ **Description**\ 
 \ *Actual Project Task in a Phase*\ 
\ **Help**\ 
 \ *A Project Task in a Project Phase represents the actual work.*\ 

GL Category
-----------
\ **Description**\ 
 \ *General Ledger Category*\ 
\ **Help**\ 
 \ *The General Ledger Category is an optional, user defined method of grouping journal lines.*\ 

Budget
------
\ **Description**\ 
 \ *General Ledger Budget*\ 
\ **Help**\ 
 \ *The General Ledger Budget identifies a user defined budget.  These can be used in reporting as a comparison against your actual amounts.*\ 

Tax
---
\ **Description**\ 
 \ *Tax identifier*\ 
\ **Help**\ 
 \ *The Tax indicates the type of tax used in document line.*\ 

Locator
-------
\ **Description**\ 
 \ *Warehouse Locator*\ 
\ **Help**\ 
 \ *The Locator indicates where in a Warehouse a product is located.*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Source Debit
------------
\ **Description**\ 
 \ *Source Debit Amount*\ 
\ **Help**\ 
 \ *The Source Debit Amount indicates the credit amount for this line in the source currency.*\ 

Source Credit
-------------
\ **Description**\ 
 \ *Source Credit Amount*\ 
\ **Help**\ 
 \ *The Source Credit Amount indicates the credit amount for this line in the source currency.*\ 

Accounted Debit
---------------
\ **Description**\ 
 \ *Accounted Debit Amount*\ 
\ **Help**\ 
 \ *The Account Debit Amount indicates the transaction amount converted to this organization's accounting currency*\ 

Accounted Credit
----------------
\ **Description**\ 
 \ *Accounted Credit Amount*\ 
\ **Help**\ 
 \ *The Account Credit Amount indicates the transaction amount converted to this organization's accounting currency*\ 

UOM
---
\ **Description**\ 
 \ *Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM defines a unique non monetary Unit of Measure*\ 

Quantity
--------
\ **Description**\ 
 \ *Quantity*\ 
\ **Help**\ 
 \ *The Quantity indicates the number of a specific product or item for this document.*\ 
