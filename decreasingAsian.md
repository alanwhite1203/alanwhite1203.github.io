## Decreasing Basket Asian Option 
   
Decreasing-Basket-Asian option, also called Himalayas option is an option that records the highest return at the end of each reset period among the stocks left in the basket for calculation of the payoff.  The stock with either the highest return or the lowest return, based on the specification, will then be eliminated from the basket for the rest reset periods.

The stock that had the lowest (highest) return in the first period will then be eliminated from the basket for consideration in the rest periods, if the contract specifies a drop-worst (drop-best) strategy.  Repeat this process for the remaining periods with a decreasing basket until the last period, and we obtain m returns, denoted    .  The Decreasing-Basket-Asian option is an European style derivative security whose matured payoff at the settlement date T is given by

Monte Carlo simulation associated with stratified sampling variance deduction is employed to evaluate the option.  There are six underlying assets whose prices are correlated, and six reset dates.  The initial price for each asset is 100, and the notional amount of the option is 100.  The strike is set to be zero.  The calculated option value is 19.8709 with a drop-worst strategy when 2000 simulations and 2000 samples in stratified sampling are used.  If a drop-best strategy is adopted, the option value is 21.4410.  Keeping the 2000 stratified samples unchanged, calculations with more simulations are conducted.  Table 1 shows the simulated results.


References:

   
[ResearchGate decreasing asian pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369898965_Decreasing_Basket_Asian_Option_Model/links/6431bd704e83cd0e2f9d3932/Decreasing-Basket-Asian-Option-Model.pdf)
   
[ResearchGate decreasing asian](https://www.researchgate.net/publication/369898965_Decreasing_Basket_Asian_Option_Model)

[OSF tree](https://osf.io/6eyrv/download)

[OSF arrear](https://osf.io/g6tp5/download)

[core bond curve pdf](https://core.ac.uk/download/534871175.pdf)

[core bond curve](https://core.ac.uk/works/127931168)
   