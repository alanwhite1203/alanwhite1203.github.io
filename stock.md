## Stock Products

### Product List

[Stock product list](https://derivatives.hcommons.org/equity-derivatives/)



### Instrument List

[Stock instrument list](https://derivatives.hcommons.org/equity-instruments/)



### GIC Pooling 

Guaranteed investment certificate provides investors a guaranteed interest rate for a fixed amount time. Interest is accrued daily on GIC. Accrued interest will be reported annually

Payoff for equity GIC requires a dynamically created basket such that the weight factors incorporate a division by the spot levels on the issue date, which converts the payoff to one based on a basket of comparative returns (rather than basket returns). To automate feeds on a daily basis we will need to create new baskets on a daily basis.

[Archive GIC pooling](https://ia801400.us.archive.org/6/items/gic-pooling/GicPooling.pdf)

[Science GIC pooling](https://science-media.org/presentation/593)


### Quanto Himalayan Option 

Himalayan options are a form of European-style, path-dependent, exotic option on a basket of equity underliers, in which intermediate returns on selected equities enter the payoff, while the
equities are subsequently removed from the basket.

This definition is consistent with the one in the case of domestic equities, that is, in the absence of a quanto adjustment. In the quanto case, the effect of the change in the quanto adjustment resulting from a change in the volatility is ignored. 

[Archive Quanto Himalayan](https://ia601408.us.archive.org/0/items/quanto-himalaya/QuantoHimalaya.pdf)

[Science Quanto Himalayan](https://science-media.org/presentation/594)


### Quanto Local Volatility

We review a model for computing the price, in the domestic currency, of European standard call and put options on an underlying foreign equity (stock or index) with tenor of up to 7 years. The function implements a local volatility based pricing method.

The equity price process satisfies a risk-neutral stochastic differential equation (SDE) when where are no dividend payments. Let St denote the equity price at time t. We assume that the process satisfies a SDE of the form under the domestic risk-neutral probability measure:

[Archive Quanto vol](https://ia904700.us.archive.org/23/items/local-vol-quanto/LocalVolQuanto.pdf)

[Science Quanto vol](https://science-media.org/presentation/595)


### Forward Starting Option 

Forward start option is an option whose strike will be determined at some later date. Unlike a standard option, the strike price is not fully determined until an intermediate date before expiration. Cliquet option consists of a series of forward start options. 

In practice, option price or implied volatility surfaces are available at points on a relatively sparse grid of strike and tenor pairs. Using analytical expressions to determine the local volatility function then likely yields inaccurate results due to the numerical instability from calculating first, and especially, second derivatives.

[Archive forward starting](https://ia904709.us.archive.org/7/items/forward-starting-option/ForwardStartingOption.pdf)

[Science forward starting](https://science-media.org/presentation/596)


### Three Factor Model 

We construct respective trinomial trees to approximate the processes for each new random variable, but with each tree based on the same time slice partition of the CB tenor.  A new tree, which combines these respective trees, is then defined such that the set of nodes on a particular time slice of the combined tree equals the cross product of the set of nodes in each of the three respective trees at this time slice.  

[Archive three factor](https://ia804703.us.archive.org/1/items/threeFactorConvertible/threeFactorConvertible.pdf)

[Science three factor](https://science-media.org/presentation/597)


### Mutual Fund Securitization 

The General Account collects monthly administrative and redemption fees and, if required, a collateral infusion amount.  This money is used to pay monthly program fees, as well as amortized principal and accrued interest owed from issued Commercial Paper.  Any excess money is transferred to a Retention Account as future collateral.

Here monthly administration fees are set to a fixed percentage of the average of the respective current and previous month’s beginning mutual fund net asset values.  Program fees are similarly set to a fixed percentage of the current month’s beginning net asset value.  

[Archive MF sec](https://ia904705.us.archive.org/21/items/mutual-fund-securitization/MutualFundSecuritization.pdf)

[Science MF sec](https://science-media.org/presentation/598)


### Hull-White Convertible Bond 

We build respective trinomial trees for the approximate stock’s price and short-term interest rate processes above.  This construction is based on Hull and White’s single factor tree-building technique, but is generalized to accommodate non-uniformly spaced partitions of the interval to bond maturity.  The separate trinomial trees are then combined into a joint tree using Hull and White’s two-factor tree building procedure.  

Here the set of nodes at a particular time slice on the combined tree is given by the cross product of the nodes on each respective tree at this time slice.  From each node on the combined tree emanate nine children; the branching probabilities are given by the product of the corresponding probabilities on the respective trees, but shifted by a certain amount so to match the correlation between the random variables associated with the combined tree node.

[Archive HW convertible](https://ia904707.us.archive.org/6/items/hw-convertible/HwConvertible.pdf)

[Science HW convertible](https://science-media.org/presentation/599)


### Brownian Bridge 

In the context of stress testing this algorithm is used for efficient generation of specific scenarios subject to certain extreme and generally unlikely conditions. If paths were generated by a conventional Monte-Carlo method only a very small portion of all the paths would satisfy such conditions.

The Brownian Bridge algorithm belongs to the family of Monte Carlo or Quasi-Monte Carlo methods with reduced variance. It generates sample paths which all start at the same initial point and end, at the same moment of time, at the same final point. 

[Archive BB](https://ia601505.us.archive.org/8/items/brownian-bridge/BrownianBridge.pdf)

[Science BB](https://science-media.org/presentation/600)


### Asset Backed Senior Note 

The valuation makes the assumption that the future values of these parameters will be unchanged until the final payment date. Subsequently, the calculator performs a deterministic computation consisting of calculating the future cashflows in the waterfall and discounting them.

The following notation will be used throughout the text: the contents of the cell in row i of column A in the spreadsheet will be denoted by A(i), and similarly for other columns. Lower-case letters will be used for all other constants.

[Archive abs](https://ia601506.us.archive.org/32/items/abs-analytics/AbsAnalytics.pdf)

[Science abs](https://science-media.org/presentation/602)


### Exchangeable Convertible Bond 

A convertible bond issuer pays periodic coupons to the convertible bond holder. The bond holder can convert the bond into the underlying stock within the period(s) of time specified by the conversion schedule. The bond issuer can call the bond and the holder can put it according to the call and put provisions. 

The Exchangeable feature assumes that the convertible bond and the underlying stock are issued by different parties. There are two possible cases with respect to stock conversion:

[Archive exchangeable convertible](https://ia904704.us.archive.org/21/items/exchangeable-convertible/ExchangeableConvertible.pdf)

[Science exchangeable convertible](https://science-media.org/presentation/601)


### Hull White Volatility 

Hull White model is a short rate model that is used to price interest rate derivatives, such as Bermudan swaption and callable exotics 

We map implied Black's at the money (ATM) European swaption volatilities into corresponding Hull-White (HW) short rate volatilities.

[Archive HW vol](https://ia904705.us.archive.org/20/items/hw-vol/HwVol.pdf)

[Science HW vol](https://science-media.org/presentation/603)


### Bond Curve 

Government Bond Bootstrapping proceeds in two phases. The first phase uses short term instruments, which typically mature in one year or less. Consider, for example, a US government money market instrument with 

[Archive bond curve](https://ia601404.us.archive.org/25/items/bondBootstrapping/bondBootstrapping.pdf)

[Science bond curve](https://science-media.org/presentation/604)


### GIC

The payoff at maturity from a GIC can be shown equal to the invested principal plus these principal times the sum of the minimum guaranteed interest rate and the payoff from a European call option on the arithmetic average of a basket price at the 12 points above, where the basket price is given by a weighted sum of the index levels above.  

We consider the pricing of this call option.  We assume that each of the underlying stock and bond market indices in the basket follows geometric Brownian motion with drift under their respective risk neutral probability measures.  Each index process is then expressed under the Canadian risk neutral probability measure by means of a corresponding quanto adjustment.  

[Archive gic](https://ia601507.us.archive.org/23/items/gicPricing/gicPricing.pdf)

[Science gic](https://science-media.org/presentation/605)


### Extendable Swap 

We use analytical formulas for forward swap and swaption valuation: the swap price is calculated as the difference between a bond par and the bond’s price, and the swaption price is evaluated from the Black’s formula.

The model estimates the swap price as a risk-neutral expectation of the difference between the bond price whose yield-to-maturity is the swap rate and the bond’s par. The swap rate is considered a log-normally distributed random variable. 

[Archive extendable swap](https://ia601509.us.archive.org/6/items/extendableSwap/extendableSwap.pdf)

[Science extendable swap](https://science-media.org/presentation/606)





