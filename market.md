## Financial Markets


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


