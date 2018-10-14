
.. _functional-guide/smart-browse/smart-browse-pos-bank-statement-close:

========================
POS Bank Statement Close
========================

This Smart Browser allows to close the statement for POS Terminal

.. seealso::
    :ref:`functional-guidewindowwindow-payment`


.. seealso::
    :ref:`functional-guide/process/process-c_pos-bank-statement-close`


.. note::
    Show totals for the column  of amount type.

Fields
======


================  ========================================  =========  ==============  ========  =========  =========
Name              Description                               Displayed  Query Criteria  Order By  Read Only  Mandatory
================  ========================================  =========  ==============  ========  =========  =========
Bank Account      Account at the Bank                       No         Yes             No        No         Yes      
Receipt           This is a sales transaction (receipt)     No         Yes             No        Yes        No       
POS Terminal      Point of Sales Terminal                   No         Yes             No        Yes        Yes      
Payment           Payment identifier                        Yes        No              No        Yes        No       
Order             Order                                     Yes        No              No        Yes        No       
Transaction Date  Transaction Date                          Yes        Yes             No        Yes        No       
Document No       Document sequence number of the document  Yes        No              No        Yes        No       
Pay Amt           Amount being paid                         Yes        No              No        Yes        No       
Tender type       Method of Payment                         Yes        No              Yes       Yes        No       
Tender Type       Tender Type                               Yes        Yes             No        Yes        No       
================  ========================================  =========  ==============  ========  =========  =========
