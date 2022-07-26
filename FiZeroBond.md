## Zero Coupon Bond Valuation

A company can raise capital in financial markets either by issuing equities or bonds. A zero coupon bond is a bond that doesn’t pay interest/coupon but instead pays one lump sum face value at maturity. Investors buy zero coupon bonds at a deep discount from their face value. A zero coupon bond generates gains from the difference between the purchase price and the face value while a coupon bond produces gains from the regular distribution of coupon/interest.
Zero coupon bonds are issued at a deep discount and repaid the face value at maturity. The greater the length of the maturity is the cheaper price a bond has. Unlike other bonds, the investor’s return is the difference between the purchase price and the face value. An investor preferring a long-term investment may purchase zero coupon bonds such as saving money for children’s college tuition. The deep discount helps the investor grow a small amount of money into a sizable sum over several years. Normally investors buy zero coupon bonds when interest rates are high. This presentation gives an overview of zero coupon bond product and valuation. 

	The present value of a risk-free zero coupon bond is given by
B(t)=Pe^(-rT)
where
	t – valuation date
P – principal amount or face value
	r - continuous compounded interest rate for the period (t,T)
	T – maturity date
	The present value of a defaultable zero coupon bond can be expressed as
B(t)=Pe^(-(r+s)T)
where
s – credit spread


	For a risk-free zero coupon bond with $1 face value, the bond price B(t)=e^(-rT) that is exactly the discount factor.
	In theory, a discount factor is a stochastic variable while a zero coupon bond price is deterministic variable. The bond price is the expectation of the discount factor.
	In practice, however, discount factor and risk-free zero coupon bond price are equivalent.

	Intuitively,   e^(-(r+s)T)   can be regarded as a credit risk adjusted discount factor.



References:


[More details](./FiZeroBond-17.pdf)

[Zenodo zero bond](https://zenodo.org/record/5765447)

[OSF zero bond](https://osf.io/d59wu/download)

[Gitbook zero](https://cmrm11.gitbook.io/zero-coupon-bond/)

[github collatral swap](https://github.com/cfrm17/CollateralizedSwap)





   