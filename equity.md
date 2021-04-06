## Equity Derivative Products

### Equity American Option

An American option give an investor the right but not the obligation to buy a call or sell a put at a set strike price at any time prior to the contract’s expiry date. 
Since investors have the freedom to exercise their American options at any point during the life of the contract, they are more valuable than European options, 
which can only be exercised at maturity.  

An American option give an investor the right but not the obligation to buy a call or sell a put at a set strike price at any time prior to the contract’s expiry date. 
American options provide investors a way to hedge risk or speculate.  In general, American options do not have a closed-form solution. This presentation provides a 
practical guide for pricing an American equity option. 

[Equity American Option](EqAmerican.md)

[Reference Pdf](EqAmerican-1.pdf)


### Equity Asian Option 

An Asian option or average option is a special type of option contract  where the payoff depends on the average price of the underlying asset over a certain period of 
time. The payoff is different from the case of a European option or American option, where the payoff of the option contract depends on the price of the underlying 
stock at exercise date. 

Asian options allow the buyer to purchase or sell the underlying asset at the average price instead of the spot price. Asian options are commonly seen options over 
the OTC markets. Average price options are less expensive than regular options and are arguably more appropriate than regular options for meeting some of the needs 
of corporate treasurers. Average can be calculated in a number of ways (daily, weekly, monthly, etc.). This presentation provides an overview of Asian equity option 
product and valuation. 

[Equity Asian Option](EqAsian.md)
 
 
 
### Equity Basket Option
 
A Basket Option is an option whose payoff depends on the value of a portfolio or basket of assets. The assets in an equity basket option could be equity indices or individual equities. A basket option can be used to hedge the risk exposure to or speculate the market move on the underlying stock basket. 

A basket option can be used to hedge the risk exposure to or speculate the market move on the underlying stock basket. Because it involves just one transaction, a basket option often costs less than multiple single options. The most important feature of a basket option is its ability to efficiently hedge risk on multiple assets at the same time. Rather than hedging each individual asset, the investor can manage risk for the basket, or portfolio, in one transaction. The benefits of a single transaction can be great, especially when avoiding the costs associated with hedging each and every component of the basket or portfolio.

[Equity Basket Option](EqBasket.md)

  
  
### Convertible Bond
  
Convertible bonds can be thought of as normal corporate bonds with embedded options, which enable the holder to exchange the bond asset for the issuer's stock. Having properties of both stocks and bonds, convertibles can be an attractive choice for investors and have tended to have lower risk. 

A convertible bond has an embedded call option that gives bondholders the right to convert their bonds into equity at a given time for a predetermined number of shares in the issuing company. Whereas a reverse convertible bond has an embedded put option that gives the issuer the right to convert the bond's principal into shares of equity at a set date. 

[Convertible Bond](EqConvertible.md)

[Pdf reference](./EqConvertible-4.pdf)
  
  
   
### Equity Futures
   
An Equity Forward contract is an agreement between two counterparties to buy a specific number of equity stocks, stock index or basket at a given price (called strike price) at a given date. For any forward contract no cash changes hands until the maturity of the contract. Equity forward contracts are cash settled in most cases. At maturity, the two counterparties exchange a cashflow equivalent to the difference between the stock closing price and the strike price. Equity forward contract is traded over the counter (OTC) instead of exchange market. 

Differently from Equity Forward, an Equity Futures contract traded over the organized exchange. In this contract parties commit to buy or sell a specified amount of an individual equity or a basket of equities or an equity index at an agreed contract price on a specified date. Generally there are two types of Equity Futures: Index Future and Stock Future. Stock markets Index Futures are futures contracts used to replicate the performance of an underlying stock market index. They can be used for hedging against an existing equity position, or speculating on future movements of the index. Indices for futures include well-established indices such as S&P 500, FTSE 100, DAX, CAC 40 and other G12 country indices. Indices for OTC products are broadly similar, but offer more flexibility.

[Equity Futures](EqFuture.md)
 
[Reference pdf](./EqFuture-5.pdf)
   
  
   
### Equity Option
   
Equity options, which are the most common type of equity derivatives, give an investor the right but not the obligation to buy a call or sell a put at a set strike price prior to the contract’s expiry date. Equity options are derivatives that means their value is derived from the value of an underlying equity. Investors and traders can use equity options to take a long or short position in a stock without actually buying or shorting the stock. This is advantageous because taking a position with options allows the investor/trader more leverage in that the amount of capital needed is much less than a similar outright long or short position on margin. Investors/traders can therefore profit more from a price movement in the underlying stock.

Equity options or stock options provide investors a way to hedge risk or speculate.  Also option trading can limit an investor’s risk and leverage investing potential. Option investors have a number of strategies they can utilize, depending on risk tolerance and expected return. 

[Equity Option](EqOption.md)
   
[Reference pdf](./EqOption-6.pdf) 
   
   
   
### Equity Swap
   
An equity swap is an OTC contract between two parties to exchange a set of cash flows in the future. Normally one party pays the return based on capital gains and dividends realized on an equity security and the other party pays the return based on a floating interest rate plus a spread. 

An equity swap can be used to transfer both the credit risk and the market risk of an underlying asset. Equity swaps can be also used to avoid transaction costs (including Tax), to avoid locally based dividend taxes, limitations on leverage (notably the US margin regime) or to get around rules governing the particular type of investment that an institution can hold. Equity swaps can make investment barriers vanish and help an investor create leverage. 
   
[Equity Swap](./EqSwap.md)
   

   
### Warrant
   
An equity warrant is an option on the equity of a firm issued by the same firm, which gives the holder the right to purchase shares at a fixed price from the firm at a future date. When a warrant is exercised, the firm typically issues new shares at the exercise price to fill the order. The resulting increase in shares outstanding dilutes the share value. 

An equity warrant gives the holder the right to purchase shares at a fixed price from the firm. It is an option on the common stock of a firm issued by the same firm. Warrants are in many ways similar to call options, but a few key differences distinguish them. 

[Warrant](./EqWarrant.md)   

[Reference pdf](./EqWarrant-8.pdf)  


### Variance Swap

A variance swap is an instrument which allows investors to trade future realized (historical) volatility against current implied volatility.

The market value of a variance swap is based on the variance determined from
a combination of realized (historical) volatility and unrealized volatility obtained from broker's quote. 

[Variance Swap](./EqVariance.md)   


### Lookback Option

A lookback option gives the option holder the right but not the obligation to buy the underlying asset at the lowest price. It pays a single call-option-style payoff based on the performance of the underlying asset’s final price relative to its initial price, where both the initial and final prices are computed using a lookback formula.

The initial price is taken as the highest price observed over a set of Initial Lookback Dates. The final price is taken as the maximum of the running cumulative average, observed over a set of Payoff Observation Dates.

[Lookback Option](./EqLookback.md)   

 
### Barrier Option

Barrier options are set up conditionally, so that within the life of the option, a barrier may or may not be reached. The barrier option is dependent on an “extreme” price, either high or low, attained by the underlying. If a barrier is reached, or touched, the constraints are triggered.

The two types of contracts, knock-in barrier options and knock-out barrier options, each respond differently when the barrier is "triggered". If a knock-out option's underlying touches the barrier, the option is eliminated and the holder receives a rebate. Conversely, a knock-in option touches the barrier to activate the option. If the knock-in option never reaches the barrier, the holder will receive a rebate.

[Barrier Option](./EqBarrier.md) 


### Cliquet Option

A cliquet option, also called ratchet option, consists of a series of forward start options, each struck at the money on the date it becomes active. Typically, each option begins on the date corresponding to the expiry of the previous option. The cliquet is a series of at-the-money options, with periodic settlement, resetting the strike value at the then current price level, at which time, the option locks in the difference between the old and new strike and pays that out as the profit. The profit can be accumulated until final maturity, or paid out at each reset date.

Cliquet options are widely traded in many retail-structured products. They consist of financial derivatives which provide a guaranteed minimum return in exchange for a capping of the maximal return over the life of the contract. A cliquet option is equivalent to a series of forward-starting at-the-money options, which may be globally and locally floored and capped. 

[Cliquet Option](./EqCliquet.md) 


### Binary Option

A binary option is an option with a predetermined payoff, triggered only if the underlying price meets the strike price. These are also commonly referred to as “all or nothing” or “digital options”. Binary call pays a fixed amount if the underlying price ends up above the strike price, while binary put pays off a fixed amount if the underlying price is below the strike price at option maturity.

The payoff of a digital option or binary option is either some fixed amount of some asset or nothing at all. The two main types of binary options are the cash-or-nothing binary option and the asset-or-nothing binary option. The cash-or-nothing binary option pays some fixed amount of cash if the option expires in-the-money while the asset-or-nothing pays the value of the underlying security.

[Binary Option](./EqBinary.md)


### Quanto Option

A quanto option is an option whose payout is made in a currency other than that of the underlying security, based on a fixed exchange rate. The term “quanto” is abbreviation for “quantity adjusted” that refers to the feature where the payoff of an option is determined by the financial price of index in one currency but the actual payout if realized in another currency.

It is a common trend that domestic investors allocate their assets in foreign stock markets. The major reason behind this investment trend is that the regulation liberalization spreads throughout in the global security markets. Domestic investors who put their money into foreign stock markets will encounter both of the foreign stock price risk and foreign exchange rate risk. 

[Quanto Option](./EqQuanto.md)


### Callable Exotics

A callable note allows the issuer to exercise a call option on the note on a specified date or set of dates prior to maturity.

Callable note or callable exotics are among the most challenging derivatives to price. These products are loosely defined by the provision that the holder or issuer has the right to call the product or exercise into various underlying instruments after a lock-out period expires.

[Callable Exotics](./EqCallable.md)


### Spread Option

A spread option is an option written on the difference of two underling assets, whose values at time t we denote by S1(t) and S2(t). We consider only options of the European type for which the buyer has the right to be paid, at the maturity date T, the difference S2(T)−S1(T), known as the spread. To exercise the option, the buyer must pay at maturity a prespecified price K, known as the strike, or the exercise price of the option.

The use of spread options is widespread for speculation, basis risk mitigation, or even asset valuation. Spread options allow investors to simultaneously take positions in two are more assets and profit from their price difference over some spread.

[Spread Option](./EqSpread.md)


### Best Performer Option

A best performer option pays the option holder the best return at maturity among a given set of portfolios, where each portfolio may be defined by a set of weights on the same underlying basket or different baskets.

These are chooser options that return the best performing among several baskets of funds or indices that reflect growth, moderate and conservative investment styles. The returns could be based on average (Asian), single currency or quanto. The final payoff could be capped and floored.

[Best Performer Option](./EqPerform.md)


### Reverse Convertible Swap

A reverse convertible autocallable swap allows two parties exchange floating coupons with fixed coupons on certain future dates. On some coupon dates, the swap may be cancelled. Should the swap be cancelled on coupon date t, the coupons due on coupon date t will be paid and all further cash flows are terminated.

The decision to cancel the option is made based on the performance of an underlying asset, index, or basket of assets. The swap is called if its price at some observation date, relative to its initial price, exceeds the cancellation trigger level. The initial price is averaged over a short period after inception of the deal. This averaged price may be ‘reset’; that is, should the stock price on some ‘reset date’ be lower than the previously averaged price, the initial price is replaced by the price on the reset date.

[Reverse Convertible Swap](./EqReverse.md)


### Constant Proportion Portfolio Insurance 

A constant proportion portfolio insurance (CPPI) is a trading strategy where an initial investment is dynamically reallocated between a risky asset and risk-free bond such that a minimum payoff is guaranteed at maturity. The risky asset could be from equities, funds, or commodities.

In upside markets, the strategy allocates more towards the risky asset whereas in downside, the strategy allocates more towards the safe asset. The capital protection feature makes CPPI one of the most popular derivative products. 

[Constant Proportion Portfolio Insurance](./EqCppi.md)


### Accelerated Return Note 

An Accelerated Return Note (ARN) is a structured instrument that offers a potentially higher return linked to the performance of a reference entity that could be an equity, an index, or a basket of assets. The payoff depends on the performance of the underlying assets. Usually, it is capped but not floored, that means it does not offer any downside protection.

The note normally pays the holder an increased participation rate on its underlying asset were its returns at maturity to be positive, while exposing the note holder to a lower participation rate should the underlying asset’s return at maturity be negative.

[Accelerated Return Note](./EqArn.md)


### Accelerated Share Repurchase 

An accelerated share repurchase (ASR) agreement is a contract or an investment strategy used by a publicly traded company to buy back shares of stocks expeditiously from the market. In these agreements, firms are able to repurchase a significant number of their shares upfront. The intermediary must then repurchase the shares over a given time window that is equivalent to enter into a forward contract. 

In a share buyback program, a firm normally sets out the amount of shares it wishes to buy back, and over a specified time window the shares are bought back and the firm agrees to pay the average volume weighted average price (VWAP) over this fixed time period. 


[Accelerated Share Repurchase](./EqAsr.md)


### Equity-Linked Bonus Coupon Note 

A bonus coupon note, also referred to as coupon growth note or bonus enhanced note or basket coupon note, is an equity-linked note that provides guaranteed coupons over the life of the note with potential for a bonus coupon based on the underlying asset trading above a specified barrier level. 

The note pays a series of coupons based on the weighted performance of all assets in the basket on each Coupon Determination Date. The coupons are usually capped and floored.


[Bonus Coupon Note](./EqCoupon.md)



### Yield Note

A yield note is a principal-protected structured note that pays periodic coupons that are linked to the performance of a basket of equities. A callable yield note gives the issuer the right to recall the note on specific observation dates. Once recalled, the cancellation coupon is paid, the notional is returned, and the deal is cancelled.

The auto-call feature limits the total return paid to the buyer by automatically cancelling the note once the return of the worst performing asset is above the trigger (threshold). If the cancellation event is not triggered, the payoff on each payment date is equivalent to a spread-adjusted reference rate.

[Yield Note](./EqYield.md)


### Rainbow Option

A rainbow option is an option on a basket that pays a non-equally weighted sum of returns over all assets in the basket according to their performance, where individual asset returns are computed as the percentage growth from initial levels to final levels that may be averages over multiple dates.

Rainbow options are multi-asset options that have a payoff depending on the assets by their performance at maturity. When the rainbow only pays the best (worst) performing asset of the basket, it is also called the best (worst) of performing option.

[Rainbow Option](./EqRainbow.md)


### Himalaya Option

Himalaya option is a popular version of maintain range options that basically pays the sum of the best performers of a basket of assets over a particular time horizon. Maintain range options are exotic options that have multiple underlying assets, path-dependency, and best (worst) of payoff structure. They include Everest options, Atlas options, Altiplano options, and Himalaya options. 

A Himalaya option is an option on the sum of the returns of the best (worst) performing assets from a basket on predefined observation dates. It has a set of observation dates are defined. The number of observation dates are equal to the number of underlying assets. The unique feature of Himalaya option is the withdrawal of the best performer asset from the basket at each pre-defined observation date, until only one stock remains.

[Himalaya Option](./EqHimalaya.md)



   