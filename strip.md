## Strip Rho 
   
Rho is defined as change of the instrument value with respect to 10bps parallel shift of the entire continuous compounding zero curve.  Users can input the rate shock amount when requesting rho calculation from the model.  The default amount is still 10bps.

Strip rho is a piece-wise shift of the zero curve.  It is defined as change of the instrument value with respect to 10 bps shift of the continuous compounding zero curve between maturities of two adjacent Eurodollar futures contracts.  Since the date lag between maturities of two adjacent Eurodollar futures contracts is sometimes not the same as the effective period of the underlying Libor, the effective periods of these Libor rates may overlap, or there is a gap between the maturity of an underlying Libor and that of the next futures contract start date.  We also calculate number of Eurodollar futures contracts for these occasions using an adjustment method.

The above calculations apply to situations that either a single currency (USD) is involved in the instrument, or USD is the payoff currency in duo-currency instruments.  In cases where USD is the underlying currency that is different from the payoff currency, a spot exchange rate   has to be divided from the right side of equation (7).  Here   is expressed as units of the payoff currency per one USD.

We also propose a method by precisely calculating number of contracts due to over-hedging or less-hedging, and subsequently removing or adding those contracts.  In this method, instead of calculating strip rho by shifting the forward interest rate between maturities of two adjacent Eurodollar futures contracts, strip rho is defined as



References:

   
[ResearchGate strip pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369931682_Strip_Rho_Calculation/links/643566e3ad9b6d17dc4ed8e7/Strip-Rho-Calculation.pdf)
   
[ResearchGate strip](https://www.researchgate.net/publication/369931682_Strip_Rho_Calculation)

[archive local](https://ia904700.us.archive.org/23/items/local-vol-quanto/LocalVolQuanto.pdf)

[gitbook methodology](https://cmrm11.gitbook.io/debt-specific-risk-methodology/)

[core american pdf](https://core.ac.uk/download/534871192.pdf)

[core american](https://core.ac.uk/works/127931203)
   