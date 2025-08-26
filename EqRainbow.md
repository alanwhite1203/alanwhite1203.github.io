## Violations Approval Process

There will be multiple violation and excess processes to handle the different cases of limits that have been breached:
a.	Customer
b.	Country
c.	Settlement
d.	Tenor

It is often the case that a single deal will create multiple violations. Violations from the same deal and in the same process will be transitioned together automatically.
a.	For violations that enter the same workflow process and are from the same deal (or portfolio), the system will automatically group the violations together as a violation group. 
b.	All violations in the violation group will then automatically be presented as a single workflow
c.	Transitions are applied to the “single violation group workflow” and are then automatically applied to all of the violations.
d.	For the purpose of exception management, users with appropriate rights will have access to view the single violations rather than only for the less granular “violation group workflow”. 
Additional fields can be displayed when single violations are shown, rather than violation groups.

The system will allow the user to group workflows together within the same process and Bulk Transition them as a group by applying the same transition to each workflow. Grouping workflows can be done 
by applying search criteria to workflows and defining a group by visually tagging the desired workflows.

Irregular Prior Approval (IPA). When a Portfolio Manager (PM) does not confirm the pre-transaction approval of a violation, the Trader is directed to unwind the trade. Where the Account Manager has 
not conveyed an authorization for the violation and the trade is not unwound, an IPA flag on the violation is set to ‘YES’ in the system. 
a.	For the violation process and for an Approval transition, it will be possible for Portfolio Managers to set an “IPA flag” to “YES”.
b.	Relay this information to the trader in the source system.



References:
   
   
[Zenodo rainbow](https://zenodo.org/record/5759794)
   
[OSF rainbow](https://osf.io/47zwk/download)

[gitbook rainbow](https://davidlee1203.gitbook.io/rainbow-option/)

[github mbs](https://github.com/timxiao1203/MBS-Model)
