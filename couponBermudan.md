## 	User Rights for Violation and Excess Approval
   
Every violation and excess workflow process will have a current owner. The current owner can be a single user. The current owner can be a single Group that is “Workflow Eligible”.

A given user will have user rights to transition a violation/excess workflow process ONLY IF: 
a.	The given user is the current owner.
b.	The current owner is a Group User, and the given user of a member of the Current Owner/ Group User.  
c.	The current owner has named a delegate that is currently in effect, and the given user is the delegate of the current owner.
d.	Note that in the case where the current owner has named a delegate that is in effect, the current owner will not have the user rights to apply a transition.

There will be a mandatory Portfolio Manager Owner for each: Customer and Connection
b.	When a Violation Group is created for Customer limits, Connection limits, or Country limits, a workflow will be created. The only allowable owner for the “with Portfolio Manager” state will be the Customer Portfolio Manager Owner.
c.	When an Excess is created, a workflow will be created. The entry state will be “with Portfolio Manager”, and the “Current Owner” of the workflow will be set to:
1.	The Customer Portfolio Manager Owner if the Excess is for a Customer Limit.
2.	The Connection Portfolio Manager Owner if the Excess is for a Connection Limit.
d.	There will be no default Portfolio Manager Owner (in the event that an Entity has no Owner) because there will be a Portfolio Manager Owner for every Customer and Counterparty. 

There will be a Credit Manager Owner for each: Customer and Connection
b.	When a Violation Group is created for Customer limits, or Connection limits, a workflow will be created. The only allowable owner for the “with Credit Manager” state will be the Customer Credit Manager Owner.
c.	When an Excess is created for Customer limits, or Connection limits, a workflow will be created. The only allowable owner for the “with Credit Manager” state will be:
1.	The Customer Credit Manager Owner if the Excess is for a Customer Limit.
2.	The Connection Credit Manager Owner if the Excess is for a Connection Limit.
d.	There will be no default Credit Manager Owner (in the event that an Entity has no Owner) because there will be a Credit Manager Owner for every Customer and Counterparty.

There will be one Country Owner. When a Violation Group is created for a Country limit, a workflow will be created. The only allowable owner for the “with Country Manager” state will be the Customer Owner.
When an Excess is created for a Country limit, a workflow will be created. The entry state will be “with Country Manager”, and the “Current Owner” of the workflow will be set to the Country Owner.


References:

   
[ResearchGate bermudan pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369997758_Zero_Coupon_Bermudan_Swaption_Model/links/64384275ad9b6d17dc54fe88/Zero-Coupon-Bermudan-Swaption-Model.pdf)
   
[ResearchGate bermudan](https://www.researchgate.net/publication/369997758_Zero_Coupon_Bermudan_Swaption_Model)

[archive convertible](https://ia904707.us.archive.org/6/items/hw-convertible/HwConvertible.pdf)

[gitbook gic](https://finwhite.gitbook.io/gicpool/)

[core asr pdf](https://core.ac.uk/download/534867878.pdf)

[core asr](https://core.ac.uk/works/127929898)
   
