## Excess Auto-Close Threshold (ACT) Requirements
   
Approve and Auto-close excesses for 6 months. It will be possible to approve a limit breach and have subsequent excesses be “automatically closed by the system” until a set expiry date. 
This avoids the situation where a Portfolio Manager or a Credit Manager must approve an excess on the same limit repeatedly after each revaluation. 

An “Excess that is automatically closed” will not create any workflow process related to the excess. It will be possible to connect an Auto-Close Threshold (ACT) to a single given limit. 
It will be possible to connect an ACT to a Potential Future Exposure (PFE) limit, and to a Notional limit. It will NOT be possible to connect an ACT to a Tenor limit.

There can only be one ACT connected to a limit that is effective at a given time. Updating an ACT value, will expire out the previous ACT value and ACT expiry date. The ACT will be stored 
as an incremental threshold. It will be compared against the Highest Excess Amount.


The ACT value will be set equal to the Highest Excess Amount for the given limit. Create multiple ACTs from Violation Approval. It will be possible to create multiple ACT from the approval 
process of a single Violation Group. Let the present values, at time T, of the domestic and foreign floating leg cash flows be respectively defined as

For each given Violation in the Violation Group, there will be one ACT created for the associated limit. Each ACT will have a value equal to the Highest Excess Amount for the associated limit.    

An ACT will apply for a default period of 6 months, after which a set expiry date will be reached and the ACT will no longer be in effect. The ACT expiry date will be determined by incrementing 
upon the date on which the given excess was created. It will also be possible to select a period of 3 months.



References:

   
[ResearchGate xccy swaption pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369997382_Cross_Currency_Swaption_Model/links/6438378620f25554da2bbae9/Cross-Currency-Swaption-Model.pdf)
   
[ResearchGate xccy swaption](https://www.researchgate.net/publication/369997382_Cross_Currency_Swaption_Model)

[archive factor](https://ia804703.us.archive.org/1/items/threeFactorConvertible/threeFactorConvertible.pdf)

[gitbook kpi](https://cmrm11.gitbook.io/var-model-kpi/)

[core bond pdf](https://core.ac.uk/download/534868164.pdf)

[core bond](https://core.ac.uk/works/126057829)
   
