## Equity American Option Valuation

An American option give an investor the right but not the obligation to buy a call or sell a put at a set strike price at any time prior to the contract’s expiry date. Since investors have the freedom to exercise their American options at any point during the life of the contract, they are more valuable than European options, which can only be exercised at maturity.  

An American option give an investor the right but not the obligation to buy a call or sell a put at a set strike price at any time prior to the contract’s expiry date. American options provide investors a way to hedge risk or speculate.  In general, American options do not have a closed-form solution. This presentation provides a practical guide for pricing an American equity option. 

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

On this grid, the point (i,j) corresponds to time i∆t and stock price j∆Z. Let the value of the option at (i,j) be denoted by f_(i,j). Values for N and M are chosen based on the life of the option and the desired level of accuracy.

The Crank-Nicolson finite difference model replaces the space and time derivatives with finite differences centered at an imaginary time step at (i+1/2). Therefore, we obtain the following formula:


References:

[More details](./EqAmerican-1.pdf)

[Zenodo American](https://zenodo.org/record/5748070)

[Fliphtml5 American](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamcTOxgjM5ITPkl0av9mY)

[gitbook AO](https://captim.gitbook.io/eqamerican/)

[FlipHtml5 American](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamcTOxgjM5ITPkl0av9mY)

[Github gic pooling](https://github.com/timxiao1203/EquityLinkedGICPooling)
