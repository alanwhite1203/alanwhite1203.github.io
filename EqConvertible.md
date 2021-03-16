## Convertible Bond
  
Convertible bonds can be thought of as normal corporate bonds with embedded options, which enable the holder to exchange the bond asset for the issuer's stock. Having properties of both stocks and bonds, convertibles can be an attractive choice for investors and have tended to have lower risk. 



A convertible bond has an embedded call option that gives bondholders the right to convert their bonds into equity at a given time for a predetermined number of shares in the issuing company. Whereas a reverse convertible bond has an embedded put option that gives the issuer the right to convert the bond's principal into shares of equity at a set date. 


Convertible bonds typically have lower yields than the yields on similar bonds without the convertible option. Reverse convertible bonds usually have shorter terms to maturity and higher yields than most other bonds.

Most convertible bonds are subordinated debt of the issuer. In the event of bankruptcy, the claims of other bondholders take priority over convertible bondholders, who themselves have priority over owners of the preferred and common stock.


Issuers have several reasons to use convertible financing. By issuing convertibles they can lower their cost of debt funding compared to straight debt alone. Lower-credit companies who may not be able to access the straight debt market can often still issue convertible debt. Companies who anticipate equity appreciation can use convertibles to defer equity financing to a time when growth has been achieved.
	
Investors find several features of convertibles appealing. They offer greater satiability of income than common stock. They provide a yield that is often higher than the dividend yield of common stock. Finally, because they are often theoretically underpriced, they may provide a cheap source of common stock volatility. This presentation gives an overview of convertible bond and valuation model.


Keyword

Convertible bond, reverse convertible bond, conversion ratio, hybrid security, valuation, PDE



	Introduction

	A convertible bond has an embedded call option that gives bondholders the right to convert their bonds into equity at a given time for a predetermined number of shares in the issuing company.
	An reverse convertible bond (RCB) has an embedded put option that gives the issuer the right to convert the bond's principal into shares of equity at a set date.
	Convertible bonds typically have lower yields than the yields on similar bonds without the convertible option.
	Reverse convertible bonds usually have shorter terms to maturity and higher yields than most other bonds
	Convertible bonds are hybrid securities that have both debt and equity features.
	Most convertible bonds are subordinated debt of the issuer. In the event of bankruptcy, the claims of other bondholders take priority over convertible bondholders except the preferred and common stock owners.

	The Use of convertible bonds
	By issuing convertibles they can lower their cost of debt funding compared to straight debt alone.
	Lower-credit companies who may not be able to access the straight debt market can often still issue convertible debt.
	Companies who anticipate equity appreciation can use convertibles to defer equity financing to a time when growth has been achieved.
	Convertible bonds offer greater satiability of income than common stock. 
	They provide a yield that is often higher than the dividend yield of common stock.
	Given the optionality, convertibles have tended to have lower risk.


	Valuation
	Convertible bonds are hybrid securities that have both debt and equity features.

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


The upside constraints at time   are


{■(■(G=ηS,   B=0        if  ηS_T>min[P_c,max(P_p,L ̃ )]@G=0,   B=P_p                                     else if    L ̃≤P_p )@■(G=0,   B=P_c                                      else if    L ̃≥P_c  @G=G ̃,   B=B ̃                                                          else))┤

where 
L ̃=B ̃+G ̃ is the continuation value of the convertible bond 
B ̃ is the continuation value of the bond component
G ̃ is the continuation value of the equity component.


	Implementation
	The valuation can be done via backward induction. The procedure is as follows.
For i = penultimateTime to currentTime
	// determine accrual interest and call/put prices
	// determine boundary nodes
// use the PSOR (Projected Successive over Relaxation) method to obtain the    
continuation value of the bond component   and the continuation value of the equity  component  , applying the constraints (31). 
EndFor
	The value at node[0][y] is the convertible bond price where the equity price at node[0][y] is equal to the current market stock price.


	A Real World Example

Underlying Equity	EFN.TO	Conversion Ratio	52.35
Convertible Bond ISIN	CA286181AB88	Conversion Start Date	1/1/2016
Currency	CAD	Conversion End Date	6/30/2020
Face Value	100	Coupon	0.0425
Percent Redemption	1	First Coupon Date	12/31/2015
DayCount	dc30360U	First Settle Date	5/29/2015
Call Start Date	6/30/2018	Coupon Frequency	SEMIANNUAL
Call End Date	6/29/2020	Roll Type	Following
Call Price	100	Issue Price	100
Call Notice Period	30	Market Quote Type	CLEAN
Call Trigger	125	Maturity	6/30/2020
Trigger days	20	Par Amount	1000


References:
  
[More details](./EqConvertible-4.pdf)
  
[FlipHtml5 convertible](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamczMygjM5ITPkl0av9mY)
  
[Zenodo convertible](https://zenodo.org/record/3945092/files/EqConvertible-4.pdf)
  
[Pubpub convertible](https://david.pubpub.org/pub/p5wrxj58/download/pdf)
  
[Github convertible](https://github.com/alanwhite1203/EqConvertible/raw/master/EqConvertible-4.pdf)
  
[Gitlab convertible](https://gitlab.com/finance15/eqconvertible/-/raw/master/EqConvertible-4.pdf)
  
[Bitbucket convertible](https://bitbucket.org/cmrm11/eqconvertible/downloads/EqConvertible-4.pdf)
  
[OSF convertible](https://osf.io/5uzdy/download)

[Pub convertible](https://david.pubpub.org/pub/p5wrxj58/release/1)

[Pub pdf](https://assets.pubpub.org/a41h7lgw/71595703115219.pdf)

[Github convertible](https://github.com/alanwhite1203/EqConvertible/raw/master/EqConvertible-4.pdf)

[gitbook pdf](https://captim.gitbook.io/eqconvertible/)

[science-media pdf](https://science-media.org/userfiles/1020/presentations/1020_presentation_497.pdf)
