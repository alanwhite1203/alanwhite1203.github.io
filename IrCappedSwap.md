## Capped Swap Valuation
   
A capped swap is an interest rate swap with an interest rate cap option where the floating rate of the swap is capped at a certain level while a floored swap is an interest rate swap with a floor option where the floating rate of the swap is floored at a certain level. Capped swaps or floored swaps limit the risk of the floating rate payer or receiver to adverse movements in interest rates. A capped swap can be decomposed into a swap and a cap whereas a floored swap can be decomposed into a swap and a floor. 

A capped swap can be decomposed into a swap and a cap whereas a floored swap can be decomposed into a swap and a floor. Given the optionality, an up-front fee or premium has to be paid by the floating rate payer for a capped swap and an up-front fee or premium has to be paid by the floating rate receiver for a floored swap. This presentation gives an overview of capped/floored swap product and valuation.

	A floored swap is an interest rate swap with a floor where the floating rate of the swap is floored at a certain level.
	It limits the risk of the floating rate receiver to adverse movements in interest rates.
	Given the optionality, an up-front fee or premium has to be paid by the floating rate receiver.
	A floored swap can be decomposed as a swap plus an interest rate floor.

	There are four types of capped or floored swap.
	Capped payer swap
	Capped receiver swap
	Floored payer swap
	Floored receiver swap


	The present value of a capped payer swap is given by
〖PV〗_CappedPayerSwap (t)=〖PV〗_float (t)-〖PV〗_fixed (t)-〖PV〗_cap (t)
Where 
〖PV〗_float is the present value of the floating leg of the underlying swap;
 〖PV〗_fixed is the present value of the fixed leg of the underlying swap;
〖PV〗_cap is the present value of the embedded cap.

	The present value of a capped receiver swap can be expressed as
〖PV〗_CappedReceiverSwap (t)=〖PV〗_fixed (t)-〖PV〗_float (t)+〖PV〗_cap (t)
Where  〖PV〗_floor is the present value of the embedded floor.

	The present value of a floored payer swap can be represented as
〖PV〗_FlooredPayerSwap (t)=〖PV〗_float (t)-〖PV〗_fixed (t)+〖PV〗_floor (t)

	The present value of a floored receiver swap can be computed as
〖PV〗_FlooredReceiverSwap (t)=〖PV〗_fixed (t)-〖PV〗_float (t)-〖PV〗_floor (t)





	The present value of the fixed leg is given by
〖PV〗_fixed (t)=RN∑_(i=1)^n〖τ_i D_i 〗
Where R – the fixed rate; N – the notional; τ_i – the day count fraction for period [T_(i-1),T_i]; D_i=D(t,T_i) – the discount factor.
	The present value of the floating leg is given by
〖PV〗_float (t)=N∑_(i=1)^n〖(F_i+s)τ_i D_i 〗
Where s – the floating spread; F_i=F(t;T_(i-1),T_i )=1/τ_i  (D_(i-1)/D_i -1) – the simply compounded forward rate
	The present value of the cap is given by

〖PV〗_cap (t)=N∑_(i=1)^n〖τ_i D_i (F_i Φ(d_1 )-KΦ(d_2)) 〗
Where d_1,2=(ln⁡(F_i/K)±0.5σ_i^2 T_i )/(σ_i √(T_i )) and Φ – the cumulative normal distribution function.
	The present value of the floor is given by

〖PV〗_cap (t)=N∑_(i=1)^n〖τ_i D_i (KΦ(-d_2 )-F_i Φ(〖-d〗_1 )) 〗



References:

   
[More details](./IrCappedSwap-31.pdf)
   
[Zenodo capped swap](https://zenodo.org/record/6493574/files/Zenodo-IrCappedSwap.pdf)
 
[OSF capped](https://osf.io/jskhm/download)

[Zenodo deferred asset](https://zenodo.org/record/6547212)

[Github mortgage](https://github.com/cfrm17/MortgageAnalytics)


