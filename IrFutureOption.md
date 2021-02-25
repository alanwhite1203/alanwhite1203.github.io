## Future Option
   
An interest rate future option gives the holder the right but not the obligation to buy or sell an interest rate future at a specified price on a specified date. It is usually traded in an exchange. The buyer normally can exercise the option on any business day (American style) prior to expiration by giving notice to the exchange. Option sellers (writer) receive a fixed premium upfront and in return are obligated to buy or sell the underlying asset at a specified price.

Interest rate future options can be used to hedge against adverse changes in interest rates. In general futures markets tend to be more liquid than underlying cash markets. This presentation gives an overview of interest rate future option product and pricing model. 

	Keywords
Interest rate futures, interest rate future option, Eurodollar futures, hedge, valuation, exchange.

	Interest Rate Future Option Definition
	An interest rate future option gives the holder the right but not the obligation to buy or sell an interest rate future at a specified price on a specified date.
	Interest rate future options are usually traded in an exchange.
	It is used to hedge against adverse changes in interest rates.
	The buyer normally can exercise the option on any business day (American style) prior to expiration by giving notice to the exchange.
	Option sellers (writer) receive a fixed premium upfront and in return are obligated to buy or sell the underlying asset at a specified price.
	Option writers are exposed to unlimited liability.

	Interest Rate Future Definition
	An interest rate future is a contract between the buyer and seller to deliver an interest rate asset at a specified rate on a specified date.
	The future allows the buyer and seller to lock in the price of the interest rate asset at a future date.
	It is used to hedge against adverse changes in interest rates.
	Interest rate futures are mainly listed for 3-month Eurodollar, 1-month LIBOR, 1-month banker’s acceptance futures and 3-month banker’s acceptance futures.

	Advantages of trading interest rate futures and future options
	An investor who expected short-term interest rates to decline would also be expecting the price of the future contracts to increase. Thus, they might be inclined to purchase a 3-month ED futures call option to speculate on their belief.
	The advantage of future options over options of a spot asset stems from the liquidity of futures contracts.
	Futures markets tend to be more liquid than underlying cash markets.
	Interest rate future options are leveraged instruments.
	Other benefits
	Price transparency and liquidity
	Immediate execution and confirmation
	Reduction of counterparty risk
	Centralized clearing.

	Valuation
	The price of an interest rate option is quoted by the exchange.
	A model is mainly used for calculating sensitivities and managing market risk.
	European option approximation
	Interest rate future options are normally American options. One may use an European option for approximation.
	The present value of a call option is given by

V(t)=NτD(L(t)Φ(d_1 )-KΦ(d_2))
where 
d_1,2=±(L(t)-K)/(σ√(T-t))
t- the valuation date, 
L(t) =  Y(t;T,T_E)) – the forward rate
  				Or L(t) = (100 - F)/100
				K = (100-R)/100 – the strike
				R – quoted strike in price
K – the strike
 N – the notional
 τ – the day count fraction for period [〖T,T〗_E]
 T – the maturity of the future contract and also the start date of forward period
 T_E – the end date of the forward period
D – the discount factor
Φ – accumulative normal distribution function.

	The present value of a put option is given by

V(t)=NτD(KΦ(-d_2 )-L(t)Φ(d_1 ))
where 
d_1,2=±(L(t)-K)/(σ√(T-t))
t- the valuation date, 
L(t) =  Y(t;T,T_E)) – the forward rate
  				Or L(t) = (100 - F)/100
				K = (100-R)/100 – the strike
				R – quoted strike in price
K – the strike
 N – the notional
 τ – the day count fraction for period [〖T,T〗_E]
 T – the maturity of the future contract and also the start date of forward period
 T_E – the end date of the forward period
D – the discount factor
Φ – accumulative normal distribution function.

	A real world example

Future option specification	Underlying future specification
Quote Price	0.05	Contract Size	10000
Trade Date	11/23/2016	First Delivery Date	5/30/2017
Option Maturity Date	6/19/2017	Last Delivery Date	6/30/2017
Option Expiry Date	6/19/2017	Future Maturity Date	6/19/2017
Settlement Amount	-62500	Tenor	3M
Settlement Date	11/23/2016	Future Ticker	EDM17
Strike	98.75	Future Ticker Size	100
Option Ticker	EDM17P 98.75	Number of Contract	500
Call Put	Put		
Currency	USD		
Buy Sell	Buy		


References:

   
[More detials](./IrFutureOption-35.pdf)
   
[FlipHtml5 future option](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamMjN4gzM5ITPkl0av9mY)
   
[Zenodo future option](https://zenodo.org/record/4038197/files/IrFutureOption-35.pdf)
   
[Pubpub future option](https://interestrate.pubpub.org/pub/ayoefgzr/download/pdf)
   
[Github future option](https://github.com/alanwhite1203/irFutureOption/raw/main/IrFutureOption-35.pdf)
   
[Gitlab future option](https://gitlab.com/cmrm11/irfutureoption/-/raw/master/IrFutureOption-35.pdf)
   
[Bitbucket future option](https://bitbucket.org/cmrm11/irfutureoption/downloads/IrFutureOption-35.pdf)
   
[OSF future option](https://osf.io/gbzj3/download)

[Pub future option](https://interestrate.pubpub.org/pub/ayoefgzr/release/1)

[Pub future option pdf](https://assets.pubpub.org/uloyiim5/71597601350677.pdf)

[Github futre option](https://github.com/alanwhite1203/irFutureOption/raw/main/IrFutureOption-35.pdf)
