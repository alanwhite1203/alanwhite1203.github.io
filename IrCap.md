## Interest Rate Caps and Floors Valuation
   
An interest rate cap is an OTC derivative where the buyer receives payments at the end of each period when the interest rate exceeds the strike, whereas an interest rate floor is a similar contract where the buyer receives payments at the end of each period when the interest rate is below the strike. Caps and floors are widely used to hedge against interest rate fluctuations. 

An interest rate cap is a financial contract between two parties that provides an interest rate ceiling or cap on the floating rate payments. It actually consists of a series of European call options (caplets) on interest rates.  The buyer receives payments at the end of each period when the interest rate exceeds the strike.  In return, the buyer needs to pay an up-front premium to the seller.

Interest rate caps are frequently purchased by issuers of floating rate debt who wish to protect themselves from the increased financing costs that would result from a rise in interest rates. Investors use caps to hedge against the risk associated with floating interest rate and will benefit from any risk in interest rates above the strike. The holder gets a payment when the underlying interest rate exceeds a specified strike rate. This presentation gives an overview of interest rate cap products and valuation model. 


	The holder gets a payment when the underlying interest rate exceeds a specified strike rate.

	The Payoff of a Caplet
	The payoff of a caplet
Payoff=N*τ*max(R-K,0)
where N – the notional; R – the realized interest rate; K – the strike; τ – the day count fraction.
	Payoff diagram
 

	Valuation
	The present value of a cap is given by
PV(0)=N∑_(i=1)^n〖τ_i D_i (F_i Φ(d_1 )-KΦ(d_2)) 〗
where 
D_i=D(0,T_i) – the discount factor; 
F_i=F(t;T_(i-1),T_i )=(D_(i-1)/D_i -1)/τ_i – the forward rate for period (T_(i-1),T_i).
Φ – the accumulative normal distribution function
d_1,2=(ln⁡(F_i/K)±0.5σ_i^2 T_i)/(σ_i √(T_i ))





References:
   
   
[More details](./IrCap-30.pdf) 
   
[Zenodo cap](https://zenodo.org/record/6493279/files/Zenodo-IrCap.pdf)
   
[OSF cap](https://osf.io/kvbyz/download)

[Zenodo acquisation](https://zenodo.org/record/6547140)

[github balance](https://github.com/cfrm17/BalanceSheetRisk)


