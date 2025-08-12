## 	Bank Credit Group
   
For counterparties in the industry, “Banking”, the Portfolio Manager Owner role and the Credit Manager Owner role are filled by the same user, and this user is given the role “Bank Credit Group Owner (BCG-owner)” 
for a given Customer or Connection.

When applying the “send to Market Risk” transition, the only allowable next owner will be the “Counterparty Risk Reporting” Group User (which is a group of users). When a violation is created, by default, the first 
owner for the workflow process will be the Deal Trader from the marginal deal causing the violation. There are additional special cases as follows: It will be possible to assign the deal to the manager of the trader.

When an excess is created, by default, the first owner for the workflow process will be the Portfolio Manager owner for the Customer or Connection associated with the limit breach.

Where a violation is created for a customer with no PM-owner, the Trader will have the following options: The trader CANNOT immediately transition the trade to a PM. This option will be greyed out with an explanation 
that there is no PM-owner. The trader will need to identify the PM and ask for this information to be updated in the source system. Upon the PM-owner being updated, the trader can then transition 
the trade to the PM-owner. The trader will also have the option to send the violation to Market Risk, or to select any other transition that would normally be available. 

Where a violation is created for a customer with no CM-owner: A portfolio manager CANNOT immediately transition the trade to a CM. This option will be greyed out with an explanation that there is no CM-owner. 
The PM will need to identify the CM and ask for this information to be updated in the source system. Upon the CM-owner being updated, the PM may then transition the trade to the CM-owner.
The PM will also have the option to transition the workflow to Market Risk, or to select any other transition that would normally be available

Where a trade enters system and the counterparty is not in system:
a.	Irrespective of the counterparty being set up in system the risk will be immediately captured (despite having no valid counterparty) and a violation/excess may be created.
b.	If an excess is created where there is no PM-owner/BCG-owner, then the “Counterparty Risk Reporting” Group User (a group of users) will be the first workflow owner.


References:

   
[ResearchGate strip pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369931682_Strip_Rho_Calculation/links/643566e3ad9b6d17dc4ed8e7/Strip-Rho-Calculation.pdf)
   
[ResearchGate strip](https://www.researchgate.net/publication/369931682_Strip_Rho_Calculation)

[archive local](https://ia904700.us.archive.org/23/items/local-vol-quanto/LocalVolQuanto.pdf)

[gitbook methodology](https://cmrm11.gitbook.io/debt-specific-risk-methodology/)

[core american pdf](https://core.ac.uk/download/534871192.pdf)

[core american](https://core.ac.uk/works/127931203)
   
