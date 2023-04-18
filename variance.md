## Variance Swap  
   
A variance swap is a forward contract on annualized variance, the square of the realized volatility.  The holder of a variance swap at expiration receives a notional amount of dollar for every point by which the stock’s realized variance has exceeded the variance delivery price.  Valuation of the swap involves decomposition of the contract into two periods, one that has become historical, and the other with stock prices still unknown.  

The unknown variance from the value date to the swap maturity can be replicated by a portfolio of call and put options. Volatility skew can be incorporated into pricing of these options through bi-linear interpolation The new pricing model accounts for the expected contribution from the current trading day and admits discrete dividend schedules. 

We test several cases. The results are shown below:

We also tested the calculation of Greeks according to the methodology. Here, we present the details of Delta calculation only. For more on this (Gamma, Vega, Rho).


References:

   
[ResearchGate variance pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369907899_Variance_Swap_Model/links/6433107420f25554da1d49fb/Variance-Swap-Model.pdf)
   
[ResearchGate variance](https://www.researchgate.net/publication/369907899_Variance_Swap_Model)

[OSF digital](https://osf.io/azy78/download)

[gitbook backtest](https://cmrm11.gitbook.io/counterparty-credit-risk-backtesting-methodology/)

[core ois pdf](https://core.ac.uk/download/534864745.pdf)

[core ois](https://core.ac.uk/works/125999398)
   