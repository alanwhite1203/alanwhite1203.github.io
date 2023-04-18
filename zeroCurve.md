## Zero Curve 
   
We present a Zero Curve Bootstrap Algorithm to allow more cash and futures contracts as underlying instruments for curve generation. 

All computation is carried out with all input rates converted into continuous compounding with Actual/365. We simplify rates and day count fraction with continuous compounding and actual/365 as the following.

where CON represents continuous compounding. Once final curve is constructed, it is converted into semi-annual rates with actual/365 to be compared with curve (output). 

The short end of the curve is derived from over-night, tomorrow night, one week, one-month, two-month and three-month cash deposit rates. The medium segment of the curve is derived from interest rate futures contracts. The following table summarizes the details of the underlying instruments (inputs) for Canadian and US curve generation.

As the overnight is zero-coupon rate, it just needs to be converted with continuously compounded rate with actual/365. In other words, it is converted using the formula

where SIM represents simply compounded rate and T is the maturity of overnight rate. Other rates apply to forward-starting time periods and converted into continuously compounded forward rates with actual/365 as the following.

Valuation date is June 22, 2005. The details of underlying instruments for curve generation are presented in the appendix. Testing on arbitrage-free condition, i.e. re-pricing of the underlying instruments by computing implied forward rates from constructed curve.


References:

   
[ResearchGate zero curve pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369920969_Zero_Curve_Construction/links/6434782bad9b6d17dc4b85f1/Zero-Curve-Construction.pdf)
   
[ResearchGate zero curve](https://www.researchgate.net/publication/369920969_Zero_Curve_Construction)

[archive seasonality](https://ia601508.us.archive.org/12/items/seasonality-adj/SeasonalityAdj.pdf)

[gitbook debt](https://cmrm11.gitbook.io/debt-specific-risk-backtesting/)

[core hw convertible pdf](https://core.ac.uk/download/534871138.pdf)

[core hw convertible](https://core.ac.uk/works/127933256)
   