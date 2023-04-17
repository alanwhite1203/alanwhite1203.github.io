## Futures Fair Value 
   
The proposal for the new methodology to calculate the fair value of equity-index futures was reviewed. The proposed method attempts to improve traditional method by taking into consideration the dynamic rebulanching of the position (tail hedge) over the life of futures contract. We find the model adequate for the purposes of the fair value adjustment. We present our conclusions below. 

It is possible to identify several sources of error between the two models to account for these small discrepancies.  These include date roll conventions, yield curve interpolation, and numerical noise.  In the construction of the test model’ accurate date roll conventions, taking into account holidays and weekends were not implemented, rather the different maturities were simply represented as fractions of years.

It is known that the small differences in daycount fractions due to date rolls can easily account for the very small discrepancies between the test model and the GCD model.  Thus we are completely confident that the GCD model is performing correctly.

The identical contract priced from both curves reveals substantial differences in protection value. Since the model relies on fee information from the market in order to compute the mark to market of a derivative contract, it is reliable only to the extent that the input fee information is reliable.  Thus an important criterion is the efficiency of the relevant market.  

Contracts that are illiquid and for which the bid-ask spreads are large will be very difficult to price accurately with this model. In relation to the above paragraph, data of the correct type should be used, but the priority should be to use high quality data.  Thus if data for both contract types exists, but that for one type is much inferior to that of the other, the better quality data should be used.



References:

   
[ResearchGate fair pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369899263_Futures_Fair_Value_Model/links/6431cc06609c170a1302eba0/Futures-Fair-Value-Model.pdf)
   
[ResearchGate fair](https://www.researchgate.net/publication/369899263_Futures_Fair_Value_Model)

[OSF early](https://osf.io/kapm3/download)

[core frn pdf](https://core.ac.uk/download/534868267.pdf)

[core frn](https://core.ac.uk/works/126056982)
   