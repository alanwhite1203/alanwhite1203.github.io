## Rainbow Option Valuation

A rainbow option is an option on a basket that pays a non-equally weighted sum of returns over all assets in the basket according to their performance, where individual asset returns are computed as the percentage growth from initial levels to final levels that may be averages over multiple dates.

Rainbow options are multi-asset options that have a payoff depending on the assets by their performance at maturity. When the rainbow only pays the best (worst) performing asset of the basket, it is also called the best (worst) of performing option.

The number of assets is called the number of colours of the rainbow, as the option is based on a combination of various assets just like a rainbow is a combination of various colours. The assets are sorted by their performance at payment date. Asian rainbow option is a common version of rainbows where the return of an asset takes an average, as the Asian rainbow is usually cheaper than the vanilla one. 

The payoff function can be specified in the form of a put, call or a forward (pure return). The structure is unique in the way the weights are applied to assets in computing the payment. First, assets may be grouped into buckets each containing one or more asset. A vector of weights is then applied to the ranked bucket returns based on performance. 

Rainbow options are appealing to investors due to its natural risk diversification, cost efficiency, and weighted average on the best or worst performing assets. The best version offers higher returns, whereas the worst version is normally cheap.



References:
   
[More details](./EqRainbow-24.pdf)   
   
[Zenodo rainbow](https://zenodo.org/record/5759794)
   
[OSF rainbow](https://osf.io/47zwk/download)

[Fliphtml5 rainbow](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamcjM1QjN4MTPkl0av9mY)

[gitbook rainbow](https://davidlee1203.gitbook.io/rainbow-option/)

[github mbs](https://github.com/timxiao1203/MBS-Model)