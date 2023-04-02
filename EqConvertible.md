## Convertible Bond Valuation
  
Convertible bonds can be thought of as normal corporate bonds with embedded options, which enable the holder to exchange the bond asset for the issuer's stock. Having properties of both stocks and bonds, 
convertibles can be an attractive choice for investors and have tended to have lower risk. 


	A convertible bond has an embedded call option that gives bondholders the right to convert their bonds into equity at a given time for a predetermined number of shares in the issuing company.
	An reverse convertible bond (RCB) has an embedded put option that gives the issuer the right to convert the bond's principal into shares of equity at a set date.
	Convertible bonds typically have lower yields than the yields on similar bonds without the convertible option.
	Reverse convertible bonds usually have shorter terms to maturity and higher yields than most other bonds
	Convertible bonds are hybrid securities that have both debt and equity features.
	Most convertible bonds are subordinated debt of the issuer. In the event of bankruptcy, the claims of other bondholders take priority over convertible bondholders except the preferred and common stock owners.


	By issuing convertibles they can lower their cost of debt funding compared to straight debt alone.
	Lower-credit companies who may not be able to access the straight debt market can often still issue convertible debt.
	Companies who anticipate equity appreciation can use convertibles to defer equity financing to a time when growth has been achieved.
	Convertible bonds offer greater satiability of income than common stock. 
	They provide a yield that is often higher than the dividend yield of common stock.
	Given the optionality, convertibles have tended to have lower risk.

	The valuation of convertible or reverse convertible bonds can be quite complex because of its dual nature as a normal bond and as an equity call/put option.
	There is no closed-form solution for convertibles.
	Convertible prices can only be solved by numerical methods, such as, Monte Carlo simulation, tree/lattice approaches, or partial differentiao equation (PDE) solutions.
	Three sources of randomness exist in a convertible bond: the stock price, the interest rate, and the credit spread.
	Interest rate is assumed to be constant as the effect of a stochastic interest rate on convertible bond prices is so small that it can be neglected.
	Accurately modeling the equity process appears crucial.
	Since convertible bonds are issued mainly by start-up or small companies (while more established firms rely on other means of financing), credit risk plays an important role in the valuation.
	FinPricing uses PDE to price convertible and reverse convertible bonds, and use Monte Carlo simulation to value convertibles with exotic path-dependent trigger provisions.
	The value of the convertible at each node is divided into two components: a component of bond and a component of stock
	The PDE of the equity component G is given by


∂G/∂t+0.5σ^2 S^2  (∂^2 G)/〖∂S〗^2 +(r-q+h(1-φ_s))S ∂G/∂S-(r+h(1-φ_s )G=0

	where
		S	the stock price
		r	the interest rate
		q	the dividend
		h	the hazard rate
		φs	the equity recovery rate
	

	The PDE of the bond component B is

∂B/∂t+0.5σ^2 S^2  (∂^2 B)/〖∂S〗^2 +(r-q+h(1-φ_s))S ∂B/∂S-(r+h(1-φ_b ))B=0

	where φb is the bond recovery rate

	The final conditions at maturity T can be generalized as

G_T={■(ηS_T            if ηS_T>min[P_c,max(P_p,N+C)]@0                                                          otherwise)┤

B_T={■(min[P_c,max(P_p,N+C)]          if ηS_T≤min[P_c,max(P_p,N+C)]@0                                                                                                   otherwise)┤

where 
N denotes the bond principal
C denotes the coupon 
  denotes the call price, 
  denotes the put price
  denotes the conversion ratio. 

	The final conditions tell us that the convertible bond at the maturity is either a debt or an equity.



References:
  
[More details](./EqConvertible-4.pdf)

[Zenodo convertible](https://zenodo.org/record/3945092)

[Fliphtml5 convertible](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamczMygjM5ITPkl0av9mY)

[gitbook pdf](https://captim.gitbook.io/eqconvertible/)

[github 3 factor](https://github.com/timxiao1203/ConvertibleThreeFactor)

