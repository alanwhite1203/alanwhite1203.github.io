## Callable Bond Valuation

A callable bond is a bond in which the issuer has the right to call the bond at specified times from the investor for a specified price. At each callable date prior to the bond maturity, the issuer may recall the bond from its investor by returning the investor’s money. The underlying bonds can be fixed rate bonds or floating rate bonds. A callable bond can therefore be considered a vanilla underlying bond with an embedded Bermudan style option. Callable bonds protect issuers. Therefore, a callable bond normally pays the investor a higher coupon than a non-callable bond. 

For issuers, callable bonds allow them to reduce interest costs at a future date should rate decrease. For investors, callable bonds allow them to earn a higher interest rate of return until the bonds are called off. If interest rates have declined since the issuer first issues the bond, the issuer is like to call its current bond and reissues it at a lower coupon. Callable bonds protect issuers. Therefore, a callable bond normally pays investors a higher coupon than a non-callable bond. This presentation gives an overview of callable bond and valuation model.

	At the bond maturity T, the payoff of a callable bond is given by


V_c (T)={(F+C                 if not called@〖min⁡(P〗_c,F+C)        if called)┤
where 
F – the principal or face value; 
C – the coupon; 
P_c – the call price; 
T -  the maturity date;
min (x, y) – the minimum of x and y

	The payoff of the callable bond at any call date T_i can be expressed as

 (3)

V_c (T_i )={(¯V_(T_i )                                  if not called@min⁡(P_c,¯V_(T_i ) )                        if called)┤
where 	
¯V_(T_i ) – continuation value at T_i
P_c – the call price; 
T_i -  the i-th call date;
min (x, y) – the minimum of x and y


	Given the valuation complexity of a callable bond (e.g., embedded Bermudan option), there is no closed form solution. Therefore, we need to select an interest rate term structure model and a numeric solution to price the callable bond.
	The selection of interest rate term structure models
	Popular IR term structure models: 
Hull-White, Linear Gaussian Model (LGM), Quadratic Gaussian Model (QGM), Heath Jarrow Morton (HJM), Libor Market Model (LMM).
	HJM and LMM are too complex.
	Hull-White is inaccurate for computing sensitivities.
	Therefore, we choose either LGM or QGM.
	 The selection of numeric approaches
	After selecting a term structure model, we need to choose a numeric approach to approximate the underlying stochastic process of the model.
	Commonly used numeric approaches are tree, partial differential equation (PDE), lattice, and Monte Carlo simulation.
	Tree and Monte Carlo are notorious for inaccuracy in sensitivity calculation.

	The dynamics
dX(t)=α(t)dW
	Where X is the single state variable; W is the Wiener process.
	The numeraire is given by
N(t,X)=(H(t)X+0.5H^2 (t)ζ(t))/D(t)
	The zero coupon bond price is
B(t,X;T)=D(T)exp(-H(t)X-0.5H^2 (t)ζ(t))

	The LGM model is mathematically equivalent to the Hull-White model but offers
	Significant improvements in calibration stability and accuracy.
	More accurate and stable in sensitivity calculation.
	The state variable is normally distributed under the appropriate measure.
	The LGM model has only one stochastic driver (one-factor), thus changes in rates are perfected correlated.




References:


[More details](./FiCallableBond-13.pdf)

[Zenodo callable](https://zenodo.org/record/5765076)

[Zenodo bma swap](https://zenodo.org/record/6558053)

[OSF callable](https://osf.io/qkbfn/download)

[Fliphtml5 callable](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamEzM1ITM5ITPkl0av9mY)

[Gitbook callable](https://cmrm11.gitbook.io/callable-bond/)

[github digital](https://github.com/timxiao1203/DigitalOption)

