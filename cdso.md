## Credit Default Swap Option 
   
If we decide to go long a CDS call today, then this means that we need to pay a premium today for the right and not the obligation to buy a specified forward starting CDS (that is to enter in a specified CDS contract whose effective date is the call expiry date or later as protection buyers), with contract fee set to the call strike, at the call expiry date. 

The payoff is the positive part of the value of the underlying forward starting CDS at call expiry date (unknown today) if the reference name has not defaulted, and 0, otherwise. Reformulating, it is the positive part of the difference between the forward CDS rate at call expiry date (unknown today) and the call strike (known) times the forward annuity (discounted fee leg at 100% fee) at call expiry date (which is itself unknown today, and dependent on default time) conditional on survival. 

If we are to go long a CDS put, then we need to pay a premium today for the right and not the obligation to sell a specified forward starting CDS (that is to enter in a specified CDS contract whose effective date is the call expiry date or later as protection sellers), with contract fee set to the call strike, at the call expiry date. 

The payoff is the positive part of the difference between the call strike and the forward CDS rate at call expiry date times the forward annuity at call expiry date conditional on survival. If we are to go short a CDS option, then, for a premium, we expose ourselves to the potential exercise of the CDS option by the option owner. 

A pure CDS option will be knocked-out if the reference name defaults before the option expiry date (which automatically means before the effective date of the underlying forward starting CDS). This means that if default occurs before expiry date, the option value becomes 0. Of course, protection up to expiry can be bought separately if needed.

In order to be able to compute the expectation of the discounted payoff under spot-martingale measure (real world with no-arbitrage assumption) using the change-of-numeraire technique, two central issues are raised and need solutions: choosing the right numeraire (in our pricing, it is the forward annuity, which is a process dependent on default time) and proving the existence of the corresponding survival martingale measure (under which the forward CDS rate process becomes a martingale), and making the best assumption on the martingale dynamics of the forward CDS rate (in our pricing, it is Black’s lognormal Brownian motion assumption). 

The CDS Option model chooses the Black’s lognormal Brownian motion assumption for the forward CDS rate which leads to the famous Black closed form formulas. The essential ingredient becomes, as usual, the volatility parameter. It is interesting to notice that the recovery rate does not appear independently in the final formula, but it is already factored in the current forward CDS rate (credit risk assessment is not necessary, as it is already done by the market when the forward CDS rate is formed, the same way as the share valuation problem is irrelevant to the equity option pricing). 

Also, the current forward CDS rate factors in all default risk, which means that, for a given forward CDS rate, higher volatility does not make early default (and thus knock-out) more likely. Consequently, the price behaves just like in the equity option price case: even for a CDS put, the higher the volatility, the higher the price.  



References:

   
[ResearchGate cdso pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369937115_Single_Name_Credit_Default_Swap_Option_Model/links/6435712420f25554da256a9b/Single-Name-Credit-Default-Swap-Option-Model.pdf)
   
[ResearchGate cdso](https://www.researchgate.net/publication/369937115_Single_Name_Credit_Default_Swap_Option_Model)

[archive forward](https://ia904709.us.archive.org/7/items/forward-starting-option/ForwardStartingOption.pdf)

[gitbook risk](https://cmrm11.gitbook.io/dividend-risk/)

[core bonus pdf](https://core.ac.uk/download/534867897.pdf)

[core bonus](https://core.ac.uk/works/127932914)
   