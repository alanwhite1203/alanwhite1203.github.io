## Deal Entry Requirements
   
Deal entry covers both the situation where deal details are committed into production and the case where a deal is entered for the purpose of analysis only, e.g. a What-If Investigation. 

Deals that are committed into production typically enter the credit system after deal details have originally been entered into a source trading system by the executing trader. Manual deal entry is also possible in order 
to fix any potential errors. 

A pre-deal check (PDC) can be used to test for credit availability and for potential deal exceptions before committing them in the source system.

Deals are validated as they are written to the SDR, which is prior to the deal being valued by a pricer. Deal details are validated in the Deal Validation Process at the point

Any deal that does not have enough detail to apply Non-Standard rule, at a minimum, will be rejected. Therefore, the following is required:
a.	Valid counterparty.
b.	Valid transit (or BMO Legal Entity).
c.	Notional amount.
d.	Currency.
e.	Or, the above is determinable from given detail.

For any rejected deal, the following information will be recorded:
a.	The test which caused the deal to be rejected.
b.	The source of the deal entry message.
c.	The deal entry message.
d.	The Timestamp.

Rejected Deals will be listed in a view in the credit system.

During deal entry, a deal entering the system that is not rejected will have additional validation tests applied to the deal details. Note that in the current state, a Validation Exception would be called a Non-standard Violation.


References:


[Zenodo option](https://zenodo.org/record/3948304#)

[OSF option](https://osf.io/86t9p/download)

[gitbook option](https://deripricing.gitbook.io/stock-option-product-and-valuation/)

[Github convertible hw](https://github.com/timxiao1203/ConvertibleHullWhite)

