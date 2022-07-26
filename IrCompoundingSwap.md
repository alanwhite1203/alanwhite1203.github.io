## Compounding Swap Valuation
   
A compounding swap is an interest rate swap in which interest, instead of being paid, compounds forward until the next payment date. Compounding swaps can be valued by assuming that the forward rates are realized. Normally the calculation period of a compounding swap is smaller than the payment period. For example, a swap has 6-month payment period and 1-month calculation period (or 1-month index tenor). An overnight index swap (OIS) is a typical compounding swap. This presentation gives an overview of compounding swap product and valuation model. 


	Assuming that An average compounded swap consists of two legs: a regular fixed leg and a compounding floating leg.
	The compounding leg is similar to a regular floating leg except the reset frequency is higher than the payment frequency. For example, a compounding leg has 1 month reset frequency and 6 month payment frequency.
	From the fixed rate payer perspective, the payoff of a swap or swaplet at payment date T is given by
〖Payff〗_payer=NτR-NF)
where 
N- the notional;
 τ – accrual period in years (e.g., a 3 month period ≈ 3/12 = 0.25)
R – the fixed rate in simply compounding.
F=∏_(j=1)^k〖(1+Q_j )-1〗 – the realized compounded floating rate for a payment period, e.g., 6-month
Q_j=r_j τ_j – the accrued interest for a calculation period, say, 1-month
	From the fixed rate receiver perspective, the payoff of a swap or swaplet at payment date T is given by
〖Payff〗_receiver=Nτ(F-R)

	Valuation
	The present value of a fixed rate leg is given by

〖PV〗_fixed (t)=RN∑_(i=1)^n〖τ_i D_i 〗
where t is the valuation date and D_i=D(t,T_i) is the discount factor.
	The present value of a floating leg is given by
〖PV〗_compound (t)=N∑_(i=1)^n〖(∏_(j=1)^k〖(1+Q_i 〗)-1) τ_i D_i 〗
where
Q_j=〖(r〗_(j+s)) τ_j –the accrued interest for calculation period j.
 F_i=(D_(i-1)/D_i -1)/τ_i - the simply compounded forward rate
s - the floating spread.
	The present value of an interest rate swap can expressed as
	From the fixed rate payer perspective, PV=〖PV〗_float-〖PV〗_fixed		
	From the fixed rate receiver perspective, PV=〖PV〗_fixed-〖PV〗_float



References:

		
[More details](./IrCompoundingSwap-32.pdf)
   
[Zenodo compounding](https://zenodo.org/record/5771052/files/Zenodo-IrCompoundingSwap.pdf)
   
[OSF compounding](https://osf.io/dqepj/download)

[Zenodo commitment](https://zenodo.org/record/6547376)

[github rate lock](https://github.com/cfrm17/RateLockAnalysis)


