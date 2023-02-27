## Fixed Income Instruments

### Product List

[Fixed income product list](https://derivatives.hcommons.org/fixed-income-instruments/)



### Instrument List

[Fixed income instrument list](https://derivatives.hcommons.org/fixed-income-derivatives/)



### Variable Rate Swap

Variable rate swap is a special type of interest rate swap in which one leg of the swap corresponds to fixed rate payments while the other involves fixed rate payments for an initial period of time and a floating rate for the rest. The floating rate on that portion is defined as a minimum of two index rates.

We treat the two index rates as assets whose values are lognormally distributed random variable. Their pricing procedure uses discount factors retrieved from the EURIBOR curve.
	
[Archive variable swap](https://ia601404.us.archive.org/30/items/variableSwap/variableSwap.pdf)

[Science variable swap](https://science-media.org/presentation/613)


### CMS Spread Option 

A constant maturity swap (CMS) spread option makes payments based on a bounded spread between two index rates (e.g., a GBP CMS rate and a EURO CMS rate).  The GBP CMS rate is calculated from a 15 year swap with semi-annual, upfront payments, while the EURO CMS rate is based on a 15 year swap with annual, upfront payments. 

From the above the correlation, under foreign T-forward measure, between the Brownian motions respectively driving the foreign bond yield and GBP swap rate processes constrains the correlation between the Brownian motions driving the Euro bond yield and forward GBP CMS rate processes under domestic T-forward measure.  

[Archive cms spread](https://ia904704.us.archive.org/3/items/cmsSpreadOption/cmsSpreadOption.pdf)

[Science cms sprad](https://science-media.org/presentation/614)


### Early Start Swap 

An early start swap is a swap that has an American style option for the counterparty of starting the swap early, within a period of three month. Otherwise, the swaps are plain vanilla fixed-for-floating swaps.

The present value of the swap is then calculated as the sum of present values of corresponding cash flows. To simulate the swap value at a later date, the coupon bond is represented through its forward rate of return. 

[Archive early start](https://ia601500.us.archive.org/35/items/earlyStartSwap/earlyStartSwap.pdf)

[Science early start](https://science-media.org/presentation/615)


### Quanto Total Return LIBOR Swap 

A quanto total return Libor Swap is a swap where one leg is a regular floating leg paying LIBOR less a constant spread and the other leg makes a single payment at the swap’s maturity equal to a leveraged non-negative return on USD-for-EURO exchange rate paid in CAD. The main focus of the valuation model is the quantoed total return on the FX rate.

There must exist a measure under which all the tradeables on the Canadian market, discounted by the Canadian saving account, including CU and CE, are martingales. A standard Brownian motion under this measure w* is coupled with the original Brownian motion:

[Archive quanto trs](https://ia904703.us.archive.org/32/items/quantoTrs/quantoTrs.pdf)

[Science quanto trs](https://science-media.org/presentation/616)


### Daily Digital LIBOR Swap

A daily digital LIBOR swap is an interest rate swap whose reference interest rate is three-month USD Libor BBA. For each accrual period in the swap, one party receives the reference rate, and pays the reference rate plus a positive spread, but weighted by the ratio of the number of calendar days in the period that the reference rate sets below an upper level to the total number of calendar days in the period.

Consider a particular day in the accrual period above, and let   denote the time (expressed in years) corresponding to this day.  Furthermore let   denote the reference Libor rate at time  .   

[Archive daily digital](https://ia601405.us.archive.org/35/items/dailyDigital/dailyDigital.pdf)

[Science daily digital](https://science-media.org/presentation/617)


### Ratchet Swap 

The coupon rate is stated as an annualized rate or real rate based on market conventions. Adjustment is made for long/short first/last coupon periods. When a coupon date falls on non-business day, payment may be made next business day with no amount adjustment

The valuation methodology is based on the Monte Carlo spot LIBOR rate model. The model generates spot rates which log-normally distributed at each reset date. These spot rates are derived from corresponding forward rates whose stochastic behavior is constructed in an arbitrage-free manner. Outcomes for the spot rate are generated for each reset date. These rates are then applied to the ratchet-type payoff structure. The ratchet instrument is then valued by discounting and averaging these payoffs.

[Archive ratchet swap](https://ia601506.us.archive.org/33/items/ratchetSwap/ratchetSwap.pdf)

[Science ratchet swap](https://science-media.org/presentation/618)


### LIBOR Rate Model

LIBOR Rate Model is used for pricing Libor-rate based derivative securities. The model is applied, primarily, to value instruments that settle at a Libor-rate reset point.  In order to value instruments that settle at points intermediate to Libor resets, we calculate the numeraire value at the settlement time by interpolating the numeraire at bracketing Libor reset points. 

Libor rate model is very useful to price callable exotics. Many derivatives have callable features. Callable exotics are among the most challenging derivatives to price. These products are loosely defined by the provision that gives the holder or issuer the right to call the product after a lock-out period

[Archive libor rate](https://ia601500.us.archive.org/4/items/liborSwapModel/liborSwapModel.pdf)

[Science libor rate](https://science-media.org/presentation/619)


### Amortizing Floor Option

An amortizing floor option consists of 12 floorlets, or put options, on the arithmetic average of the daily 12-month Pibor rate fixings over respective windows of approximately 30 calendar days.  Furthermore the notional amount corresponding to each floorlet is specified by an amortization schedule.

We note that, mathematically, the Pibor rates above cannot simultaneously be martingales under the common  -forward probability measure; moreover, in order to simultaneously express the Pibor rates above under this same measure, the SDE above requires a drift correction term.

[Archive amortizing floor](https://ia601505.us.archive.org/7/items/amortizing-floor-option/AmortizingFloorOption.pdf)

[Science amortizing floor](https://science-media.org/presentation/620)


### Arbitrary Cash-Flow

An Arbitrary Cash-Flow (ACF) security interface values future known cash-flows. These cash-flows must be in a single (potentially foreign) currency. The present value of these cash-flows is determined by prevailing market interest and foreign exchange rates.

We note that, in the above, we equivalently apply log-linear interpolation of discount factors.
In the case, when we considered an Imagine bond par yield curve input, we performed the following calculations:

[Archive arbitrary cash-flows](https://ia601408.us.archive.org/7/items/arbitrary-cash-flow/ArbitraryCashFlow.pdf)

[Science arbitrary cash-flows](https://science-media.org/presentation/622)


### Currency Bermudan Swaption 

The pricing method is based on Jamshidian’s Libor rate model (i.e., where Libor rates are modeled simultaneously under the spot Libor measure).  Furthermore, we value a Bermudan swaption based on the Monte Carlo technique presented by Longstaff and Schwartz towards American style pricing.

We price a Bermudan style swaption using a Monte Carlo technique, which is based on the approach proposed by Longstaff and Schwartz towards American style pricing using simulation.  In particular, at every exercise time, we must solve a linear least squares problem, and then decide whether to exercise the option.

[Archive Bermudan swaption](https://ia601404.us.archive.org/17/items/bermudan-swaption/BermudanSwaption.pdf)

[Science Bermudan swaption](https://science-media.org/presentation/621)


### Partial Payoff Swap 

Partial payoff swap pays periodically, the payoff from a particular European style put option on the spread between respective ten and two-year CMS rates. Moreover, this payoff is algebraically equivalent to the sum of the spread above and the payoff from a related European style put option.  

[Archive partial swap](https://ia904700.us.archive.org/27/items/partial-payoff-swap/PartialPayoffSwap.pdf)

[Science partial swap](https://science-media.org/presentation/623)





