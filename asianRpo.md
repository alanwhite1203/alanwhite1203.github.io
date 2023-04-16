## Asian Basket Relative Performance
   
The pay of a basket Asian relative performance option (RPO) is determined by the difference between the performance of a reference stock and that of a basket of stocks, where performance is defined as the ratio of (weighted) average of two sets of averaging dates. A model is presented for pricing basket Asian RPO using Monte Carlo simulation.  

The above formulae are in a world that is forward risk-neutral with respect to a specific currency  .  If an underlying asset j is measured in another currency  , the governing price dynamics of this underlying asset in the risk-neutral world of   should be written as

We test the model via several trades (transactions). In these sample transactions, Monte Carlo simulation associated with stratified sampling variance deduction is employed to evaluate the option.  In the first sample transaction, there are six stocks, one as a reference, and the other five in a basket with equal weight.  These underling stocks and the option are all measured in CAD.  A strike share table is provided so that a share number can be interpolated based on the relative performance.  The initial price for each asset is 100.  The calculated option value is 96.5776 when 2000 simulations and 2000 samples in stratified sampling are used.  Keeping the 2000 stratified samples unchanged, calculations with more simulations are conducted.  Table 1 shows the simulated results.

In the second sample transaction, there is only one stock in the basket.  The initial prices for the reference stock and the stock in the basket are both 100.  The underlying and the option are both measured in CAD.  Other input data are the same as the first sample transaction.  The input data for the third sample transaction are identical to the second one except that the reference stock is measured in USD while the only stock in the basket is CAD.  

It can be seen from Tables 1 that the results from the two models converge as the number of simulations becomes large in all cases.  The differences are within the tolerable range.



References:

   
[ResearchGate Asian RPO pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369876624_Asian_Basket_Relative_Performance_Option_Model/links/64301f20609c170a13fd4cc1/Asian-Basket-Relative-Performance-Option-Model.pdf)
   
[ResearchGate Asian RPO](https://www.researchgate.net/publication/369876624_Asian_Basket_Relative_Performance_Option_Model)

[OSF gic](https://osf.io/atyb9/download)

[Bitbucket flow](https://bitbucket.org/timxiao1203/market-risk-data-flow/downloads/MarketRiskDataFlow.pdf)

[core cms spread pdf](https://core.ac.uk/download/534871211.pdf)

[core cms spread](https://core.ac.uk/works/127931161)
   