## Deal Entry Validation

Deals are validated as they are written to the SDR, which is prior to the deal being valued by a pricer. Deal details are validated in the Deal Validation Process at the point.

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

During deal entry, a deal entering the system that is not rejected will have additional validation tests applied to the deal details. Note that in the current state, a Validation Exception would be called 
a Non-standard Violation.

Any deal that fails a validation test will generate a Validation Exception workflow. A Validation Exception workflow will record the following information:
a.	The validation test which caused the validation fail.
b.	The Source System the rejected deal came from.
c.	The credit system deal ID.
d.	The Timestamp.

Validation Exceptions will be listed in a view in the credit system. In the Validation Exception detailed view, a user will be able to view:
a.	Deal details in a “Deal Modify” view.
b.	Validation Exception Properties.



References:


[Zenodo callable](https://zenodo.org/record/5765076)

[Zenodo bma swap](https://zenodo.org/record/6558053)

[OSF callable](https://osf.io/qkbfn/download)

[Gitbook callable](https://cmrm11.gitbook.io/callable-bond/)

[github digital](https://github.com/timxiao1203/DigitalOption)

