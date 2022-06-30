## Interest Rate Bermudan Swaption Valuation
  
 An interest rate Bermudan swaption gives the holder the right but not the obligation to enter an interest rate swap at predefined dates. It is one of the fundamental ways for an investor to enter a swap. Comparing to regular swaptions, Bermudan swaptions provide market participants more flexibility and control over the exercising of an option and less restriction.

Given those flexibilities, a Bermudan swaption is more expensive than a regular European swaption. In terms of valuation, it is also much more complex. This presentation provides practical details for pricing Bermudan swaption. 


	At the maturity T, the payoff of a Bermudan swaption is given by
Payoff(T)=max⁡(0,V_swap (T))
	where V_swap (T) is the value of the underlying swap at T.
	At any exercise date T_i, the payoff of the Bermudan swaption is given by
Payoff(T_i )=max(V_swap (T_i ),I(T_i))
Where V_swap (T_i) is the exercise value of the Bermudan swap and I(T_i) is the intrinsic value.


	Given the complexity of Bermudan swaption valuation, there is no closed form solution. Therefore, we need to select an interest rate term structure model and a numeric solution to price Bermudan swaptions.
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
	Therefore, we choose either PDE or lattice.
	We decide to use LGM plus lattice. 

	Create the lattice based on the LGM: the grid range should cover at least 3 standard deviations.
	Find the underlying swap value at each final note.
	Conduct backward induction process iteratively rolling back from final dates until reaching the valuation date.
	Compare exercise values with intrinsic values at each exercise date.
	The value at the valuation date is the price of the Bermudan swaption.





References:

 
[More details](./IrBermudan-28.pdf)
  
[FlipHtml5 bermudan](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamQTMxkjNyETPkl0av9mY)
  
[Zenodo bermudan](https://zenodo.org/record/6492307/files/Zenodo-IrBermudan.pdf)
   
[OSF bermudan](https://osf.io/5dz4u/download)

[Zenodo flow](https://zenodo.org/record/6546938#.YpDvB6gpDq4)

[github mortgage](https://github.com/cfrm17/MortgageCommitment)

