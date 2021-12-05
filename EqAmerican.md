## Equity American Option Valuation

An American option give an investor the right but not the obligation to buy a call or sell a put at a set strike price at any time prior to the contract’s expiry date. Since investors have the freedom to exercise their American options at any point during the life of the contract, they are more valuable than European options, which can only be exercised at maturity.  

An American option give an investor the right but not the obligation to buy a call or sell a put at a set strike price at any time prior to the contract’s expiry date. American options provide investors a way to hedge risk or speculate.  In general, American options do not have a closed-form solution. This presentation provides a practical guide for pricing an American equity option. 

	American Option Introduction

	An American option give an investor the right but not the obligation to buy a call or sell a put at a set strike price at any time prior to the contract’s expiry date. 
	Since investors have the freedom to exercise their American options at any point during the life of the contract, they are more valuable than European options, which can only be exercised at maturity. 
	An investor holding an American-style option and seeking optimal value prefer to sell it on, rather than exercise it before maturity under certain circumstances. 
	Investors and traders can use equity options to take a long or short position in a stock without actually buying or shorting the stock. 
	This is advantageous because taking a position with options allows the investor/trader more leverage in that the amount of capital needed is much less than a similar outright long or short position on margin. 
	Investors/traders can therefore profit more from a price movement in the underlying stock.
	American options provide investors a way to hedge risk or speculate.  Also option trading can limit an investor’s risk and leverage investing potential. 
	Option investors have a number of strategies they can utilize, depending on risk tolerance and expected return.
	Buying call options allows you to benefit from an upward price movement. The right to buy stock at a fixed price becomes more valuable as the price of the underlying stock increases.
	Put options may provide a more attractive method than shorting stock for profiting on stock price declines.
	If you have an established profitable long stock position, you can buy puts to protect this position against short-term stock price declines. 
	An option seller earns the premium if the underlying stock price would not change much.

	Valuation

	In general, American options do not have a closed-form solution.
	There are several methods to approximate the price of an American option: Roll-Geske-Whaley, Barone-Adesi and Whaley, Bjerksund and Stensland.
	To accreately value an American option, one needs to use a numerical approach.
	The most popular numerical methods are tree, lattice, PDE and Monte Carlo.
	FinPricing is using the Black-Scholes PDE plus finite difference method to price an American equity option.
	The finite difference model is one of the most widely used methods of approximation to solve the partial differential equation (PDE) equation for American options.
	There are three finite difference approximations most widely used for pricing American options: the Explicit, Fully Implicit and Crank-Nicolson models.
	Among these three, the  Crank-Nicolson  is unconditionally stable with respect to domain discretization and is the most accurate. 
	Compared with the binomial tree method or the Whaley model, Crank-Nicolson also has obvious advantages of computation speed and accuracy. 
	The Black-Scholes PDE for American option is:
	∂V/∂t+1/2 σ^2 S^2  (∂^2 V)/〖∂S〗^2 +(r-q)S ∂V/∂S-rV ≤0	
where
S – the underlying stock price
V – the price of the American optin as a function of time and the underlying stock price
σ – the volatility of the underlying stock
r – the continuously compounded risk-free interest rate
q – the dividend yield
t – the time in years

	The boundary condition for an American call option is given by
C(S,T)=max⁡(S-K,0), C(0,t)=0, C(S→∞,t)=S
	The boundary condition for an American put option is given by
P(S,T)=max⁡(K-S,0), P(0,t)=S, P(S→∞,t)=0
where 
T – the expiry time
K – the exercise price
C and P – the  payoffs for the call and put options respectively

	Practical Guide

	To solve the PDE using the finite difference method, one needs to define the grid.
	In the time dimension, divide the time t into N equally spaced intervals of length ∆t=T⁄N where T is the option maturity date.
	In the stock price dimension, divide the stock price into M equally spaced intervals of length ∆Z=σ√3∆t, which should cover at least 3 standard deviations.
	One challenge is how to define the grid in the case of discrete dividends. If the grid is missing a discrete dividend, the price of the option might significantly differ from the fair value.
	In the FinPricing Platform, the finite difference grid is constructed dynamically to mitigate the above mentioned risks.
	For the case of discrete dividends, FinPricing dynamically inserts an extra point on the grid, if necessary, to calculate the fair value of the option.

	A Real World Example
Underlying equity	CCJ.N
Currency	USD
Strike	8
Maturity Date	1/19/2018
Call or Put	Put
Buy or Sell	Buy
Exercise Type	American
Settlement Type	Physical
Position	250000


On this grid, the point (i,j) corresponds to time i∆t and stock price j∆Z. Let the value of the option at (i,j) be denoted by f_(i,j). Values for N and M are chosen based on the life of the option and the desired level of accuracy.

The Crank-Nicolson finite difference model replaces the space and time derivatives with finite differences centered at an imaginary time step at (i+1/2). Therefore, we obtain the following formula:


References:

[More details](./EqAmerican-1.pdf)

[Zenodo American](https://zenodo.org/record/5748070/files/Zenodo-EqAmerican.pdf)

[Archive AO](https://ia803409.us.archive.org/30/items/eq-american-1/EqAmerican-archive.pdf)

[gitbook AO](https://captim.gitbook.io/eqamerican/)

[science-media AO](https://science-media.org/userfiles/1020/presentations/1020_presentation_495.pdf)
