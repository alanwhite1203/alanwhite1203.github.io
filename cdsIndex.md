## Credit Default Swap Index Option 
   
Market participants are now able to trade in portfolio options whose underlying asset is TRAC-X North America portfolio (with 100 credits) or CDX North America portfolio (with 125 credits). Liquidity is also growing in the European version. The rationale for options based on such indices is that the portfolio effect will reduce the option volatility and make it easier for dealers to hedge. As far as an investor is concerned, this will give a way to take a macro view on spread volatility.

The CDS index contracts have typical expiries from three to nine months, and are typically physically settled. If the portfolio spread is wider than the strike level on the expiry date, the holder of the payer swaption (portfolio swap call) will exercise the option and lock in the portfolio protection at more favourable levels. If the portfolio spread is smaller than the strike, the holder of the receiver swaption (portfolio swap put) will benefit from exercising the option and realizing the mark-to-market gain. 

We start by defining the no-knockout (NKO) forward starting CDS contract and the associated NKO forward CDS rate. Then we present the detailed payoff of a portfolio swaption. Finally, we present the simplified view of it, and the corresponding Black pricing.

If we assume no counterparty credit risk, and mutual independence of default, interest rate and recovery rate risks (hazard and interest rates are assumed deterministic, and recovery rate is assumed constant), then (1) and (2) become:

The value at time t of the default-adjusted forward portfolio swap is then (we abbreviate CDS index by CDX – CDX happens to be the name of a real family of indices, but the presentation is not restricted to it, of course)

The pricing of this product with such a complex payoff is challenging. Full multiple default time simulations combined with approximating techniques applied already in equity basket option pricing could be used. At least for comparison reasons, one of these more demanding models could be implemented (the volume of input data required would be also bigger). Also, it is unlikely, but it is possible that the market may not embrace the standard exposed below, and, even if it does, pricing less liquid options will still remain a challenge. 


References:

   
[ResearchGate cds index pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369908221_Credit_Default_Swap_Index_Option_Model/links/64331adcad9b6d17dc46cd42/Credit-Default-Swap-Index-Option-Model.pdf)
   
[ResearchGate cds index](https://www.researchgate.net/publication/369908221_Credit_Default_Swap_Index_Option_Model)

[archive return](https://ia801401.us.archive.org/20/items/return-calculation/ReturnCalculation.pdf)

[gitbook ccr](https://cmrm11.gitbook.io/counterparty-credit-risk-jobs/)

[core futures pdf](https://core.ac.uk/download/534868760.pdf)

[core futures](https://core.ac.uk/works/126051692)
   