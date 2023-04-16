## Bet Option 
   
A bet option is a bet on a basket of stocks.  There are multiple reset periods before the maturity of the option.  At the end of each period, if all the stocks in the basket are above their respective strikes, the option will payout a rebate amount for this period at maturity.

We propose a model for pricing bet option based on Monte Carlo simulation. 

Let m be the number of assets in a given basket,   be the price process of the jth underlying asset in the basket and  .  Let   be a set of reset dates and   be a payoff settlement date or maturity.  The bet option on the basket of stocks is a European style derivative security whose matured payoff at the settlement date T is given by

Our test is based on several trades or transactions. In this sample transaction, Monte Carlo simulation associated with stratified sampling variance deduction is employed to evaluate the option.  There are three underlying assets whose prices are correlated, and five reset dates. We get market data from FinPricing (https://finpricing.com/lib/IrCurve.html)

The initial price for each asset is 100, and the strike for each asset is 100.  The calculated option value is 14.0547 when 2000 simulations and 2000 samples in stratified sampling are used.  Keeping the 2000 stratified samples unchanged, calculations with more simulations are conducted.  Table 1 shows the simulated results.

We also tested cases with different strike levels.  Table 3 presents the results of these cases. Relative errors are calculated for different models.  It can be seen from Tables 1, 2 and 3 that the results from the two models converge as the number of simulations becomes large in all cases.  The differences are within the tolerable range.


References:

   
[ResearchGate bet pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369878537_Bet_Option_Model/links/643025894e83cd0e2f97a3b5/Bet-Option-Model.pdf)
   
[ResearchGate bet](https://www.researchgate.net/publication/369876624_Asian_Basket_Relative_Performance_Option_Model)

[OSF himalayan](https://osf.io/cg5x4/download)

[Bitbucket P&L](https://bitbucket.org/timxiao1203/profit-and-loss-explanation/downloads/PnLExplain.pdf)

[core forwarding start pdf](https://core.ac.uk/download/534871134.pdf)

[core forwarding start](https://core.ac.uk/works/127933887)
   