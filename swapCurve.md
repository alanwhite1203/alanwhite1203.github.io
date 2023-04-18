## Swap Curve 
   
The swap curve construction is an algorithm based on the assumption that the term forward rate curve must exhibit minimal quadratic variation. The Curve Construction Algorithm contains the following main features:
 
•	Maximal input generality: a variety of market instruments like cash deposit, 1-month futures, regular and serial 3-month futures, swap could be used. 

•	 Maximal smoothness of the term forward rate curve is implied by design, as minimality of its quadratic variation is required in the algorithm. One of the important consequences is that the outputted 1 and 3 month forward curves move in parallel producing smoother P&L report profiles.

•	The new curve may have the ability of reasonably predicting market rates of standard instruments that have not been used in the input. We are not aware of an extensive compilation of data supporting this statement, but on our USD example this property is noticeable. 

Depending on currency, we recommend a standard list of input instruments (see main text). In USD case, it enforces a behind the scenes dropping of longer term cash deposit contracts in favour of 1-month futures contracts when both types of contracts are being inputted making it a so-called futures dominated curve.

From market cash deposit rates and futures contract yields, using the correct conventions, we can easily determine continuously compounded term forward rates for the corresponding underlying term. Assume there are m input instruments used to construct the short end. 

That is, these forward rates should satisfy the m linear equations imposed by relation (3) (see below) so that the generated curve can faithfully re-price the input instruments (the short-end can then be declared arbitrage-free). 


References:

   
[ResearchGate swap curve pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369899213_Swap_Curve_Construction/links/6431d58b20f25554da1b4f17/Swap-Curve-Construction.pdf)
   
[ResearchGate swap curve](https://www.researchgate.net/publication/369899213_Swap_Curve_Construction)

[OSF digital](https://osf.io/qzmer/download)

[gitbook exposure](https://cmrm11.gitbook.io/collateralized-exposure/)

[core arrear pdf](https://core.ac.uk/download/534871194.pdf)

[core arrear](https://core.ac.uk/works/127931210)
   