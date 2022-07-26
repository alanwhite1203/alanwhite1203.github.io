## Future Option Valuation
   
An interest rate future option gives the holder the right but not the obligation to buy or sell an interest rate future at a specified price on a specified date. It is usually traded in an exchange. The buyer normally can exercise the option on any business day (American style) prior to expiration by giving notice to the exchange. Option sellers (writer) receive a fixed premium upfront and in return are obligated to buy or sell the underlying asset at a specified price.

Interest rate future options can be used to hedge against adverse changes in interest rates. In general futures markets tend to be more liquid than underlying cash markets. This presentation gives an overview of interest rate future option product and pricing model. 

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




References:

   
[More detials](./IrFutureOption-35.pdf)
   
[Zenodo future option](https://zenodo.org/record/6494261/files/Zenodo-IrFutureOption.pdf)
   
[OSF future option](https://osf.io/gbzj3/download)

[Zenodo mortgage](https://zenodo.org/record/6548953)

[github knockout](https://github.com/cfrm17/KnockoutSwap)

