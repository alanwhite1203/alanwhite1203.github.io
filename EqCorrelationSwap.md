## Correlation Swap Valuation
   
A Correlation Swap is a contract in which the option buyer receives the difference between the observed correlation and the strike correlation on a basket of assets, observed over a specified time interval. 

The correlation swap can be thought of as a forward contract on realized correlation. Its payoff is simply the difference between the realized correlation over the stated period and the strike times the notional of the contract, i.e.,
•	Buyer payoff = Notional x (realized correlation – strike correlation)
•	Seller payoff = Notional x (strike correlation – realized correlation)

The realized correlation of the basket is computed as the average of the   pair-wise correlations in a basket of n assets.  The strike correlation is set at inception date and stays constant during the life of the swap. The payoff may further be capped and floored.

Due to the nature of the contract, as maturity approaches, the payoff is almost known since all the observations for calculating the correlation are almost known. Therefore, the model risk decreases as the contract moves toward maturity.

For an outstanding contract, implied correlation needs to be computed for any future correlations that can be thought of as the market price of future correlation. The implied correlation or correlation mark can be backed out from observed correlation swap prices of from OTC dealer quotes. Most commonly it can be calculated via Monte-Carlo simulation. The total correlation is equal to a weighted average of the realized correlation and the implied correlation.

Investors can use a correlation swap to hedge correlation risk. It gives investor exposures to the average correlation of an index. Correlation swaps also allow investors to speculate or bet or hedge future correlations.



References:
   
[More details](./EqCorrelationSwap-26.pdf)   
   
[Zenodo correlation swap](https://zenodo.org/record/5759799/files/Zenodo-EqCorrelationSwap.pdf)
   
[Pubpub correlation swap](https://david.pubpub.org/pub/7xhp22bd/release/1)
   
[OSF correlation swap](https://osf.io/uwy25/download)

[archive correlation swap](https://ia803401.us.archive.org/11/items/eq-correlation-swap-26/EqCorrelationSwap-archive.pdf)  