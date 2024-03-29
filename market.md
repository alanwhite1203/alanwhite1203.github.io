## Financial Markets


[Credit market reference](https://derivatives.hcommons.org/credit-derivatives/)

[Github market reference](https://github.com/timxiao1203?tab=repositories)


### Asian Basket Relative Performance Option 

The pay of a basket Asian relative performance option (RPO) is determined by the difference between the performance of a reference stock and that of a basket of stocks, where performance is defined as the ratio of (weighted) average of two sets of averaging dates. A model is presented for pricing basket Asian RPO using Monte Carlo simulation.  


References:

	
[More details](./asianRpo.md)



### Bet Option 

A bet option is a bet on a basket of stocks.  There are multiple reset periods before the maturity of the option.  At the end of each period, if all the stocks in the basket are above their respective strikes, the option will payout a rebate amount for this period at maturity.


References:

	
[More details](./bet.md)



### Digital Return Note

The structure of a Binary Return Note is similar to the one of a regular note, but the coupons are contingent on return rates on stocks. We developed and implemented a Monte Carlo (Quasi-Monte Carlo) pricing model for the Binary Return Note product.


References:

	
[More details](./binary.md)



### Bond Futures Option 

For bond futures options, the futures price is taken directly from the market instead of being calculated from the bond futures calculator.


References:

	
[More details](./bondOption.md)



### Bond Option

We present a pricing model for bond options. Assuming that the bond price at the maturity of the option is lognormal, the model adopts the Black’s analytical closed-form solution. In market, both the underlying spot price of bond and the strike price are clean prices (quoted prices), while dirty prices are used in the price dynamic and the closed-form solution.


References:

	
[More details](./bondOp.md)



### Callable Asian Option 

Asian options allow their underwriters to call the options back from investors at a specified time and with a specified amount prior to option maturities.  A hybrid of Monte Carlo simulation and the closed form solution is employed in pricing.


References:

	
[More details](./callableAsian.md)



### Credit Default Swap 

Each of these maturity dates has to be identical to one of the payment dates in the target default swap; otherwise, those that cannot match any payment date in the target default swap will be changed to the closest payment dates.  If the target default swap is forward starting or finishes before the last maturity date in the term structure file, we will extend the quarterly payment dates of the target swap to the value date or to the last maturity date in the term structure, and use extended payment dates of the target swap for the calibration purpose.  As such, calibration is dependent on the payment dates of the target swap.


References:

	
[More details](./cdsModel.md)



### Floating Rate Convertible Bond 

Floating rate convertible bond pays floating rate coupons, which differentiate itself from the fixed rate convertible bond. The coupon rates are reset periodically based on market reference rates such as LIBOR plus or minus a spread. Similar to other convertible bond types, call and put features may be applied.   


References:

	
[More details](./floatingConvertible.md)



### Refix Convertible Bond 

A convertible bond is a bond with convertible options to the investor such that debt can be converted to the underlying stock in a future date if the stock price performs well. When stock price rises high, the bondholder can ride on the high stock prices and exercise the convertible option. When stock price deteriorates, the bondholder can still receive stable coupon payment if no default occurs.  


References:

	
[More details](./refixConvertible.md)



### Non Quanto Convertible Bond 

In a non-quanto convertible bonds, the spot stock price in foreign currency is converted into an amount in domestic currency using the spot exchange rate.  This amount is then adjusted by the current value of predicted future discrete dividends, measured in domestic currency.  The domestic risk-free interest rate is employed as the drift rate for the translated stock.


References:

	
[More details](./nonQuantoConvertible.md)



### Soft Call Convertible Bond 

The convertible bond issuer can call the bond back at a given call amount and at a specified time period only when the underlying stock price goes beyond a pre-specified barrier.  If the barrier is zero, this call becomes a hard call (unconditional call).  On the other end, if the barrier is considerably high, it is as if there is no call at all.  We use a smoothing technique when dealing with convertible bond with soft call under the semi-continuous tree method.  Its effectiveness and limitation have been investigated.


References:

	
[More details](./softConvertible.md)



### Correlation Swap 

We developed a conventional mark-to-market/pricing model for a new product Correlation Swap. The payoff of the correlation swap at maturity is the difference between the realized correlation (of a basket of stock indices) and the strike. The realized correlation has two main components: historical correlation part and future realized correlation part.


References:

	
[More details](./correlationSwap.md)



### Generic FX Option

We test the model in two cases: European and Asian FX options. The attribute terminology is borrowed from equity options, but the mapping is obvious: in particular the dividend file acts as foreign zero interest rate file. The cases studied can be obtained by commenting and uncommenting out the corresponding attributes. 


References:

	
[More details](./genericFxOption.md)



### Decreasing Basket Asian Option 

Decreasing-Basket-Asian option, also called Himalayas option is an option that records the highest return at the end of each reset period among the stocks left in the basket for calculation of the payoff.  The stock with either the highest return or the lowest return, based on the specification, will then be eliminated from the basket for the rest reset periods.


References:

	
[More details](./decreasingAsian.md)



### Dividend Enhancement Common Stock 

A dividend enhancement common stock (or DECS) instrument is a portfolio of stock options and a fixed coupon stream. The DECS is developed to price a corporate financing structure with the option that the debt principal can be converted to the underlying common stock at maturity date. 


References:

	
[More details](./decs.md)



### Eurodollar Futures Option 

Option on Eurodollar futures is a European type of call/put option on the Eurodollar futures price or put/call option on the 3-month LIBOR forward interest rate referred by the futures contract. Standard Black’s model can be used to price the options on LIBOR forward interest rate. The price of the option on Eurodollar futures is related to the price of options on LIBOR forward with a ratio adjustment.    


References:

	
[More details](./futureOption.md)



### Fixed Forward Option 

The fixed forward call/put contracts are options on forward equity contracts. The option buyer has the right, but not obligation to enter into an equity forward contract, which starts on the expiration date of the option and matures on a later date further into the future.  The fixed forward call/put contracts can be priced using standard option pricing methodologies such as closed form Black-Scholes model or lattice tree model. 


References:

	
[More details](./fixedForward.md)



### Futures Fair Value 

The proposal for the new methodology to calculate the fair value of equity-index futures was reviewed. The proposed method attempts to improve traditional method by taking into consideration the dynamic rebulanching of the position (tail hedge) over the life of futures contract. We find the model adequate for the purposes of the fair value adjustment. We present our conclusions below. 


References:

	
[More details](./fair.md)



### Equity Forward with Dividend Reinvestment

We developed a pricing model to calculate unwinding values of equity forward with dividend reinvestment.


References:

	
[More details](./DividendReinvestment.md)



### Swap Curve 

The swap curve construction is an algorithm based on the assumption that the term forward rate curve must exhibit minimal quadratic variation. The Curve Construction Algorithm contains the following main features


References:

	
[More details](./swapCurve.md)




### Variance Swap 

A variance swap is a forward contract on annualized variance, the square of the realized volatility.  The holder of a variance swap at expiration receives a notional amount of dollar for every point by which the stock’s realized variance has exceeded the variance delivery price.  Valuation of the swap involves decomposition of the contract into two periods, one that has become historical, and the other with stock prices still unknown.  


References:

	
[More details](./variance.md)




### CDS Index Option  

The CDS index contracts have typical expiries from three to nine months, and are typically physically settled. If the portfolio spread is wider than the strike level on the expiry date, the holder of the payer swaption (portfolio swap call) will exercise the option and lock in the portfolio protection at more favourable levels. If the portfolio spread is smaller than the strike, the holder of the receiver swaption (portfolio swap put) will benefit from exercising the option and realizing the mark-to-market gain. 


References:

	
[More details](./cdsIndex.md)



### Cross Currency Option  

A non-quanto cross currency option is a currency translated option of the type foreign equity option struck in domestic currency, which is a call or put on a foreign asset with a strike price set in domestic currency and payoff measured in domestic currency.

References:

	
[More details](./xccyOption.md)



### Zero Curve 

We present a Zero Curve Bootstrap Algorithm to allow more cash and futures contracts as underlying instruments for curve generation. 


References:

	
[More details](./zeroCurve.md)



### Reverse Floor Option 

A reverse floor option has multiple reset periods before the maturity of the option.  At the end of each reset period, a return of the underlying is recorded.  The payoff of the option at maturity is related to the accumulated absolute values of those negative returns. We present a pricing model for reverse floor options using Monte Carlo simulation.


References:

	
[More details](./reverse.md)



### Strip Rho 

Rho is defined as change of the instrument value with respect to 10bps parallel shift of the entire continuous compounding zero curve.  Users can input the rate shock amount when requesting rho calculation from the model.  The default amount is still 10bps.


References:

	
[More details](./strip.md)



### Credit Default Swap Option 

If we decide to go long a CDS call today, then this means that we need to pay a premium today for the right and not the obligation to buy a specified forward starting CDS (that is to enter in a specified CDS contract whose effective date is the call expiry date or later as protection buyers), with contract fee set to the call strike, at the call expiry date. 


References:

	
[More details](./cdso.md)



### Cross Currency Swaption 

A Cross Currency European Swaption gives the holder the option to enter into a swap to exchange cash flows in two different currencies. The domestic and foreign swap leg cash flows can be fixed or floating.


References:

	
[More details](./xccySwaption.md)




### Zero Coupon Bermudan 

A Zero Coupon Bermudan Swaption is a Bermudan Swaption to enter into a Zero Coupon Swap. It can be characterized as a swap where the cashflows are accrued and exchanged at the maturity of the swap. The Floating Leg cash flows are accrued at the realised floating rates and the Fixed Leg cash flows are accrued at the specified vector of fixed rates. 


References:

	
[More details](./couponBermudan.md)

