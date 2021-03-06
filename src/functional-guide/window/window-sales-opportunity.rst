
.. _functional-guide/window/window-sales-opportunity:

=================
Sales Opportunity
=================

A potential sale

.. note::
    Beta functionality is not fully tested or completed.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Opportunity
-----------

.. note::
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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Campaign
--------
\ **Description**\ 
 \ *Marketing Campaign*\ 
\ **Help**\ 
 \ *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*\ 

Sales Representative
--------------------
\ **Description**\ 
 \ *Sales Representative or Company Agent*\ 
\ **Help**\ 
 \ *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*\ 

Sales Stage
-----------
\ **Description**\ 
 \ *Stages of the sales process*\ 
\ **Help**\ 
 \ *Define what stages your sales process will move through*\ 

Probability
-----------

Expected Close Date
-------------------
\ **Description**\ 
 \ *Expected Close Date*\ 
\ **Help**\ 
 \ *The Expected Close Date indicates the expected last or final date*\ 

Opportunity Amount
------------------
\ **Description**\ 
 \ *The estimated value of this opportunity.*\ 

Weighted Amount
---------------
\ **Description**\ 
 \ *The amount adjusted by the probability.*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Comments
--------
\ **Description**\ 
 \ *Comments or additional information*\ 
\ **Help**\ 
 \ *The Comments field allows for free form entry of additional information.*\ 

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

Close Date
----------
\ **Description**\ 
 \ *Close Date*\ 
\ **Help**\ 
 \ *The Close Date indicates the last or final date*\ 

Cost
----
\ **Description**\ 
 \ *Cost information*\ 

Quote/Order
-----------

.. note::
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

Order Reference
---------------
\ **Description**\ 
 \ *Transaction Reference Number (Sales Order, Purchase Order) of your Business Partner*\ 
\ **Help**\ 
 \ *The business partner order reference is the order reference for this specific transaction; Often Purchase Order numbers are given to print on Invoices for easier reference.  A standard number can be defined in the Business Partner (Customer) window.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Target Document Type
--------------------
\ **Description**\ 
 \ *Target document type for conversing documents*\ 
\ **Help**\ 
 \ *You can convert document types (e.g. from Offer to Order or Invoice).  The conversion is then reflected in the current type.  This processing is initiated by selecting the appropriate Document Action.*\ 

Self-Service
------------
\ **Description**\ 
 \ *This is a Self-Service entry or this entry can be changed via Self-Service*\ 
\ **Help**\ 
 \ *Self-Service allows users to enter data or update their data.  The flag indicates, that this record was entered or created via Self-Service or that the user can change it via the Self-Service functionality.*\ 

Date Ordered
------------
\ **Description**\ 
 \ *Date of Order*\ 
\ **Help**\ 
 \ *Indicates the Date an item was ordered.*\ 

Date Promised
-------------
\ **Description**\ 
 \ *Date Order was promised*\ 
\ **Help**\ 
 \ *The Date Promised indicates the date, if any, that an Order was promised for.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Invoice Partner
---------------
\ **Description**\ 
 \ *Business Partner to be invoiced*\ 
\ **Help**\ 
 \ *If empty the shipment business partner will be invoiced*\ 

Partner Location
----------------
\ **Description**\ 
 \ *Identifies the (ship to) address for this Business Partner*\ 
\ **Help**\ 
 \ *The Partner address indicates the location of a Business Partner*\ 

Invoice Location
----------------
\ **Description**\ 
 \ *Business Partner Location for invoicing*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Invoice Contact
---------------
\ **Description**\ 
 \ *Business Partner Contact for invoicing*\ 

Delivery Rule
-------------
\ **Description**\ 
 \ *Defines the timing of Delivery*\ 
\ **Help**\ 
 \ *The Delivery Rule indicates when an order should be delivered. For example should the order be delivered when the entire order is complete, when a line is complete or as the products become available.*\ 

Priority
--------
\ **Description**\ 
 \ *Priority of a document*\ 
\ **Help**\ 
 \ *The Priority indicates the importance (high, medium, low) of this document*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Drop Shipment
-------------
\ **Description**\ 
 \ *Drop Shipments are sent from the Vendor directly to the Customer*\ 
\ **Help**\ 
 \ *Drop Shipments do not cause any Inventory reservations or movements as the Shipment is from the Vendor's inventory. The Shipment of the Vendor to the Customer must be confirmed.*\ 

Drop Shipment Partner
---------------------
\ **Description**\ 
 \ *Business Partner to ship to*\ 
\ **Help**\ 
 \ *If empty the business partner will be shipped to.*\ 

Drop Shipment Location
----------------------
\ **Description**\ 
 \ *Business Partner Location for shipping to*\ 

Drop Shipment Contact
---------------------
\ **Description**\ 
 \ *Business Partner Contact for drop shipment*\ 

Delivery Via
------------
\ **Description**\ 
 \ *How the order will be delivered*\ 
\ **Help**\ 
 \ *The Delivery Via indicates how the products should be delivered. For example, will the order be picked up or shipped.*\ 

Shipper
-------
\ **Description**\ 
 \ *Method or manner of product delivery*\ 
\ **Help**\ 
 \ *The Shipper indicates the method of delivering product*\ 

Freight Cost Rule
-----------------
\ **Description**\ 
 \ *Method for charging Freight*\ 
\ **Help**\ 
 \ *The Freight Cost Rule indicates the method used when charging for freight.*\ 

Freight Category
----------------
\ **Description**\ 
 \ *Category of the Freight*\ 
\ **Help**\ 
 \ *Freight Categories are used to calculate the Freight for the Shipper selected*\ 

Freight Amount
--------------
\ **Description**\ 
 \ *Freight Amount*\ 
\ **Help**\ 
 \ *The Freight Amount indicates the amount charged for Freight in the document currency.*\ 

Invoice Rule
------------
\ **Description**\ 
 \ *Frequency and method of invoicing*\ 
\ **Help**\ 
 \ *The Invoice Rule defines how a Business Partner is invoiced and the frequency of invoicing.*\ 

Price List
----------
\ **Description**\ 
 \ *Unique identifier of a Price List*\ 
\ **Help**\ 
 \ *Price Lists are used to determine the pricing, margin and cost of items purchased or sold.*\ 

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

Sales Representative
--------------------
\ **Description**\ 
 \ *Sales Representative or Company Agent*\ 
\ **Help**\ 
 \ *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*\ 

Discount Printed
----------------
\ **Description**\ 
 \ *Print Discount on Invoice and Order*\ 
\ **Help**\ 
 \ *The Discount Printed Checkbox indicates if the discount will be printed on the document.*\ 

Charge
------
\ **Description**\ 
 \ *Additional document charges*\ 
\ **Help**\ 
 \ *The Charge indicates a type of Charge (Handling, Shipping, Restocking)*\ 

Charge amount
-------------
\ **Description**\ 
 \ *Charge Amount*\ 
\ **Help**\ 
 \ *The Charge Amount indicates the amount for an additional charge.*\ 

Payment Rule
------------
\ **Description**\ 
 \ *How you pay the invoice*\ 
\ **Help**\ 
 \ *The Payment Rule indicates the method of invoice payment.*\ 

Payment Term
------------
\ **Description**\ 
 \ *The terms of Payment (timing, discount)*\ 
\ **Help**\ 
 \ *Payment Terms identify the method and timing of payment.*\ 

Promotion Code
--------------
\ **Description**\ 
 \ *User entered promotion code at sales time*\ 
\ **Help**\ 
 \ *If present, user entered the promotion code at sales time to get this promotion*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

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

Total Lines
-----------
\ **Description**\ 
 \ *Total of all document lines*\ 
\ **Help**\ 
 \ *The Total amount displays the total of all lines in document currency*\ 

Grand Total
-----------
\ **Description**\ 
 \ *Total amount of document*\ 
\ **Help**\ 
 \ *The Grand Total displays the total amount including Tax and Freight in document currency*\ 

Document Status
---------------
\ **Description**\ 
 \ *The current status of the document*\ 
\ **Help**\ 
 \ *The Document Status indicates the status of a document at this time.  If you want to change the document status, use the Document Action field*\ 

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 

Copy Lines
----------
\ **Description**\ 
 \ *Copy Lines from other Order*\ 

Process Order
-------------

Posted
------
\ **Description**\ 
 \ *Posting status*\ 
\ **Help**\ 
 \ *The Posted field indicates the status of the Generation of General Ledger Accounting Lines*\ 

Order Line
----------

.. note::
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

Order
-----
\ **Description**\ 
 \ *Order*\ 
\ **Help**\ 
 \ *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Partner Location
----------------
\ **Description**\ 
 \ *Identifies the (ship to) address for this Business Partner*\ 
\ **Help**\ 
 \ *The Partner address indicates the location of a Business Partner*\ 

Date Promised
-------------
\ **Description**\ 
 \ *Date Order was promised*\ 
\ **Help**\ 
 \ *The Date Promised indicates the date, if any, that an Order was promised for.*\ 

Date Ordered
------------
\ **Description**\ 
 \ *Date of Order*\ 
\ **Help**\ 
 \ *Indicates the Date an item was ordered.*\ 

Line No
-------
\ **Description**\ 
 \ *Unique line for this document*\ 
\ **Help**\ 
 \ *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Charge
------
\ **Description**\ 
 \ *Additional document charges*\ 
\ **Help**\ 
 \ *The Charge indicates a type of Charge (Handling, Shipping, Restocking)*\ 

Attribute Set Instance
----------------------
\ **Description**\ 
 \ *Product Attribute Set Instance*\ 
\ **Help**\ 
 \ *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*\ 

Resource Assignment
-------------------
\ **Description**\ 
 \ *Resource Assignment*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Quantity
--------
\ **Description**\ 
 \ *The Quantity Entered is based on the selected UoM*\ 
\ **Help**\ 
 \ *The Quantity Entered is converted to base product UoM quantity*\ 

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

Delivered Quantity
------------------
\ **Description**\ 
 \ *Delivered Quantity*\ 
\ **Help**\ 
 \ *The Delivered Quantity indicates the quantity of a product that has been delivered.*\ 

Reserved Quantity
-----------------
\ **Description**\ 
 \ *Reserved Quantity*\ 
\ **Help**\ 
 \ *The Reserved Quantity indicates the quantity of a product that is currently reserved.*\ 

Quantity Invoiced
-----------------
\ **Description**\ 
 \ *Invoiced Quantity*\ 
\ **Help**\ 
 \ *The Invoiced Quantity indicates the quantity of a product that have been invoiced.*\ 

Shipper
-------
\ **Description**\ 
 \ *Method or manner of product delivery*\ 
\ **Help**\ 
 \ *The Shipper indicates the method of delivering product*\ 

Price
-----
\ **Description**\ 
 \ *Price Entered - the price based on the selected/base UoM*\ 
\ **Help**\ 
 \ *The price entered is converted to the actual price based on the UoM conversion*\ 

Unit Price
----------
\ **Description**\ 
 \ *Actual Price*\ 
\ **Help**\ 
 \ *The Actual or Unit Price indicates the Price for a product in source currency.*\ 

List Price
----------
\ **Description**\ 
 \ *List Price*\ 
\ **Help**\ 
 \ *The List Price is the official List Price in the document currency.*\ 

Freight Amount
--------------
\ **Description**\ 
 \ *Freight Amount*\ 
\ **Help**\ 
 \ *The Freight Amount indicates the amount charged for Freight in the document currency.*\ 

Tax
---
\ **Description**\ 
 \ *Tax identifier*\ 
\ **Help**\ 
 \ *The Tax indicates the type of tax used in document line.*\ 

Discount %
----------
\ **Description**\ 
 \ *Discount in percent*\ 
\ **Help**\ 
 \ *The Discount indicates the discount applied or taken as a percentage.*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

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

Line Amount
-----------
\ **Description**\ 
 \ *Line Extended Amount (Quantity * Actual Price) without Freight and Charges*\ 
\ **Help**\ 
 \ *Indicates the extended line amount based on the quantity and the actual price.  Any additional charges or freight are not included.  The Amount may or may not include tax.  If the price list is inclusive tax, the line amount is the same as the line total.*\ 

Lost Sales Qty
--------------
\ **Description**\ 
 \ *Quantity of potential sales*\ 
\ **Help**\ 
 \ *When an order is closed and there is a difference between the ordered quantity and the delivered (invoiced) quantity is the Lost Sales Quantity.  Note that the Lost Sales Quantity is 0 if you void an order, so close the order if you want to track lost opportunities.  [Void = data entry error - Close = the order is finished]*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Activity
--------

.. note::
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

Sales Opportunity
-----------------

Activity Type
-------------
\ **Description**\ 
 \ *Type of activity, e.g. task, email, phone call*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Sales Representative
--------------------
\ **Description**\ 
 \ *Sales Representative or Company Agent*\ 
\ **Help**\ 
 \ *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*\ 

Comments
--------
\ **Description**\ 
 \ *Comments or additional information*\ 
\ **Help**\ 
 \ *The Comments field allows for free form entry of additional information.*\ 

Start Date
----------
\ **Description**\ 
 \ *First effective day (inclusive)*\ 
\ **Help**\ 
 \ *The Start Date indicates the first or starting date*\ 

End Date
--------
\ **Description**\ 
 \ *Last effective date (inclusive)*\ 
\ **Help**\ 
 \ *The End Date indicates the last date in this range.*\ 

Complete
--------
\ **Description**\ 
 \ *It is complete*\ 
\ **Help**\ 
 \ *Indication that this is complete*\ 
