## Amortizing and Accreting Swap Valuation

An amortizing swap is an interest rate swap whose notional principal amount declines during the life of the contract whereas an accreting swap is an interest rate swap whose notional principal amount increases instead. The notional amount changes could be one leg or two legs, but typically on a fixed schedule. The notional principal is tied to an underlying financial instrument with a declining principal, such as a mortgage or an increasing principal, such as a construction fund. 

The notional principal of an amortizing swap is tied to an underlying financial instrument with a declining principal, such as a mortgage. On the other hand, the notional amount of an accreting swap  is tied to an underlying instrument with an increasing principal, such as a construction fund. The notional principal schedule of an amortizing or an accreting swap may decrease or increase at the same rate as the underlying instrument. Both amortizing and accreting swaps can be used to reduce or increase exposure to fluctuations in interest rates. This presentation gives an overview of amortizing or accreting swap product and valuation model. 

	The analytics is similar to a vanilla interest rate swap but the principal amount used by each period may be different.
	The present value of a fixed rate leg is given by

〖PV〗_fixed (t)=R∑_(i=1)^n▒〖N_i τ_i D_i 〗
where t is the valuation date and D_i=D(t,T_i) is the discount factor.
	The present value of a floating leg is given by
〖PV〗_float (t)=∑_(i=1)^n▒〖N_i (F_i+s) τ_i D_i 〗
where F_i=(D_(i-1)/D_i -1)/τ_i is the simply compounded forward rate and s is the floating spread.
	The present value of an interest rate swap can expressed as
	From the fixed rate payer perspective, PV=〖PV〗_float-〖PV〗_fixed		
	From the fixed rate receiver perspective, PV=〖PV〗_fixed-〖PV〗_float



References:

		
[More details](./IrAmortizingSwap-26.pdf)
 
[OSF amortizing swap](https://osf.io/mgc83/download)

[Fliphtml5 amortizing swap](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamITO3gDN3ITPkl0av9mY)

[Zenodo swap](https://zenodo.org/record/6546723)

[Zenodo amortizing swap](https://zenodo.org/record/5771045/files/Zenodo-IrAmortizingSwap.pdf)

[github portfolio](https://github.com/cfrm17/PortfolioAcquisition)

