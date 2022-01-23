## Rainbow Option Valuation

A rainbow option is an option on a basket that pays a non-equally weighted sum of returns over all assets in the basket according to their performance, where individual asset returns are computed as the percentage growth from initial levels to final levels that may be averages over multiple dates.

Rainbow options are multi-asset options that have a payoff depending on the assets by their performance at maturity. When the rainbow only pays the best (worst) performing asset of the basket, it is also called the best (worst) of performing option.

The number of assets is called the number of colours of the rainbow, as the option is based on a combination of various assets just like a rainbow is a combination of various colours. The assets are sorted by their performance at payment date. Asian rainbow option is a common version of rainbows where the return of an asset takes an average, as the Asian rainbow is usually cheaper than the vanilla one. 

The payoff function can be specified in the form of a put, call or a forward (pure return). The structure is unique in the way the weights are applied to assets in computing the payment. First, assets may be grouped into buckets each containing one or more asset. A vector of weights is then applied to the ranked bucket returns based on performance. 

Rainbow options are appealing to investors due to its natural risk diversification, cost efficiency, and weighted average on the best or worst performing assets. The best version offers higher returns, whereas the worst version is normally cheap.

Due to the complexity of the payoff structure, the option is normally priced via Monte Carlo simulation. 



References:
   
[More details](./EqRainbow-24.pdf)   
   
[Zenodo rainbow](https://zenodo.org/record/5759794/files/Zenodo-EqRainbow.pdf)
   
[Pubpub rainbow](https://david.pubpub.org/pub/zr8o4n3k/release/1)
   
[OSF rainbow](https://osf.io/47zwk/download)

[archive rainbow](https://ia903404.us.archive.org/15/items/eq-rainbow-24/EqRainbow-archive.pdf)  

[hcommons rainbow](https://hcommons.org/deposits/download/hc:41308/CONTENT/eqrainbow-24.pdf)

[gitbook rainbow](https://davidlee1203.gitbook.io/rainbow-option/)

[science-media rainbow](https://science-media.org/userfiles/1020/presentations/1020_presentation_521.pdf)