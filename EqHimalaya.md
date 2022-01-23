## Himalaya Option Valuation

Himalaya option is a popular version of maintain range options that basically pays the sum of the best performers of a basket of assets over a particular time horizon. Maintain range options are exotic options that have multiple underlying assets, path-dependency, and best (worst) of payoff structure. They include Everest options, Atlas options, Altiplano options, and Himalaya options. 

A Himalaya option is an option on the sum of the returns of the best (worst) performing assets from a basket on predefined observation dates. It has a set of observation dates are defined. The number of observation dates are equal to the number of underlying assets. The unique feature of Himalaya option is the withdrawal of the best performer asset from the basket at each pre-defined observation date, until only one stock remains.

On each pre-defined observation date, the return of the best performing asset is locked in, and the best performing asset is eliminated from the basket. The locked-in return may be capped and floored for each period. The removal of the best performing asset makes Himalaya option strongly path-dependent.

The Asian Himalaya pays off the average of the lock-in returns at maturity. The payoff could be further modified by participation.

A Digital Reverse Himalaya option contains a barrier feature. On each observation date, if any stock in the basket falls below the barrier level, a digital coupon is paid. When the barrier is triggered, the worst performing asset is removed from the basket. If the barrier is not triggered, no assets are removed.

Himalaya option is appealing to an investor due to the payoff structure as the option evaluates the maximum return of the best performing asset.

Due to the complexity of the payoff structure, the option is normally priced via Monte Carlo simulation. 



References:
   
[More details](./EqHimalaya-25.pdf)   
   
[Zenodo himalaya](hhttps://zenodo.org/record/5759797/files/Zenodo-EqHimalaya.pdf)
   
[Pubpub himalaya](https://david.pubpub.org/pub/3d3lpnvc/release/1)
   
[OSF himalaya](https://osf.io/3hf9y/download)

[archive himalaya](https://ia803400.us.archive.org/13/items/eq-himalaya-25/EqHimalaya-archive.pdf)  

[hcommons himalaya](https://hcommons.org/deposits/download/hc:41448/CONTENT/eqhimalaya-25.pdf)