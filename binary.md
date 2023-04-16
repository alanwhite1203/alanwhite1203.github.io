## Binary Return Note 
   
The structure of a Binary Return Note is similar to the one of a regular note, but the coupons are contingent on return rates on stocks. We developed and implemented a Monte Carlo (Quasi-Monte Carlo) pricing model for the Binary Return Note product.

We give a detailed description of the product here. Let   be n stocks (underlying prices) or stock indices. They can be in different currency markets. Let 0 be the current time, and T be the maturity date. Let   be a fixed reset date schedule. Let   be the list of strikes. Let   be a fixed positive constant. Let N be the notional.

The above expectation is in a world that is risk-neutral with respect to the payoff currency (we have already assumed deterministic interest rates).  As we may have underlying in different currency markets, we need to represent all dynamics in the payoff currency measure. 

The Monte Carlo method for computing expectations consists in simulating the cashflow sequence M times (where M is a large number) and taking the average. If the valuation date is later than a reset date, then the realized return rate should be used. Quasi Mote Carlo (QMC) method (Sobol low discrepancy sequences and Brownian bridge path generation) is used. Such a method has an improved convergence speed. We also use crude Monte Carlo for comparison. For the main issues that arise when computing sensitivities. It is known that Gamma requires a high number of simulations.

The three deals considered differ by the stock correlation matrix (the last two of them are extreme cases), as this is one the most important risk factor (multi-path generation starts with a multi-dimensional Brownian motion whose correlation matrix is our stock correlation matrix). Table 1 shows small discrepancies between QMC with 20,000 simulations. Relative difference is defined by (QMC-Crude MC) (reported as percentage).

Other important factors are stock volatilities, FX rate volatilities and stock/FX rate correlation. Sensitivities with respect to these factors are computed by the model. We illustrate the computation of a few of them in Table 2 (for FTSE index). Table 3 shows a full sensitivity report for 20K, 40K, 60K, 80K, and 100K (QMC model). We measure the maximum of the consecutive relative differences and the maximum of the relative differences with respect to QMC@100K, which, theoretically, provides the most accurate values. Table 4 shows that if we exclude the 20K case, these maxima improve drastically (especially for the most troublesome sensitivity, Gamma). This proves, once again, the need of using a bigger number of simulations in the Monte Carlo computations of sensitivities.


References:

   
[ResearchGate binary pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369878648_Binary_Return_Note_Model/links/64302aec20f25554da15a5ca/Binary-Return-Note-Model.pdf)
   
[ResearchGate binary](https://www.researchgate.net/publication/369878648_Binary_Return_Note_Model)

[OSF vol](https://osf.io/h35rm/download)

[Bitbucket backtest](https://bitbucket.org/timxiao1203/backtest-exception/downloads/BacktestException.pdf)

[core bb pdf](https://core.ac.uk/download/534871150.pdf)

[core bb](https://core.ac.uk/works/127933859)
   