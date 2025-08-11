## Violations and Excesses

There will be multiple violation and excess processes to handle the different cases of limits that have been breached: Customer, Country, Settlement, and Tenor.

It is often the case that a single deal will create multiple violations. Violations from the same deal and in the same process will be transitioned together automatically. For violations that enter the same 
workflow process and are from the same deal (or portfolio), the system will automatically group the violations together as a violation group. 

All violations in the violation group will then automatically be presented as a single workflow. Transitions are applied to the “single violation group workflow” and are then automatically applied to 
all of the violations.

For the purpose of exception management, users with appropriate rights will have access to view the single violations rather than only for the less granular “violation group workflow”. Additional fields can be 
displayed when single violations are shown, rather than violation groups.

The system will allow the user to group workflows together within the same process and Bulk Transition them as a group by applying the same transition to each workflow. Grouping workflows can be done by applying 
search criteria to workflows and defining a group by visually tagging the desired workflows.

Irregular Prior Approval (IPA). When a Portfolio Manager (PM) does not confirm the pre-transaction approval of a violation, the Trader is directed to unwind the trade. Where the Account Manager has not conveyed 
an authorization for the violation and the trade is not unwound, an IPA flag on the violation is set to ‘YES’ in the system. For the violation process and for an Approval transition, it will be possible for Portfolio 
Managers to set an “IPA flag” to “YES”. Relay this information to the trader in the source system.

Exposure will be stored for each monitored risk measure for each of the following 3 times:
a.	The exposure in Jaguar based on the source system time stamp
b.	The (pre-calculation) exposure in Jaguar based on the Jaguar time stamp
c.	The (post-calculation) exposure in Jaguar based on the Jaguar time stamp



References:


[Zenodo zero bond](https://zenodo.org/record/5765447)

[OSF zero bond](https://osf.io/d59wu/download)

[Gitbook zero](https://cmrm11.gitbook.io/zero-coupon-bond/)

[github collatral swap](https://github.com/cfrm17/CollateralizedSwap)





   
