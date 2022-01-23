## Stock Warrant Valuation
   
An equity warrant is an option on the equity of a firm issued by the same firm, which gives the holder the right to purchase shares at a fixed price from the firm at a future date. When a warrant is exercised, the firm typically issues new shares at the exercise price to fill the order. The resulting increase in shares outstanding dilutes the share value. 

An equity warrant gives the holder the right to purchase shares at a fixed price from the firm. It is an option on the common stock of a firm issued by the same firm. Warrants are in many ways similar to call options, but a few key differences distinguish them. 

Warrants tend to have longer durations than do exchange-traded call options. They are traded over the counter more often than on an exchange. Investors cannot write warrants like they can options. Warrants do not pay dividends or come with voting rights. When warrants are exercised, the company typically issues new shares at the exercise price to fill the order. The resulting increase in shares outstanding dilutes the share value.

Investors are attracted to warrants as a means of leveraging their positions in a security. Warrants provide investors a way to hedge risk or speculate. They can be used to exploiting arbitrage opportunities.  

Warrants frequently attached to bonds or preferred stock as a sweetener can be used to enhance the yield of the bond and make them more attractive to potential buyers. Most commonly issued warrants are often detachable, meaning that they can be separated from the bond and sold on the secondary market before expiration. Wedded or wedding warrants are not detachable. The investor must surrender the bond or preferred stock the warrant is "wedded" to in order to exercise it. Naked warrants are issued on their own, without accompanying bonds or preferred stock.



	Introduction

	An equity warrant gives the holder the right to purchase shares at a fixed price from the firm.
	An equity warrant is an option on the common stock of a firm issued by the same firm.
	Warrants are in many ways similar to call options, but a few key differences distinguish them.
	Warrants tend to have longer durations than do exchange-traded call options.
	They are traded over the counter more often than on an exchange.
	Investors cannot write warrants like they can options.
	Warrants do not pay dividends or come with voting rights.
	When warrants are exercised, the company typically issues new shares at the exercise price to fill the order. The resulting increase in shares outstanding dilutes the share value.

	The Use of Warrants

	Investors are attracted to warrants as a means of leveraging their positions in a security.
	Warrants provide investors a way to hedge risk or speculate.
	Warrants can be used to exploiting arbitrage opportunities. 
	Warrants are frequently attached to bonds or preferred stock as a sweetener. They can be used to enhance the yield of the bond and make them more attractive to potential buyers.
	Most commonly issued warrants are often detachable, meaning that they can be separated from the bond and sold on the secondary market before expiration.
	Wedded or wedding warrants are not detachable. The investor must surrender the bond or preferred stock the warrant is "wedded" to in order to exercise it.
	Naked warrants are issued on their own, without accompanying bonds or preferred stock.


	Payoff

If there were n shares outstanding and m warrants exercised, the dilution factor corresponding to the percentage of the firm value that is represented by the warrants is given by
	α=m/(m+n)
	

The payoff of the warrant at T is given by
payoff=m/(m+n) max⁡(A-K,0)
where
	A=V/m	the asset price
	V		the firm value


	Valuation
Warrants can be valued by the Black-Scholes model, but some modifications must be made to the parameters.

The price of the warrant under the diluted Black-Scholes model is given by
W=m/(m+n) (Ae^(-qT) Φ(d_1 )-Ke^(-rT) Φ(d_2))

where
d_1,2=(ln⁡(A/K)+(r-q±0.5σT))/(σ√T)
	
Strictly speaking, A is the asset price of the firm and σ is the volatility of the firm (not stock). Both of them are not observable. For simplicity, some people use stock price and stock volatility to replace the firm value A and the firm volatility σ above, although this simplification generally underestimates the warrant’s price.

	Assumption
	There are several assumptions in this simplified warrant model (5): 1) the price process of the stock follows a geometric Brownian motion; 2) the stock provides a continuous proportional instantaneous pay-out (continuous dividend); 3) the risk-free interest rate is deterministic; 4) the volatility is constant; 5) the asset value per share is equal to the stock price; 6) the volatility of the firm is equal to the volatility of the stock.


	A Real World Example


Outstanding Shares	109254024
Underlying equity	BTX.A
Currency	USD
Strike	4.55
Maturity Date	10/1/2018
CallPut	Call
Exercise Type	European
Settlement Type	Physical
Position	2038


References:
   
[More details](./EqWarrant-8.pdf)     
   
[Zenodo warrant](https://zenodo.org/record/3948314/files/EqWarrant-8.pdf)
   
[hcommons warrant](https://hcommons.org/deposits/download/hc:38350/CONTENT/eqwarrant-8.pdf)

[Pub warrant](https://david.pubpub.org/pub/tejvirlb/release/1)

[archive warrant](https://ia903404.us.archive.org/22/items/eq-warrant-8/EqWarrant-archive.pdf)
   

[OSF warrant](https://osf.io/54xj6/download)

[gitbook warrant](https://deripricing.gitbook.io/warrant-valuation/)

