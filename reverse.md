## Reverse Floor Option 
   
A reverse floor option has multiple reset periods before the maturity of the option.  At the end of each reset period, a return of the underlying is recorded.  The payoff of the option at maturity is related to the accumulated absolute values of those negative returns. We present a pricing model for reverse floor options using Monte Carlo simulation.

above formula is in a world that is forward risk-neutral with respect to a specific currency  .  As a result, the notional principal N is measured in the currency  , and the discounting factor should be calculated by a   zero curve given at the value date.  If the underlying asset is measured in another currency  , the governing price dynamics of this underlying asset in the risk-neutral world of   should be written as

We first test a Quasi - Monte Carlo method via Sobol sequence to evaluate the option.  There are fifteen reset dates, and consequently fourteen period returns.  The calculated option value is 99.5385 when 20000 simulations are used.  Calculations with other simulations are conducted.  Table 1 shows the simulated results.


References:

   
[ResearchGate reverse pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369931759_Reverse_Floor_Option_Model/links/6435615220f25554da25650e/Reverse-Floor-Option-Model.pdf)
   
[ResearchGate reverse](https://www.researchgate.net/publication/369931759_Reverse_Floor_Option_Model)

[archive gic](https://ia801400.us.archive.org/6/items/gic-pooling/GicPooling.pdf)

[gitbook modeling](https://cmrm11.gitbook.io/debt-specific-risk-default-modeling/)

[core extendable pdf](https://core.ac.uk/download/534871188.pdf)

[core extendable](https://core.ac.uk/works/127933936)
   