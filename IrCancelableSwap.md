## Interest Rate Cancelable Swap Valuation
   
A cancelable swap provides the right but not the obligation to cancel the interest rate swap at predefined dates. Most commonly traded cancelable swaps have multiple exercise dates. Given its Bermudan style optionality, a cancelable swap can be represented as a vanilla swap embedded with a Bermudan swaption. Therefore, it can be decomposed into a swap and a Bermudan swaption. Most Bermudan swaptions in a bank book actually come from cancelable swaps. This presentation provides practical details for pricing cancelable swaps.


	A Cancelable Swap Example

〖PV〗_CancellablePayerSwap=〖PV〗_PayerSwap-〖PV〗_ReceiverBermudanSwaption
〖PV〗_CancellableReceiverSwap=〖PV〗_ReceiverSwap-〖PV〗_PayerBermudanSwaption



	Bermudan Swaption Payoffs
	At the maturity T, the payoff of a Bermudan swaption is given by
Payoff(T)=max⁡(0,V_swap (T))
	where V_swap (T) is the value of the underlying swap at T.
	At any exercise date T_i, the payoff of the Bermudan swaption is given by
Payoff(T_i )=max(V_swap (T_i ),I(T_i))
Where V_swap (T_i) is the exercise value of the Bermudan swap and I(T_i) is the intrinsic value.


	The LGM model is mathematically equivalent to the Hull-White model but offers
	Significant improvements in calibration stability and accuracy.
	More accurate and stable in sensitivity calculation.
	The state variable is normally distributed under the appropriate measure.
	The LGM model has only one stochastic driver (one-factor), thus changes in rates are perfected correlated.

	LGM calibration
	Match today’s curve
At time t, X(0)=0 and H(0)=0. Thus Z(0,0;T)=D(T). In other words, the LGM automatically fits today’s discount curve.
	Select a group of market swaptions.
	Solve parameters by minimizing the relative error between the market swaption prices and the LGM model swaption prices.

	Valuation Implementation
	Calibrate the LGM model.
	Create the lattice based on the LGM: the grid range should cover at least 3 standard deviations.
	Find the underlying swap value at each final note.
	Conduct backward induction process iteratively rolling back from final dates until reaching the valuation date.
	Compare exercise values with intrinsic values at each exercise date.
	The value at the valuation date is the price of the Bermudan swaption.
	The present value of the cancelable swap is given by






References:

   
[More details](./IrCancelableSwap-29.pdf)
   
[Zenodo cancelable](https://zenodo.org/record/6492737/files/Zenodo-IrCancelableSwap.pdf)
   
[OSF cancelable](https://osf.io/v7whf/download)

[Zenodo fair value](https://zenodo.org/record/6547047)

[github performance](https://github.com/cfrm17/PerformanceDeferredShare)

