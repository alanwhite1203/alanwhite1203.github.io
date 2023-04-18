## Cross Currency Option 
   
A non-quanto cross currency option is a currency translated option of the type foreign equity option struck in domestic currency, which is a call or put on a foreign asset with a strike price set in domestic currency and payoff measured in domestic currency.

We present a model for pricing non-quanto cross currency option in which the spot underlying price in foreign currency is converted into an amount in domestic currency using the spot exchange rate.  This amount is then adjusted by the current value of predicted future discrete dividends, measured in domestic currency.  The option is valued using the Black-Scholes formula for the vanilla European style or the Michael Curran’s method for the Asian style, with the domestic risk-free interest rate as the drift rate for the translated stock.

Since there are two sources of uncertainties involved in the option, one resulting from underlying price changes and the other resulting from changes in the exchange rate, this option is non-quanto.  The holder of the option bears the risk caused by the fluctuation of the exchange rate between the underlying currency and the payoff currency.  

The values of vanilla European call/put options can be calculated by using the closed form Black-Scholes formula.  For Asian options of European style, either Monte Carlo simulation or the Michael Curran’s approximation can be employed for pricing.  Instead of using  , the composite volatility   must be used in these pricing formulae.

As to the discrete dividends, since they are a riskless component in the stock price dynamic, the spot stock price should be reduced by the present value of all the dividends during the life of the option.  Let   be the current value date.   Taking the predicted discrete dividends of the underlying stock into account, the translated stock price at time zero is given by

The aforementioned options are actually currency translated options of the type foreign equity option struck in domestic currency, which is a call or put on a foreign asset with a strike price set in domestic currency and payoff measured in domestic currency.  	

We test the model in several cases. In all the testing cases, a composite volatility of 0.45 is used.  This composite volatility is calculated using an underlying stock volatility of 0.3, an exchange rate volatility of 0.31, and a correlation coefficient of 0.1.  We assume the payment date of a dividend is one month (1/12 year) after the ex-dividend date.


References:

   
[ResearchGate xccy option pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369921018_Non-Quanto_Cross_Currency_Option_Model/links/64347105ad9b6d17dc4b8548/Non-Quanto-Cross-Currency-Option-Model.pdf)
   
[ResearchGate xccy option](https://www.researchgate.net/publication/369921018_Non-Quanto_Cross_Currency_Option_Model)

[archive calibration](https://ia601402.us.archive.org/23/items/correlation-calibration/CorrelationCalibration.pdf)

[gitbook capital](https://cmrm11.gitbook.io/capital-model/)

[core himalaya pdf](https://core.ac.uk/download/534871132.pdf)

[core himalaya](https://core.ac.uk/works/127931221)
   