
.. _functional-guide/window/window-import-order:

============
Import Order
============

Import Orders

Help
====
Please set Y/N selections in the import loader format explicitly (e.g. as constants) and no not leave them NULL. A NULL value stands for "don't know".
In general, selection boxes are not selected if the value is not "Y" (i.e. could be null or any other value). All tests are made on "Y" or "not Y" - i.e. NULL values are not "not Y", but NULL (don't know) - see SQL Language introductions.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Order
-----
\ **Description**\ 
 \ *Import Orders*\ 
\ **Help**\ 
 \ *You should supply the Document Type Name (or ID). The Document Type is on purpose not fully derived as it has too many consequences if it's wrong.  The best way is to set the Document Type Name as a Constant in your Import File Format or as an imported field in the file.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Import Order
------------
\ **Description**\ 
 \ *Import Orders*\ 

Imported
--------
\ **Description**\ 
 \ *Has this import been processed*\ 
\ **Help**\ 
 \ *The Imported check box indicates if this import has been processed.*\ 

Order
-----
\ **Description**\ 
 \ *Order*\ 
\ **Help**\ 
 \ *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*\ 

Sales Order Line
----------------
\ **Description**\ 
 \ *Sales Order Line*\ 
\ **Help**\ 
 \ *The Sales Order Line is a unique identifier for a line in an order.*\ 

Import Error Message
--------------------
\ **Description**\ 
 \ *Messages generated from import process*\ 
\ **Help**\ 
 \ *The Import Error Message displays any error messages generated during the import process.*\ 

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

Document Type Name
------------------
\ **Description**\ 
 \ *Name of the Document Type*\ 

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 

Document No
-----------
\ **Description**\ 
 \ *Document sequence number of the document*\ 
\ **Help**\ 
 \ *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

Sales Transaction
-----------------
\ **Description**\ 
 \ *This is a Sales Transaction*\ 
\ **Help**\ 
 \ *The Sales Transaction checkbox indicates if this item is a Sales Transaction.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Sales Representative
--------------------
\ **Description**\ 
 \ *Sales Representative or Company Agent*\ 
\ **Help**\ 
 \ *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*\ 

Delivery Rule
-------------
\ **Description**\ 
 \ *Defines the timing of Delivery*\ 
\ **Help**\ 
 \ *The Delivery Rule indicates when an order should be delivered. For example should the order be delivered when the entire order is complete, when a line is complete or as the products become available.*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Price List
----------
\ **Description**\ 
 \ *Unique identifier of a Price List*\ 
\ **Help**\ 
 \ *Price Lists are used to determine the pricing, margin and cost of items purchased or sold.*\ 

Payment Term Key
----------------
\ **Description**\ 
 \ *Key of the Payment Term*\ 

Payment Term
------------
\ **Description**\ 
 \ *The terms of Payment (timing, discount)*\ 
\ **Help**\ 
 \ *Payment Terms identify the method and timing of payment.*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Shipper
-------
\ **Description**\ 
 \ *Method or manner of product delivery*\ 
\ **Help**\ 
 \ *The Shipper indicates the method of delivering product*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Business Partner Key
--------------------
\ **Description**\ 
 \ *Key of the Business Partner*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Invoice To
----------
\ **Description**\ 
 \ *Bill to Address*\ 
\ **Help**\ 
 \ *The Bill/Invoice To indicates the address to use when remitting bills*\ 

Partner Location
----------------
\ **Description**\ 
 \ *Identifies the (ship to) address for this Business Partner*\ 
\ **Help**\ 
 \ *The Partner address indicates the location of a Business Partner*\ 

Address
-------
\ **Description**\ 
 \ *Location or Address*\ 
\ **Help**\ 
 \ *The Location / Address field defines the location of an entity.*\ 

Address 1
---------
\ **Description**\ 
 \ *Address line 1 for this location*\ 
\ **Help**\ 
 \ *The Address 1 identifies the address for an entity's location*\ 

Address 2
---------
\ **Description**\ 
 \ *Address line 2 for this location*\ 
\ **Help**\ 
 \ *The Address 2 provides additional address information for an entity.  It can be used for building location, apartment number or similar information.*\ 

City
----
\ **Description**\ 
 \ *Identifies a City*\ 
\ **Help**\ 
 \ *The City identifies a unique City for this Country or Region.*\ 

ZIP
---
\ **Description**\ 
 \ *Postal code*\ 
\ **Help**\ 
 \ *The Postal Code or ZIP identifies the postal code for this entity's address.*\ 

Region
------
\ **Description**\ 
 \ *Name of the Region*\ 
\ **Help**\ 
 \ *The Region Name defines the name that will print when this region is used in a document.*\ 

Region
------
\ **Description**\ 
 \ *Identifies a geographical Region*\ 
\ **Help**\ 
 \ *The Region identifies a unique Region for this Country.*\ 

ISO Country Code
----------------
\ **Description**\ 
 \ *Upper-case two-letter alphanumeric ISO Country code according to ISO 3166-1 - http://www.chemie.fu-berlin.de/diverse/doc/ISO_3166.html*\ 
\ **Help**\ 
 \ *For details - http://www.din.de/gremien/nas/nabd/iso3166ma/codlstp1.html or - http://www.unece.org/trade/rec/rec03en.htm*\ 

Country
-------
\ **Description**\ 
 \ *Country*\ 
\ **Help**\ 
 \ *The Country defines a Country.  Each Country must be defined before it can be used in any document.*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Contact Name
------------
\ **Description**\ 
 \ *Business Partner Contact Name*\ 

Phone
-----
\ **Description**\ 
 \ *Identifies a telephone number*\ 
\ **Help**\ 
 \ *The Phone field identifies a telephone number*\ 

EMail Address
-------------
\ **Description**\ 
 \ *Electronic Mail Address*\ 
\ **Help**\ 
 \ *The Email Address is the Electronic Mail ID for this User and should be fully qualified (e.g. joe.smith@company.com). The Email Address is used to access the self service application functionality from the web.*\ 

Date Ordered
------------
\ **Description**\ 
 \ *Date of Order*\ 
\ **Help**\ 
 \ *Indicates the Date an item was ordered.*\ 

Account Date
------------
\ **Description**\ 
 \ *Accounting Date*\ 
\ **Help**\ 
 \ *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Product Key
-----------
\ **Description**\ 
 \ *Key of the Product*\ 

Charge
------
\ **Description**\ 
 \ *Additional document charges*\ 
\ **Help**\ 
 \ *The Charge indicates a type of Charge (Handling, Shipping, Restocking)*\ 

Charge Name
-----------
\ **Description**\ 
 \ *Name of the Charge*\ 

SKU
---
\ **Description**\ 
 \ *Stock Keeping Unit*\ 
\ **Help**\ 
 \ *The SKU indicates a user defined stock keeping unit.  It may be used for an additional bar code symbols or your own schema.*\ 

UPC/EAN
-------
\ **Description**\ 
 \ *Bar Code (Universal Product Code or its superset European Article Number)*\ 
\ **Help**\ 
 \ *Use this field to enter the bar code for the product in any of the bar code symbologies (Codabar, Code 25, Code 39, Code 93, Code 128, UPC (A), UPC (E), EAN-13, EAN-8, ITF, ITF-14, ISBN, ISSN, JAN-13, JAN-8, POSTNET and FIM, MSI/Plessey, and Pharmacode)*\ 

UOM
---
\ **Description**\ 
 \ *Unit of Measure*\ 
\ **Help**\ 
 \ *The UOM defines a unique non monetary Unit of Measure*\ 

Ordered Quantity
----------------
\ **Description**\ 
 \ *Ordered Quantity*\ 
\ **Help**\ 
 \ *The Ordered Quantity indicates the quantity of a product that was ordered.*\ 

Unit Price
----------
\ **Description**\ 
 \ *Actual Price*\ 
\ **Help**\ 
 \ *The Actual or Unit Price indicates the Price for a product in source currency.*\ 

Line Description
----------------
\ **Description**\ 
 \ *Description of the Line*\ 

Tax Indicator
-------------
\ **Description**\ 
 \ *Short form for Tax to be printed on documents*\ 
\ **Help**\ 
 \ *The Tax Indicator identifies the short name that will print on documents referencing this tax.*\ 

Tax
---
\ **Description**\ 
 \ *Tax identifier*\ 
\ **Help**\ 
 \ *The Tax indicates the type of tax used in document line.*\ 

Tax Amount
----------
\ **Description**\ 
 \ *Tax Amount for a document*\ 
\ **Help**\ 
 \ *The Tax Amount displays the total tax amount for a document.*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

Activity
--------
\ **Description**\ 
 \ *Business Activity*\ 
\ **Help**\ 
 \ *Activities indicate tasks that are performed and used to utilize Activity based Costing*\ 

Trx Organization
----------------
\ **Description**\ 
 \ *Performing or initiating organization*\ 
\ **Help**\ 
 \ *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*\ 

Order Source Key
----------------

Order Source
------------

Import Orders
-------------
\ **Description**\ 
 \ *Import Orders*\ 
\ **Help**\ 
 \ *The Parameters are default values for null import record values, they do not overwrite any data.
Note that only Prepare and Complete are valid document actions.*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 
