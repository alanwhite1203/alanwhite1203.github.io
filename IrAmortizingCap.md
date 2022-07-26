## Amortizing and Accreting Cap and Floor Valuation

An amortizing cap is an interest rate cap whose notional principal amount declines during the life of the contract whereas an accreting cap is an interest rate cap whose notional principal amount increases during the life of the contract. Similarly, an amortizing floor is an interest rate floor whose notional principal amount declines during the life of the contract whereas an accreting floor is an interest rate floor whose notional principal amount increases during the life of the contract. 

An interest rate cap is a financial contract between two parties that provides an interest rate ceiling or cap on the floating rate payments. It consists of a series of European call options (caplets) on interest rates. An amortizing cap is an interest rate cap whose notional principal amount declines during the life of the contract whereas an accreting cap is an interest rate cap whose notional principal amount increases during the life of the contract.

An amortizing cap is primarily used to hedge loans whose principal declines on a scheduled basis while an accreting cap is primarily used to hedge construction loans whose principal increases on a scheduled basis to meet the expanding working capital requirements. Amortizing caps are frequently purchased by issuers of floating rate debt where the loan principal declines during the life. Similarly accreting caps are frequently purchased by issuers of floating rate debt where the loan principal increases during the life. The holders wish to protect themselves from the increased financing costs that would result from a rise in interest rates. This presentation gives an overview of interest rate amortizing or accreting cap products and valuation model. 


	The payoff of a caplet is given by
Payoff=N_i*τ*max(R-K,0)
where N_i – the notional of period i; R – the realized interest rate; K – the strike; τ – the day count fraction.
	Payoff diagram
 

	The analytics is similar to a vanilla cap the principal amount used by each period may be different.
	The present value of an amortizing or accreting cap is given by
PV(0)=∑_(i=1)^n〖N_i τ_i D_i (F_i Φ(d_1 )-KΦ(d_2)) 〗
where 
D_i=D(0,T_i) – the discount factor; 
F_i=F(t;T_(i-1),T_i )=(D_(i-1)/D_i -1)/τ_i – the forward rate for period (T_(i-1),T_i).
Φ – the accumulative normal distribution function
d_1,2=(ln⁡(F_i/K)±0.5σ_i^2 T_i)/(σ_i √(T_i ))





References:


[More details](./IrAmortizingCap-25.pdf)

[OSF amortizing cap](https://osf.io/rfa8e/download)

[Zenodo index](https://zenodo.org/record/6546586)

[github hedge](https://github.com/cfrm17/FairValueHedge)