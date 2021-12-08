## FX Swap Valuation
   
A foreign exchange swap or currency swap is a contract under which two parties agree to exchange two currencies at a set rate and then to re-exchange those currencies at an agreed upon rate at a fixed date in the future.  Therefore, an FX swap consists of two transactions:  a spot transaction and a forward transaction. 

An FX swap or currency swap agreement is a contract  in which both parties agree to exchange one currency for another currency at a spot FX rate. The agreement also stipulates to re-exchange the same amounts at a certain future date also at a forward FX rate. Many people confuse currency swaps with cross currency swaps. They are totally different. A cross currency swap is an interest rate swap in which two parties to exchange interest payments and principal on loans denominated in two different currencies. 

In a currency swap, one party simultaneously borrows one currency and lends another currency to a second party. The repayment obligation is used as collateral and the amount of repayment is fixed at the FX forward rate. FX swaps can be considered riskless collateralized borrowing/lending. The contract virtually allows you to utilize the funds you have in one currency to fund obligations denominated in a different currency, without incurring foreign exchange risk.

A currency swap is a simultaneous purchase and sale of identical amounts of one currency for another with two different value dates, normally spot to forward. Therefore, an FX swap consists of two transactions:  a spot transaction and a forward transaction. Effectively the FX swap is two exchange contracts packed in one: a spot foreign exchange transaction and a forward foreign exchange transaction.

A currency swap deal can be used if you have a currency, which you do not need before a certain time, but at the same time have a short-term need for another currency. Swap deals are used for managing currency risks, postponing the term of forward-deal and optimizing financing.

The most common use of FX Swaps is for institutions to fund their foreign exchange balances. FX swaps are also used by importers and exporters, as well as institutional investors who wish to hedge their positions. They are also used to speculate and, by incurring a risk, attempt to profit from rising or falling exchange rates.

Currency swaps are OTC trades and have credit risk. In the case that one of the parties is unable to fulfill its obligation, the other party will have to sign another contract with a third party, thus being exposed to market risk at that time. This presentation gives an overview of FX swaps and valuation model. 

	Currency Swap or FX Swap Introduction
	An FX swap agreement is a contract  in which both parties agree to exchange one currency for another currency at a spot FX rate. The agreement also stipulates to re-exchange the same amounts at a certain future date also at a swap FX rate.
	Many people confuse currency swaps with cross currency swaps. They are totally different. A cross currency swap is an interest rate swap in which two parties to exchange interest payments and principal on loans denominated in two different currencies..
	In a currency swap, one party simultaneously borrows one currency and lends another currency to a second party. The repayment obligation is used as collateral and the amount of repayment is fixed at the FX forward rate. 
	FX swaps can be considered riskless collateralized borrowing/lending. The contract virtually allows you to utilize the funds you have in one currency to fund obligations denominated in a different currency, without incurring foreign exchange risk. 
	An FX swap is a simultaneous purchase and sale of identical amounts of one currency for another with two different value dates, normally spot to forward. 
	Therefore, an FX swap consists of two transactions:  a spot transaction and a forward transaction.
	Effectively the FX swap is two exchange contracts packed in one: a spot foreign exchange transaction, and a forward foreign exchange transaction


	The Use of Currency Forward, Future and Swap
	A swap deal can be used if you have a currency, which you do not need before a certain time, but at the same time have a short-term need for another currency 

	Swap deals are used for managing currency risks, postponing the term of forward-deal and optimizing financing.

	The most common use of FX Swaps is for institutions to fund their foreign exchange balances. 

	FX swaps are also used by importers and exporters, as well as institutional investors who wish to hedge their positions. 

	They are also used to speculate and, by incurring a risk, attempt to profit from rising or falling exchange rates.
	Currency swaps are OTC trades and have credit risk. In the case that one of the parties is unable to fulfill its obligation, the other party will have to sign another contract with a third party, thus being exposed to market risk at that time.


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

An FX swap is a simultaneous purchase and sale of identical amounts of one currency for another with two different value dates, normally spot date and forward date. Therefore, an FX swap has two legs – a spot transaction and a forward transaction.

In the spot leg, a particular quantity of a currency is bought or sold versus another currency at an agreed upon rate on the spot date. In the forward leg, the same quantity of currency is then simultaneously sold or bought versus the other currency at a second agreed upon rate on the forward date.

From valuation perspective, an FX swap can be viewed as a combination of two forward contracts. In general, it has a long FX forward contract and a short one. Typically, one leg of the outstanding contract would have already expired. Therefore, in many situations, an FX swap is equivalent to an FX forward contract.


The present value of an FX forward contract is given by

PV(t)=N_b D_b (t,T) X_0-N_q D_q (t,T)
where
	t 	the valuation date
	T 	the payment date
	X_s 	the spot FX rate quoted base/quote
	D_b (t,T) 	the discount factor of base currency from valuation date to forward date
	D_q (t,T) 	the discount factor of quote currency from valuation date to forward date
	N_b 	the notional principal amount for base currency
	N_q 	the notional principal amount for quote currency



	A Real World Example

Delivery Type	Delivery
Leg One Currency	GBP
Leg One Notional	10043000
Leg Two Currency	USD
Leg Two Notional	12289368.03
Net Price	1.223675
Buy Sell	Buy
Base Currency	GBP
Underlying Currency	USD
Instrument	GBP/USD
Spot Quotation Denominator	GBP
Spot Quotation Numerator	USD
Trade Date	10/28/2016
Maturity Date	11/1/2017
Settlement Date	11/1/2017


References:
  
[More details](./FxSwap-23.pdf)
   
[FlipHtml5 fx swap](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamIzMwATN5ITPkl0av9mY)
   
[Zenodo fx swap](https://zenodo.org/record/3990518/files/FxSwap-23.pdf)
   
[archive fx swap](https://ia804500.us.archive.org/24/items/fx-swap-23/FxSwap-archive.pdf)
   
[Bitbucket fx swap](https://bitbucket.org/cmrm11/fxswap/downloads/FxSwap-23.pdf)
   
[OSF swap](https://osf.io/vuyzn/download)

[Pub swap](https://fixedincome.pubpub.org/pub/k0brdlqc/release/1)



   
   