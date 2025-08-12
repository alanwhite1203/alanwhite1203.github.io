##	Auto-close Excesses
   

Approve and Auto-close excesses for 6 months. It will be possible to approve a limit breach and have subsequent excesses be “automatically closed by the system” until a set expiry date. This avoids the situation 
where a Portfolio Manager or a Credit Manager must approve an excess on the same limit repeatedly after each revaluation. 
  
An “Excess that is automatically closed” will not create any workflow process related to the excess. It will be possible to connect an Auto-Close Threshold (ACT) to a single given limit. 
a.	It will be possible to connect an ACT to a Potential Future Exposure (PFE) limit, and to a Notional limit.
b.	It will NOT be possible to connect an ACT to a Tenor limit.
c.	There can only be one ACT connected to a limit that is effective at a given time. Updating an ACT value, will expire out the previous ACT value and ACT expiry date.
d.	The ACT will be stored as an incremental threshold. It will be compared against the Highest Excess Amount.

The ACT value will be set equal to the Highest Excess Amount for the given limit. Create multiple ACTs from Violation Approval. It will be possible to create multiple ACT from the approval process of a single Violation Group.
For each given Violation in the Violation Group, there will be one ACT created for the associated limit. Each ACT will have a value equal to the Highest Excess Amount for the associated limit.    
  
An ACT will apply for a default period of 6 months, after which a set expiry date will be reached and the ACT will no longer be in effect. The ACT expiry date will be determined by incrementing upon the date 
on which the given excess was created. It will also be possible to select a period of 3 months.

In the situation where:
1. A limit with an ACT is breached,
2. The breach is not due to deal entry, and
3. The Highest Excess Amount is less than the ACT,
Then, the excess will be “automatically closed by the system”.

  

References:

   
[ResearchGate decreasing asian pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369898965_Decreasing_Basket_Asian_Option_Model/links/6431bd704e83cd0e2f9d3932/Decreasing-Basket-Asian-Option-Model.pdf)
   
[ResearchGate decreasing asian](https://www.researchgate.net/publication/369898965_Decreasing_Basket_Asian_Option_Model)

[OSF tree](https://osf.io/6eyrv/download)

[OSF arrear](https://osf.io/g6tp5/download)

[core bond curve pdf](https://core.ac.uk/download/534871175.pdf)

[core bond curve](https://core.ac.uk/works/127931168)
   
