## Forward Rate Agreement Valuation
   
A forward rate agreement, or FRA, is a forward contract between two parties in which one party will pay a fixed rate while the other party will pay a reference interest rate for a set future period. Similar to a swap, a FRA has two legs: a fixed leg and a floating leg. But each leg only has one cash flow. The party paying the fixed rate is usually referred to as the borrower, while the party receiving the floating rate is referred to as the lender.

Some people believe that a FRA is equivalent to a one-period vanilla swap. That is not completely true from valuation perspective. A FRA is usually settled and paid at the end of a forwarding period, called settle in arrear, while a regular swaplet is settled at the beginning of the forward period and paid at the end. Strictly speaking, FRAs need convexity adjustment. However, given FRA is such a simple product, the adjustment is very simple as well. 

FRAs are over-the-counter (OTC) derivatives. They are cash-settled with the payment based on the net difference between the floating interest rate and the fixed (reference) rate in the contract. Similar to a swap, a FRA has two legs associating with each party: a fixed leg and a floating leg. But each leg only has one cash flow. The party paying the fixed rate is usually referred to as the buyer, while the party receiving the floating rate is referred to as the seller.

A FRA can be used to hedge future interest rate or exchange rate exposure. The buyer hedges against the risk of rising interest rate whereas the seller hedges against the risk of falling interest rates. In other words, the buyer locks in the interest rate to protect against the increase of interest rates while the seller protects against the possible decrease of interest rates. A speculator can also use FRAs to make bets on future directional changes in interest rates. Market participants can also take advantage of price differences between an FRA and other interest rate instruments. FRAs are money market instruments that are liquid in all major currencies. This presentation provides an introduction to FRA product and valuation. 


	From the seller perspective, the payoff of a FRA at payment date T is given by
〖Payff〗_seller=Nτ(R-F)		(1)
where 
N- the notional;
 τ – accrual period in years (e.g., a 3 month period ≈ 3/12 = 0.25)
R – the fixed rate in simply compounding.
F – the realized floating rate in simply compounding
	From the puyer perspective, the payoff of the FRA at payment date T is given by
〖Payff〗_buyer=Nτ(F-R)		(2)

	Some people believe that a FRA is equivalent to a one-period vanilla swap. That is not completely true from valuation perspective. 
	A FRA is usually settled and paid at the end of a forwarding period, called settle in arrear, while a regular swaplet is settled at the beginning of the forward period and paid at the end. 
	Strictly speaking, FRAs need convexity adjustment. However, given FRA is such a simple product, the adjustment is very simple as well.
	The present value of a fixed leg is given by
〖PV〗_fixed=RNτD/(1+Rτ)		(3)
where
	t   –  valuation date
	R  – fixed rate
	N  – notational principal amount
	T_1 – end time of the forwarding period
	T_0 – start time of the forwarding period
	τ=τ(T_0,T_1)  – accrual period (T_0,T_1).
	D=D(t,T_1)  –  discount factor

	The present value of a floating leg can be expressed as
〖PV〗_floating=(F+s)NτD/(1+Fτ)		(4)
where
	F=F(t;T_0,T_1) – simply compounded forward rate
	s -  floating spread
	The present value of an interest rate swap can expressed as
	For the payer perspective, PV=〖PV〗_float-〖PV〗_fixed		
	From the receiver perspective, PV=〖PV〗_fixed-〖PV〗_float




References:

		
[More details](./IrFra-33.pdf)
   
[Zenodo fra](https://zenodo.org/record/6493996/files/Zenodo-IrFra.pdf)
   
[OSF fra](https://osf.io/k8v2q/download)

[Fliphtml5 fra](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamADO5UjM5ITPkl0av9mY)

[Zenodo performance](https://zenodo.org/record/6547457)

[github mbs](https://github.com/cfrm17/MBSPassThrough)

