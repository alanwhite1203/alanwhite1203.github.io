## FX Futures Valuation
 
A currency future, also known as an FX future , is a future contract to exchange one currency for another at a specified date in the future at an exchange rate that is fixed on the purchase date. By using a currency future contract, the parties are able to effectively lock-in the exchange rate for a future transaction. Speculation and hedging in currencies can be achieved primarily through future contracts. 
A currency future or an FX future is a future contract between two parties to exchange one currency for another at a fixed exchange rate on a fixed future date. Currency futures are one of the main methods used to hedge against exchange rate volatility, as they avoid the impact of currency fluctuation over the period covered by the contract. 
Because currency futures contracts are marked-to-market daily, investors can exit their obligation to buy or sell the currency prior to the contract's delivery date. Future market participants and speculators usually close out their positions before the date of settlement, so most contracts do not tend to last until the date of delivery. Currency futures contracts are legally binding and counterparties that are still holding the contracts on the expiration date must trade the currency pair at a specified price on the specified delivery date.

Investors use futures contracts to hedge against foreign exchange risk. If an investor will receive a cashflow denominated in a foreign currency on some future date, that investor can lock in the current exchange rate by entering into an offsetting currency futures position that expires on the date of the cashflow. Currency futures can also be used to speculate and, by incurring a risk, attempt to profit from rising or falling exchange rates.

The currency future contracts are usually used by exporters and importers to hedge their foreign currency payments from exchange rate fluctuations. By using FX future contracts, investors can protect costs on products and services purchased abroad or protect profit margins on products and services sold abroad lock-in exchange rates as much as a year in advance.
Future contracts are traded in an exchange and thus have no credit risk. By locking-in the exchange rates at which the currency will be bought, the party forfeits the opportunity of profiting from a favorable exchange rate movement. Additionally, unfavorable exchange rate movements may take away further opportunity of the party for profit. This presentation gives an overview of currency futures and valuation model. 

Given spot rate X_s , spot date T_s and forward date T, the FX forward rate can be represented as


{■(X_f=X_s  (D_b (T_s,T))/(D_q (T_s,T))                 if  T≥T_s@X_f=X_s  (D_q (T,T_s))/(D_b (T,T_s))                 if  T<T_s )┤
where
	X_s  	the spot FX rate quoted as base/quote
	t 	the valuation date
	T_s 	the spot date (several days after the valuation date)
	T 	the forward date
	D_b (T_s,T) 	the discount factor of base currency from spot date to forward date
	D_q (T_s,T) 	the discount factor of quote currency from spot date to forward date


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




References:

 
[More details](./FxFuture-21.pdf)
  
[Zenodo fx futures](https://zenodo.org/record/5768241/files/Zenodo-FxFuture.pdf)
  
[archive fx futures](https://ia803403.us.archive.org/10/items/fx-future-21/FxFuture-archive.pdf)
  
[OSF futures](https://osf.io/rqd6v/download)

[Zenodo collateralized](https://zenodo.org/record/6539697#.YpDuTKgpDq4)

[github mortgage](https://github.com/cfrm17/AdjustableRateMortgages)