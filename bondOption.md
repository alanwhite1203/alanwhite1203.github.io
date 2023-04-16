## Bond Futures Option 
   
We present a pricing model for bond futures options.  Assuming that the bond futures price at the maturity of the option is lognormal, the model adopts the Black’s analytical closed-form solution.

For bond futures options, the futures price is taken directly from the market instead of being calculated from the bond futures calculator.


Let BF  be a price process of a given bond futures, and T be a payoff maturity date.  The bond futures option with the underlying BT is a European type derivative security whose matured payoff at the settlement date is given by

where beta (+1 for call, -1 for put) is the call-put index, X is the strike.  Assuming that the bond futures price at the maturity of the option is lognormal, the prices of bond futures options at time zero are given by using the Black’s formula, which are

The above pricing formulae are based on the assumption that the futures price is a martingale, i.e., there is no drift term in the futures price dynamics.

There are closed-form solutions available for the Greek values for options described above.  We adopt closed-form solutions for Deltas and Gammas, which are given by

We test the bond futures option model in several cases. The first case is a call option, with the value date of 20031212 10:54, the futures price of 111.0, the risk free interest rate of 0.01, the volatility of the futures price of 0.05, and the option maturity of 20040221 10:54.  

The second case is a put option with the same inputs as the first case except that the volatility is 0.10.


References:

   
[ResearchGate bond opton pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369879832_Bond_Option_Model/links/6430416120f25554da15b598/Bond-Option-Model.pdf)
   
[ResearchGate binary](https://www.researchgate.net/publication/369879832_Bond_Option_Model)

[OSF forward starting](https://osf.io/3vq8t/download)

[Bitbucket verification](https://bitbucket.org/timxiao1203/price-verification/downloads/IndependentValidation.pdf)

[core cap vol pdf](https://core.ac.uk/download/534864981.pdf)

[core cap vol](https://core.ac.uk/works/127928666)
   