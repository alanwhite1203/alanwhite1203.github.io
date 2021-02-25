## FX Futures
 
A currency future, also known as an FX future , is a future contract to exchange one currency for another at a specified date in the future at an exchange rate that is fixed on the purchase date. By using a currency future contract, the parties are able to effectively lock-in the exchange rate for a future transaction. Speculation and hedging in currencies can be achieved primarily through future contracts. 
A currency future or an FX future is a future contract between two parties to exchange one currency for another at a fixed exchange rate on a fixed future date. Currency futures are one of the main methods used to hedge against exchange rate volatility, as they avoid the impact of currency fluctuation over the period covered by the contract. 
Because currency futures contracts are marked-to-market daily, investors can exit their obligation to buy or sell the currency prior to the contract's delivery date. Future market participants and speculators usually close out their positions before the date of settlement, so most contracts do not tend to last until the date of delivery. Currency futures contracts are legally binding and counterparties that are still holding the contracts on the expiration date must trade the currency pair at a specified price on the specified delivery date.

Investors use futures contracts to hedge against foreign exchange risk. If an investor will receive a cashflow denominated in a foreign currency on some future date, that investor can lock in the current exchange rate by entering into an offsetting currency futures position that expires on the date of the cashflow. Currency futures can also be used to speculate and, by incurring a risk, attempt to profit from rising or falling exchange rates.

The currency future contracts are usually used by exporters and importers to hedge their foreign currency payments from exchange rate fluctuations. By using FX future contracts, investors can protect costs on products and services purchased abroad or protect profit margins on products and services sold abroad lock-in exchange rates as much as a year in advance.
Future contracts are traded in an exchange and thus have no credit risk. By locking-in the exchange rates at which the currency will be bought, the party forfeits the opportunity of profiting from a favorable exchange rate movement. Additionally, unfavorable exchange rate movements may take away further opportunity of the party for profit. This presentation gives an overview of currency futures and valuation model. 

	Currency Future or FX Future Introduction
	A currency future or an FX future is a future contract between two parties to exchange one currency for another at a fixed exchange rate on a fixed future date. 
	Currency futures are traded via exchanges.
	Currency futures are based upon the exchange rate of a currency pair, and are settled in cash in the underlying currency.
	Because currency futures contracts are marked-to-market daily, investors can exit their obligation to buy or sell the currency prior to the contract's delivery date. 
	Future market participants and speculators usually close out their positions before the date of settlement, so most contracts do not tend to last until the date of delivery.
	Currency futures contracts are legally binding and counterparties that are still holding the contracts on the expiration date must trade the currency pair at a specified price on the specified delivery date.
	Currency futures are one of the main methods used to hedge against exchange rate volatility, as they avoid the impact of currency fluctuation over the period covered by the contract.


	The Use of Currency Forward, Future and Swap
	Investors use futures contracts to hedge against foreign exchange risk. 
	If an investor will receive a cashflow denominated in a foreign currency on some future date, that investor can lock in the current exchange rate by entering into an offsetting currency futures position that expires on the date of the cashflow.
	Currency futures can also be used to speculate and, by incurring a risk, attempt to profit from rising or falling exchange rates.
	The currency future contracts are usually used by exporters and importers to hedge their foreign currency payments from exchange rate fluctuations.
	By using FX future contracts, investors can protect costs on products and services purchased abroad or protect profit margins on products and services sold abroad lock-in exchange rates as much as a year in advance.
	Future contracts are traded in an exchange and thus have no credit risk.
	By locking-in the exchange rates at which the currency will be bought, the party forfeits the opportunity of profiting from a favorable exchange rate movement. Additionally, unfavorable exchange rate movements may take away further opportunity of the party for profit

	Forex Market Convention
	One of the biggest sources of confusion for those new to the FX market is the market convention. We need to make clear the meaning of the following terms in the forex market first.

	FX quotation: the quotation EUR/USD 1.25 means that one Euro is exchanged for 1.25 USD. Here EUR (nominator) is the base or primary currency and USD (denominator) is the quote currency. One can convert any amount of base currency to quote currency by
QuoteCurrencyAmount = FxRate * BaseCurrencyAmount

	Spot Days: The spot date or value date is the day the two parties actually exchange the two currencies. In other words, a currency pair requires a specification of the number of days between the quotation date (trade date) and the Spot Date on which the exchange is to take place at that quote. Spot days can be different for each currency pair, although typically it is two business days.

	Holidays: Each currency pair has a set of holidays associated with it. The holidays of a currency pair is the union of the holidays of the two currencies.


	Forward FX Rate
Given spot rate X_s , spot date T_s and forward date T, the FX forward rate can be represented as


{■(X_f=X_s  (D_b (T_s,T))/(D_q (T_s,T))                 if  T≥T_s@X_f=X_s  (D_q (T,T_s))/(D_b (T,T_s))                 if  T<T_s )┤
where
	X_s  	the spot FX rate quoted as base/quote
	t 	the valuation date
	T_s 	the spot date (several days after the valuation date)
	T 	the forward date
	D_b (T_s,T) 	the discount factor of base currency from spot date to forward date
	D_q (T_s,T) 	the discount factor of quote currency from spot date to forward date


	Valuation

	Currency futures prices are usually quoted by exchanges.
	A pricing model is mainly used to calculate risk for a future contract, although it may produce both price and risk.

The present value of an FX forward contract is given by

PV(t)=N_b D_b (t,T) X_0-N_q D_q (t,T)+C
where
	t 	the valuation date
	T 	the payment date
	X_s 	the spot FX rate quoted base/quote
	D_b (t,T) 	the discount factor of base currency from valuation date to forward date
	D_q (t,T) 	the discount factor of quote currency from valuation date to forward date
	N_b 	the notional principal amount for base currency
	N_q 	the notional principal amount for quote currency
C 	a constant used to match the market price.


A Real World Example

Buy Sell	Buy
Base Currency	USD
Base Notional	2212500
Underlying Currency	JPY
Underlying Notional	12500000
Instrument	CME JPYUSD
Future Maturity Label	MAR 17
Number of Contracts	20
Spot Quotation Denominator	JPY
Spot Quotation Numerator	USD
Price	0.885
Trade Date	2/17/2017
Maturity Date	3/13/2017
Last Cash Flow Date	3/14/2017
Settlement Date	3/15/2017


References:

 
[More details](./FxFuture-21.pdf)
  
[FlipHtml5 fx futures](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamUzM5UDN5ITPkl0av9mY)
  
[Zenodo fx futures](https://zenodo.org/record/3988546/files/FxFuture-21.pdf)
  
[Pubpub fx futures](https://fixedincome.pubpub.org/pub/olni7vl6/download/pdf)
  
[Github fx futures](https://github.com/alanwhite1203/fxFuture/raw/main/FxFuture-21.pdf)
  
[Gitlab fx futures](https://gitlab.com/cmrm11/fxfuture/-/raw/master/FxFuture-21.pdf)
  
[Bitbucket fx futures](https://bitbucket.org/cmrm11/fxfuture/downloads/FxFuture-21.pdf)
  
[OSF futures](https://osf.io/rqd6v/download)

[Pub futures](https://fixedincome.pubpub.org/pub/olni7vl6/release/1)

[Pub futures pdf](https://assets.pubpub.org/w72dki68/51597087717478.pdf)

[Github futures](https://github.com/alanwhite1203/fxFuture/raw/main/FxFuture-21.pdf)
