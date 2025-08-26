## Price Deal Exposure
   
Unexpected situations that occur during pricing will create a Pricing Exception workflow.

If a pricing exception occurs during Deal Entry, all Pricing Exceptions that occur will reference the single deal ID which caused the process to be called.

If a pricing exception occurs during revaluation, the pricing exception will be reported, and will reference the affected entities if possible. [MS: it is not clear how to determine which entities are affected by 

A Pricing Exception workflow will record the following information:
a.	The test which determined that a pricing exception has happened.
b.	The job specification that kicked of the pricing process.
c.	The credit system deal ID.
d.	The Timestamp.

Pricing Exceptions will be listed in a view in the credit system. The specific conditions that will create a Pricing Exceptions will be described in model component DRS documents. Common deal exceptions include, but are not limited to, the following cases:
a.	Missing or invalid counterparty data.
b.	Missing or invalid market data.
c.	All instances of non-standard handling of data.
d.	Calibration Exception.
e.	Simulation Exception.
f.	Deal failed to price.
g.	Deal value outside acceptable threshold.




References:

				
   
[Zenodo swaption](https://zenodo.org/record/5771060/files/Zenodo-IrSwaption.pdf)
   
[OSF swaption](https://osf.io/f7yw9/download)

[Zenodo pass](https://zenodo.org/record/6549222)

[github mba swap](https://github.com/cfrm17/MBASwap)
   
