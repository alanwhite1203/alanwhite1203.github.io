## Best Performer Option Valuation
   
A best performer option pays the option holder the best return at maturity among a given set of portfolios, where each portfolio may be defined by a set of weights on the same underlying basket or different baskets.

These are chooser options that return the best performing among several baskets of funds or indices that reflect growth, moderate and conservative investment styles. The returns could be based on average (Asian), single currency or quanto. The final payoff could be capped and floored.

This category also contains worst performer option, option on the maximum, option on minimum, and rainbow.

Most commonly, portfolio weights are all positive and sum to 1. Note however, that weights are allowed to take on zero or negative values and need not necessarily sum to 1, but these values can considerably change the price and risk profile of the structure.

There are several following styles:

	Call on best return: 
payoff_T=max⁡(R^best-K,0)
	Call on worst return: 
payoff_T=max⁡(R^worst-K,0)
	Put on best return: 
payoff_T=max⁡(K-R^best,0)
	Put on worst return: 
payoff_T=max⁡(K-R^worst,0)
	Call on best return with cap and floor
 

 


References:
   
[More details](./EqPerform-17.pdf)   

   
[Zenodo best](https://zenodo.org/record/6480269)
   
[OSF best](https://osf.io/7pzms/download)

[Fliphtml5 best](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamAjNzQzM4MTPkl0av9mY)

[gitbook best](https://deripricing.gitbook.io/best-of-option-pricing/)

[github hw vol](https://github.com/timxiao1203/HullWhiteVolatilityCalibration)