## Credit Default Swap
   
We present a pricing model for credit default swap with a term structure of default swap spreads (referred to as CDS/T hereinafter).  The model calibrates a term structure of hazard rates independently from the target default swap we want to price. Quarterly schedule of swap dates is built and hazard rates are bootstrapped such that the market default swaps are at par.

Each of these maturity dates has to be identical to one of the payment dates in the target default swap; otherwise, those that cannot match any payment date in the target default swap will be changed to the closest payment dates.  If the target default swap is forward starting or finishes before the last maturity date in the term structure file, we will extend the quarterly payment dates of the target swap to the value date or to the last maturity date in the term structure, and use extended payment dates of the target swap for the calibration purpose.  As such, calibration is dependent on the payment dates of the target swap.


Once calibration of a term structure of hazard rates is completed, the target swap can be priced.  Currently, the model only allows fee payment at payment dates and does not allow accrued fee when default occurs.  If a payment date in the target default swap falls between two calibration pay dates, linear interpolation is employed in the model to find the hazard rate associated with the target payment date.  This is equivalent to using a time-weighted average of hazard rates in a payment period of the target swap as a flat hazard rate for that period, so long as the length of each payment period of the target swap is the same as that of the swaps for calibration. 

There are two ways the user can input the term structure of default swap spreads.  The first has the following format

where the first column represents the tenors of market swaps in years with respect to the value date (referred to as time to value date in years), and the second column represents default swap spreads.  Another format of the term structure of default swap spreads is given as follows

where the first column is the maturity dates of market swaps (referred to as maturity dates), and the second column is still default swap spreads.  Calibration of the term structure of hazard rates is dependent upon the format of the term structure of default swap spreads.

If a term structure of default swap spreads is provided in the first format, calibration is independent on the target default swap we want to price.  Time to the value date in years must be divisible by 0.25 so that quarterly payment dates can be generated; otherwise the program will give an error message. 


References:

   
[ResearchGate cds pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369880868_Credit_Default_Swap_Model/links/643052d520f25554da17af1a/Credit-Default-Swap-Model.pdf)
   
[ResearchGate cds](https://www.researchgate.net/publication/369880868_Credit_Default_Swap_Model)

[OSF hw convertible](https://osf.io/eyb8c/download)

[Bitbucket commodity vol](https://bitbucket.org/timxiao1203/volrate/downloads/CommodityVol.pdf)

[core quanto pdf](https://core.ac.uk/download/534866609.pdf)

[core quanto](https://core.ac.uk/works/126047802)
   