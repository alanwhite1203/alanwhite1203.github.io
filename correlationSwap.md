## Correlation Swap 
   
We developed a conventional mark-to-market/pricing model for a new product Correlation Swap. The payoff of the correlation swap at maturity is the difference between the realized correlation (of a basket of stock indices) and the strike. The realized correlation has two main components: historical correlation part and future realized correlation part.

We use the current correlation swap strike level on the market (available for exactly the remaining swap period) as the expectation of future realized correlation part. This way the essential part needed for the mark-to-market model becomes a direct input. The market level should be verified independently by middle office. Capping (flooring) can be included in the definition of the realized correlation (making part of payoff option-like, but this conventional MTM model extends its simplified view to such actions too).

where the expectation of the future realized correlation is evaluated directly using the current correlation swap (fair) strike level on the market for exactly the remaining of the swap period (if available), MTMCorr, and then the cap and floor are applied.     

We test several cases. The results are shown below:


References:

   
[ResearchGate correlation swap pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369898787_Correlation_Swap_Model/links/6431a73420f25554da1b4848/Correlation-Swap-Model.pdf)
   
[ResearchGate correlation swap](https://www.researchgate.net/publication/369898787_Correlation_Swap_Model)

[OSF bond curve](https://osf.io/4nhyb/download)

[Bitbucket calibration](https://bitbucket.org/timxiao1203/dividendcalibration/downloads/dividendCalibration.pdf)

[core rainbow pdf](https://core.ac.uk/download/534868019.pdf)

[core rainbow](https://core.ac.uk/works/127930421)
   