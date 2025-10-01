## Auto-Close Threshold (ACT) Condition
   
In the situation where: 1. A limit with an ACT is breached, 2. The breach is not due to deal entry, and 3. The Highest Excess Amount is less than the ACT, Then, the excess will be “automatically closed by the system”.

In the situation where: 1. A limit with an ACT is breached, 2. The breach is not due to deal entry, and 3. The Highest Excess Amount is above the ACT, Then, a new Excess will be created, and a new workflow approval
process will be triggered.

This will not allow violations above the limit, but below the “Automatic Close Threshold”.  In the situation where: 1. A limit with an ACT is breached, 2. The breach is due to deal entry, and
3. The Highest Excess Amount is below the ACT, Then, a Violation will be created.

10.	An ACT is connected to a limit and becomes effective when the workflow describing the ACT reaches the “Approved” state in the Excess Approval workflow

There will be a “configurable max threshold”. a.	The maximum threshold will cap the value of the ACT at a percentage above each associated limit. b.	The option for an Excess Automatic Approval will be greyed out 
and cannot be selected for a limit excess that is 20% (or greater) above the limit.


It will be possible for a user to determine how an ACT was created. If created within a Excess Approval workflow, then the ACT will store a reference to the Workflow from which the ACT was created.


	

References:

   
[Zenodo touch](https://zenodo.org/record/6491587/files/Zenodo-FxTouch.pdf)
   
[OSF touch](https://osf.io/6m5jx/download)

[Zenodo adjusted](https://zenodo.org/record/6539925)

[github hedge](https://github.com/cfrm17/AssetsHedge)
   
