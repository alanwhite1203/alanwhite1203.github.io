## Dividend Enhancement Common Stock 
   
A dividend enhancement common stock (or DECS) instrument is a portfolio of stock options and a fixed coupon stream. The DECS is developed to price a corporate financing structure with the option that the debt principal can be converted to the underlying common stock at maturity date. Monte Carlo simulation associated with stratified sampling variance deduction is employed to evaluate the option.  There are six underlying assets whose prices are correlated, and six reset dates.  The initial price for each asset is 100, and the notional amount of the option is 100.  The strike is set to be zero.  The calculated option value is 19.8709 with a drop-worst strategy when 2000 simulations and 2000 samples in stratified sampling are used.  If a drop-best strategy is adopted, the option value is 21.4410.  Keeping the 2000 stratified samples unchanged, calculations with more simulations are conducted.  Table 1 shows the simulated results.

Since all the options involved are European options, pricing of a DECS structure is equivalent to pricing each of the individual component and aggregating the value. In the following sections, we will first discuss the business background where the DECS is derived and then discuss the related pricing issues. 

A DECS structure can be considered as an extension to a convertible bond financing structure. Similar to convertible bonds, the DECS structure offers the debt holder the right to convert the principal of the debt into the underlying common stocks at maturity. In addition to the convertible option, DECS includes an obligation to the investor that a conversion is required even if the stock price is low. The DECS structure is actually a combination of a long bond, long calls and short puts. 

Consider a particular convertible bond, which pays a regular coupon of rate  and matures in   years.  At maturity, the bond principal will be converted to the underlying common stock according to the following rules: 

The part in the bracket is exactly a DECS portfolio, which includes a common stock, i.e. the call option with strike zero, a short call option with a low strike, a long position in call option with a higher strike and a stream of cash flows similar to a fixed swap leg of notional  .  This is how a DECS is derived from. 


References:

   
[ResearchGate decs pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369899160_Dividend_Enhancement_Common_Stock_Model/links/6431c488ad9b6d17dc44d4b8/Dividend-Enhancement-Common-Stock-Model.pdf)
   
[ResearchGate decs](https://www.researchgate.net/publication/369899160_Dividend_Enhancement_Common_Stock_Model)

[OSF tree](https://osf.io/efy6v/download)

[core collateral pdf](https://core.ac.uk/download/534863864.pdf)

[core collateral](https://core.ac.uk/works/127931261)
   