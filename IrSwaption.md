## Swaption Valuation
   
An interest rate swaption or interest rate European swaption is an OTC option that grants its owner the right but not the obligation to enter an underlying interest rate swap. There are two types of swaptions: a payer swaption and a receiver swaption.

An payer swaption is also called a right-to-pay swaption that allows its holder to exercise into a swap where the holder pays fixed rates and receives floating rates, while a receiver swaption is also called right-to-receive swaption that allows its holders to exercise into a swap where the holder receives fixed rates and pays floating rates.

Swaptions provide clients with a guarantee that the fixed rate of interest they will pay at some of future time will not exceed certain level. This presentation gives an overview of swaption product and valuation. 

An interest rate swaption or interest rate European swaption is an OTC option that grants its owner the right but not the obligation to enter an underlying interest rate swap. There are two types of swaptions: a payer swaption and a receiver swaption. A payer swaption is also called a right-to-pay swaption that allows its holder to exercise into a swap where the holder pays fixed rates and receives floating rates. A receiver swaption is also called right-to-receive swaption that allows its holders to exercise into a swap where the holder receives fixed rates and pays floating rates. Swaptions provide clients with a guarantee that the fixed rate of interest they will pay at some of future time will not exceed certain level.

Market participants use swaptions to manage interest rate risk arising from their business. A firm might buy a payer swaption if it wants protection from rising interest rates. A corporation holding a mortgage portfolio might buy a receiver swaption to protect against decreasing interest rates that might lead to mortgage prepayment. A company believing that interest rates will not increase much might sell a payer swaption and earns the premium. An institution believing that interest rates will not decrease much might sell a receiver swaption and earns the premium.

	For a payer swaption, the payoff at payment date T is given by
〖Payff〗_payer=max⁡(0,NA(S_T-S_0)		(1)
where 
N- the notional;
A – the annuity or forward basis point value
S_0 – the fixed rate or contract swap rate at inception
S_T – the swap rate at time T.
	From a receiver swaption, , the payoff at payment date T is given by
〖Payff〗_payer=max⁡(0,NA(S_0-S_T)		(2)

	Valuation
	The present value of a payer swaption is given by
 〖PV〗_payer (t)=NA[SΦ(d_1 )-KΦ(d_2)] 			(1)                          
where
	t   –  valuation date
	N  – notational principal amount
A=∑_(i=1)^n▒〖τ_i D_i 〗 – annuity factor or forward basis point value
S=[D_1-D_n ]⁄A  - forward swap rate
  -  the cumulative standard normal distribution function
	i  –  ith cash flow (swaplet) of the underlying swap from 1 to n
	τ_i=τ(T_(i-1),T_i) – the accrual period ( , ) of the ith cash flow.
	D_i=D(t,T_i)  –  the discount factor
	The present value of a receiver swaption can be expressed as

 〖PV〗_payer (t)=NA[KΦ(〖-d〗_2 )-SΦ(〖-d〗_1 )] 			(2)      
                    
where all notations are the same as (1)



References:

				
[More details](./IrSwaption-37.pdf)
   
[Zenodo swaption](https://zenodo.org/record/5771060/files/Zenodo-IrSwaption.pdf)
   
[OSF swaption](https://osf.io/f7yw9/download)

[Zenodo pass](https://zenodo.org/record/6549222#.YpDvoKgpDq4)

[github mba swap](https://github.com/cfrm17/MBASwap)
   