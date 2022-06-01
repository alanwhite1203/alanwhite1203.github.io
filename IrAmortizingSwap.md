## Amortizing and Accreting Swap Valuation

An amortizing swap is an interest rate swap whose notional principal amount declines during the life of the contract whereas an accreting swap is an interest rate swap whose notional principal amount increases instead. The notional amount changes could be one leg or two legs, but typically on a fixed schedule. The notional principal is tied to an underlying financial instrument with a declining principal, such as a mortgage or an increasing principal, such as a construction fund. 

The notional principal of an amortizing swap is tied to an underlying financial instrument with a declining principal, such as a mortgage. On the other hand, the notional amount of an accreting swap  is tied to an underlying instrument with an increasing principal, such as a construction fund. The notional principal schedule of an amortizing or an accreting swap may decrease or increase at the same rate as the underlying instrument. Both amortizing and accreting swaps can be used to reduce or increase exposure to fluctuations in interest rates. This presentation gives an overview of amortizing or accreting swap product and valuation model. 

	Keywords
Amortizing swap, Accreting Swap, Interest rate swap, OTC derivatives, swaplet, valuation, pricing model, interest rate risk

	Interest Rate Amortizing or Accreting Swap Introduction
	An interest rate swap is an agreement between two parties to exchange future interest rate payments over a set period of time.
	An amortizing swap is an interest rate swap whose notional principal amount declines during the life of the contract
	An accreting swap is an interest rate swap whose notional principal amount increases instead.
	The notional amount changes could be one leg or two legs, but typically on a fixed schedule.
	The notional principal is tied to an underlying financial instrument with a declining principal, such as a mortgage or an increasing principal, such as a construction fund.

	The Use of Amortizing or Accreting Swap 
	The notional principal of an amortizing swap is tied to an underlying financial instrument with a declining principal, such as a mortgage.
	On the other hand, the notional amount of an accreting swap  is tied to an underlying instrument with an increasing principal, such as a construction fund.
	The notional principal schedule of an amortizing or an accreting swap may decrease or increase at the same rate as the underlying instrument.
	Both amortizing and accreting swaps can be used to reduce or increase exposure to fluctuations in interest rates.

	Valuation
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

	Practical Notes
	First of all, you need to generate accurate cash flows for each leg. The cash flow generation is based on the start time, end time and payment frequency of the leg, plus calendar (holidays), business convention (e.g., modified following, following, etc.) and whether sticky month end.
	We assume that accrual periods are the same as reset periods and payment dates are the same as accrual end dates in the above formulas for brevity. But in fact, they are different due to different market conventions. For example, index periods can overlap each other but swap cash flows are not allowed to overlap.
	The accrual period is calculated according to the start date and end date of a cash flow plus day count convention 
	The forward rate should be computed based on the reset period (index reset date, index start date, index end date)  that are determined by index definition, such as index tenor and convention. it is simply compounded.
	Sometimes there is a floating spread added on the top of the floating rate in the floating leg.
	The formula above doesn’t contain the last live reset cash flow whose reset date is less than valuation date but payment date is greater than valuation date. The reset value is
〖PV〗_reset=r_0 Nτ_0 D_0  
where r_0 is the reset rate. 
	The present value of the reset cash flow should be added into the present value of the floating leg.
	Some dealers take bid-offer spreads into account. In this case, one should use bid curve constructed from bid quotes for forwarding and offer curve built from offer quotes for discounting.



References:

		
[More details](./IrAmortizingSwap-26.pdf)
 
[FlipHtml5 amortizing swap](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamITO3gDN3ITPkl0av9mY)
 
[Zenodo amortizing swap](https://zenodo.org/record/4015549/files/IrAmortizingSwap-26.pdf)
 
[OSF amortizing swap](https://osf.io/mgc83/download)

[Zenodo swap](https://zenodo.org/record/6546723#.YpDu3qgpDq4)


