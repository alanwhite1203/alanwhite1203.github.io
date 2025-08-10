## Counterparty Credit Risk Violation Workflow
   
The Counterparty Credit Risk (CCR) Customer Violation Approval process allows credit limit breaches that were caused by a single deal to be approved or closed by the appropriate users. 
The entity being approved is a Violation Group, which is a group of Violations.


There will always be a current owner for a workflow process that is in progress. A workflow process that is in a terminal state will have no owner.
The current owner will be able to apply a transition. Proxy. An effective delegate of the current owner will also be able apply a transition. 
Excluding the cases above, it will not be possible to apply a transition.

At every step throughout the workflow, it will be possible to perform the following actions: It is possible for the user to attach a document, or multiple documents;
It is possible for the user to attach a screenshot, or multiple screenshots; It is possible for the user to add/update comments.

A workflow instance will be created automatically by the Limit Breach Check process. The first owner will be the trader from the deal causing the limit breach.
The Job Spec which caused the limit breach will be recorded.

The next owner must be the Customer/Connection “CM-Owner”. See the Force Next Owners Appendix. Excess Auto-Close Threshold. It will be possible to create/update an Excess Auto-Close 
Threshold for the limit breached by the given Excess. Add-on Flag. It will be possible to categorize the Violation/Excess as utilizing the “Add-on” process.
Irregular Prior Approval Flag. It will be possible to categorize the Violation/Excess as an Irregular Prior Approval. Send an alert to the next owner.

The next owner must be the user who previously applied the transition, Acknowledge (to move the workflow from “With Trader” to “With Portfolio Manager”. Send an alert to the next owner.




References:

   
[Zenodo future option](https://zenodo.org/record/6494261/files/Zenodo-IrFutureOption.pdf)
   
[OSF future option](https://osf.io/gbzj3/download)

[Zenodo mortgage](https://zenodo.org/record/6548953)

[github knockout](https://github.com/cfrm17/KnockoutSwap)

