
.. _functional-guide/process/process-pp_product_planning:

=======================
Create Product Planning
=======================

This process will create the data plannig register for every product

Help
====
In order to facilitate to load the data planning of similar products, you can run the process Create product Planning and this process will create the data plannig register for every product which fits the parameters: Product category, Warehouse and Resource.

You must indicate the planning parameters defined in the last section for every Product category, Warehouse, and Resource set. Every product which fit these three parameters will have a data planning record with the same data planning values you enter in this form.

Parameters
==========

Product Category
----------------
\ **Description**\ 
 \ *Category of a Product*\ 
\ **Help**\ 
 \ *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Resource
--------
\ **Description**\ 
 \ *Resource*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Create Plan
-----------
\ **Description**\ 
 \ *Indicates whether planned orders will be generated by MRP*\ 
\ **Help**\ 
 \ *Indicates whether planned orders will be generated by MRP, if this flag is not just MRP generate a 'Create' action notice*\ 

Is MPS
------
\ **Description**\ 
 \ *Indicates if this product is part of the master production schedule*\ 
\ **Help**\ 
 \ *The independent demand products such as end products or spare parts, should be part of the MPS.


This flag is used to segregate the products to be used in reports and inquiries of the MPS and allows to calculate the MPS by the execution of a selective MRP process.*\ 

Network Distribution
--------------------
\ **Description**\ 
 \ *Identifies a distribution network, distribution networks are used to establish the source and target of the materials in the supply chain*\ 
\ **Help**\ 
 \ *DRP uses the distribution networks to generate the distribution plan.

A distribution network defines the supply path by a relationship between the source and target warehouse and a percentage of the supply quantity.*\ 

Workflow
--------
\ **Description**\ 
 \ *Workflow or combination of tasks*\ 
\ **Help**\ 
 \ *The Workflow field identifies a unique Workflow in the system.*\ 

Time Fence
----------
\ **Description**\ 
 \ *The Time Fence is the number of days since you execute the MRP process inside of which  the system must not change the planned orders.*\ 
\ **Help**\ 
 \ *The system will generate  action messages warning if some order needs to be modified or created into the time fence.

The Limit time is used for the master plan products, the number of days is the equal or bigger than the product’s delivery time.

It is recommended to establish a limit time, so you don’t have a nervous manufacturing system or a systems that reacts to any change or plan modification.*\ 

Transfer Time
-------------
\ **Description**\ 
 \ *Transfer Time*\ 
\ **Help**\ 
 \ *Indicates the number of days the product needs to be moved from one warehouse to another.*\ 

Safety Stock Qty
----------------
\ **Description**\ 
 \ *Safety stock is a term used to describe a level of stock that is maintained below the cycle stock to buffer against stock-outs*\ 
\ **Help**\ 
 \ *Safety stock is defined as extra units of inventory carried as protection against possible stockouts. It is held when an organization cannot accurately predict demand and/or lead time for the product.

Rereference:
http://en.wikipedia.org/wiki/Safety_stock*\ 

Minimum Order Qty
-----------------
\ **Description**\ 
 \ *Minimum order quantity in UOM*\ 
\ **Help**\ 
 \ *The Minimum Order Quantity indicates the smallest quantity of this product which can be ordered.*\ 

Maximum Order Qty
-----------------
\ **Description**\ 
 \ *Maximum order quantity in UOM*\ 
\ **Help**\ 
 \ *The Maximum Order Quantity indicates the biggest quantity of this product which can be ordered.*\ 

Order Pack Qty
--------------
\ **Description**\ 
 \ *Package order size in UOM (e.g. order set of 5 units)*\ 
\ **Help**\ 
 \ *The Order Pack Quantity indicates the number of units in each pack of this product.*\ 

Order Qty
---------
\ **Description**\ 
 \ *Order Qty*\ 
\ **Help**\ 
 \ *Define the fixed quantity to be ordered when the order policy used is FOQ*\ 

Working Time
------------
\ **Description**\ 
 \ *Workflow Simulation Execution Time*\ 
\ **Help**\ 
 \ *Amount of time the performer of the activity needs to perform the task in Duration Unit*\ 

Yield %
-------
\ **Description**\ 
 \ *The Yield is the percentage of a lot that is expected to be of acceptable wuality may fall below 100 percent*\ 
\ **Help**\ 
 \ *ADempiere Calculate the total yield for a product from the yield for each activity when the process Workflow Cost Roll-Up is executed.

The expected yield for an Activity can be expressed as:

Yield = Acceptable Units at Activity End x 100

The Total manufacturing yield for a product is determined by multiplying the yied percentage for each activity.

Manufacturing Yield = Yield % for Activity 10 x Yied % for Activity 20 , etc

Take care when setting yield to anything but 100% particularly when yied is used for multiples activities*\ 

Promised Delivery Time
----------------------
\ **Description**\ 
 \ *Promised days between order and delivery*\ 
\ **Help**\ 
 \ *The Promised Delivery Time indicates the number of days between the order date and the date that delivery was promised.*\ 

Order Policy
------------
\ **Description**\ 
 \ *Order Policy*\ 
\ **Help**\ 
 \ *If the DRP Required checkbox is ticked, this means it has been a change in some element which affect the material plan  for this product, i.e Network Distribution, Orders, Inventory, MPS, etc. and therefore  you need to executed again DRP to adjust the Planned Orders to the new conditions and to get the updated action messages.


Lot-For-Lot  (LFL): Creates planned orders to satisfy the demand, an order is created to satisfy each net requirement. so MRP process must generate one planned order for each demand not satisfied.

Period Order Quantity (POQ): Creates planned orders to satisfy the demand, the requirements are accumulated in a defined period and a planned order is created for the period quantity accumulation. The number of days are entered in the field Order Period.

Use  Fixed Order Quantity when you always need to ask for  the same Quantity of product, this Quantity is entered in the field Order Qty.
* 
If the order policy is not FOQ and you enter a quantity in the Order Qty field, this quantity is the Economic Order Quantity.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Order Period
------------
\ **Description**\ 
 \ *Order Period*\ 
\ **Help**\ 
 \ *Number of calendar days used to accumulate  the net requirements to integrate the quantity of a planned order under the policy of POQ.*\ 

Planner
-------
\ **Description**\ 
 \ *Company Agent for Planning*\ 
\ **Help**\ 
 \ *The Master Planner indicates the company agent in charge of the MPS management. Any Master Planner must be a valid internal user.*\ 
