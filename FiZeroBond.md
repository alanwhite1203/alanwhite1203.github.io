## Zero Coupon Bond Valuation

A company can raise capital in financial markets either by issuing equities or bonds. A zero coupon bond is a bond that doesn’t pay interest/coupon but instead pays one lump sum face value at maturity. Investors buy zero coupon bonds at a deep discount from their face value. A zero coupon bond generates gains from the difference between the purchase price and the face value while a coupon bond produces gains from the regular distribution of coupon/interest.
Zero coupon bonds are issued at a deep discount and repaid the face value at maturity. The greater the length of the maturity is the cheaper price a bond has. Unlike other bonds, the investor’s return is the difference between the purchase price and the face value. An investor preferring a long-term investment may purchase zero coupon bonds such as saving money for children’s college tuition. The deep discount helps the investor grow a small amount of money into a sizable sum over several years. Normally investors buy zero coupon bonds when interest rates are high. This presentation gives an overview of zero coupon bond product and valuation. 

	Zero Coupon Bond Introduction
	A company can raise capital in financial markets either by issuing equities or bonds. 
	A zero coupon bond is a bond that doesn’t pay interest/coupon and instead pays one lump sum face value at maturity. 
	Investors buy zero coupon bonds at a deep discount from their face value. Zero coupon bonds are probably the simplest bond type in the market.
	The bond principal will be returned at maturity date.
	A zero coupon bond generates gains from the difference between the purchase price and the face value while a coupon bond produces gains from the regular distribution of coupon/interest.

	The Use of Zero Coupon Bonds
	Zero coupon bonds are issued at a deep discount and repaid the face value at maturity.
	The greater the length of the maturity is, the cheaper price a bond has.
	Unlike other bonds, the investor’s return is the difference between the purchase price and the face value. For example, a $100 zero coupon bond is sold as $90. The investment return is $10.
	An investor preferring a long-term investment may purchase zero coupon bonds such as saving money for children’s college tuition.
	The deep discount helps the investor grow a small amount of money into a sizable sum over several years.
	Normally investors buy zero coupon bonds when interest rates are high.

	Valuation
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

	Zero Coupon Bond Price vs Discount Factor
	For a risk-free zero coupon bond with $1 face value, the bond price B(t)=e^(-rT) that is exactly the discount factor.
	In theory, a discount factor is a stochastic variable while a zero coupon bond price is deterministic variable. The bond price is the expectation of the discount factor.
	In practice, however, discount factor and risk-free zero coupon bond price are equivalent.

	Practical Guide
	Intuitively,   e^(-(r+s)T)   can be regarded as a credit risk adjusted discount factor.
	To use the model, one should first calibrate the model price to the market quoted price by solving the credit spread. Comparing to curve construction or calibration for exotic products, the solving here is very simple.
	After making the model price equal to the market price, one can calculate sensitivities by shocking interest rate curve and credit spread.
	We use LIBOR curve plus credit spread rather than bond specific curves for discounting because bond specific curves rarely exist in the market, especially issued by small entities. Using LIBOR curve plus credit spread not only accounts for credit/issuer risk but also solves the missing data issue.

 
	A Real World Example
Buy Sell	Buy
Calendar	NYC
Coupon Type	Zero
Currency	USD
Issue Date	3/2/2017
Maturity Date	8/31/2017
Settlement Date	3/2/2017
Settlement Lag	1
Face Value	100
Pay Receive	Receive


References:


[More details](./FiZeroBond-17.pdf)

[FlipHtml5 zero bond](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamkDM3QjM5ITPkl0av9mY)

[Zenodo zero bond](https://zenodo.org/record/5765447/files/Zenodo-FiZeroBond.pdf)

[archive zero bond](https://ia903403.us.archive.org/28/items/fi-zero-bond-17/FiZeroBond-archive.pdf)

[hcommons zero bond](https://hcommons.org/deposits/download/hc:41724/CONTENT/fizerobond-17.pdf)

[OSF zero bond](https://osf.io/d59wu/download)

[Pub zero bond](https://fixedincome.pubpub.org/pub/xmrfe4fp)




   