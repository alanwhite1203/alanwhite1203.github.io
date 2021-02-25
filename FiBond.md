## Fixed Rate Bond

A bond is a debt instrument in which an investor loans money to the issuer for a defined period of time and receives coupons paid by the issuer at fixed interest rate. The bond principal will be returned at maturity date. Bonds are usually issued by companies, municipalities, states/provinces and countries to finance a variety of projects and activities. This presentation gives an overview of fixed rate bonds and also elaborates two valuation models at http://www.finpricing.com/lib/FiBond.html

Fixed rate bonds generally pay higher coupons than interest rates. An investor who wants to earn a guaranteed interest rate for a specified term can choose fixed rate bonds. The benefit of a fixed rate bond is that investors know for certain how much interest rate they will earn and for how long. Due to the fixed coupon, the market value of a fixed rate bond is susceptible to fluctuation in interest rate and therefore has a significant interest rate risk. 

There are two types of bond valuation models in the market: yield-to-maturity model and credit spread model. 

A fixed rate bond is a debt instrument in which an investor loans money to the issuer for a defined period of time and receives coupons paid by the issuer at fixed interest rate. The bond principal will be returned at maturity date. Bonds are usually issued by companies, municipalities, states/provinces and countries to finance a variety of projects and activities. This presentation gives an overview of fixed rate bonds and also discusses two valuation models. 



Bond, fixed rate bond, fixed income security, coupon, face value, dirty price, clean price, yield-to-maturity valuation model, credit spread valuation model

	Fixed Rate Bond Introduction
	A bond is a debt instrument in which an investor loans money to the issuer for a defined period of time. 
	Over the life of a fixed rate bond, the investor will receive coupons paid by the issuer at a predetermined  interest rate at specified dates before bond maturity.
	The bond principal will be returned at maturity date.
	A fixed rate bond is usually a long term paper.
	Bonds are usually issued by companies, municipalities, states/provinces and countries to finance a variety of projects and activities. 

	The Use of Fixed Rate Bond
	Fixed rate bonds generally pay higher coupons than interest rates.
	An investor who wants to earn a guaranteed interest rate for a specified term can choose fixed rate bonds. 
	The benefit of a fixed rate bond is that investors know for certain how much interest rate they will earn and for how long.
	Due to the fixed coupon, the market value of a fixed rate bond is susceptible to fluctuation in interest rate and therefore has a significant interest rate risk.
	The long maturity schedule and fixed coupon rate offers an investor a solidified return.
	The real value of a fixed rate bond is also susceptible to inflation rate given its long term.

	Valuation: Yield-to-Maturity Approach
	There are two types of bond valuation models in the market: yield-to-maturity model and credit spread model.
	The present value of a bond under the yield-to-maturity model is given by
V(t)=∑_(i=1)^n▒〖cP/(1+y)^i +P/(1+y)^n 〗
where
	t – the valuation date
P – the principal amount or face value
y – the yield to maturity
c – the coupon rate
i – the ith cash flow or coupon from 1 to n

	Valuation: Credit Spread Approach
	The present value of a fixed rate bond under the credit spread model can be expressed as
V(t)=∑_(i=1)^n▒〖cPe^(-(r_i+s) T_i )+Pe^(-(r^n+s) T_n ) 〗
where
	t – the valuation date
i – the ith cash flow from 1 to n
	r_i – the continuous compounded interest rate for period (t,T_i)
T_i – the coupon payment date of the ith  cash flow
s – the credit spread
P – the principal amount or face value
c – the coupon rate

	Practical Guide
	The present value of a bond computed by any pricing models is the dirty price of the bond. To purchase a bond, the buyer pays this dirty price.
	Although investors pay dirty prices, bonds are typically quoted in terms of clean prices. 
Dirty Price = Clean Price + Accrued Interest
	The Yield-To-Maturity Model is a good tool to compute the present value or the fair value of a bond. But it is very difficult to calculate risk, such as term structure sensitivities, that is more important than the fair value in trading, hedging and risk management. Therefore, we introduce the Credit Spread Model for computing both risk and fair value.
	Intuitively,   e^(-(r+s)T)   can be regarded as a credit risk adjusted discount factor.
	To use the model, one should first calibrate the model price to the market quoted price by solving the credit spread. Comparing to curve construction or calibration for exotic products, the solving here is very simple.
	After making the model price equal to the market price, one can calculate sensitivities by shocking interest rate curve and credit spread.
	We use LIBOR curve plus credit spread rather than bond specific curves for discounting because bond specific curves rarely exist in the market, especially issued by small entities. Using LIBOR curve plus credit spread not only accounts for credit/issuer risk but also solves the missing data issue.

 
	A Real World Example

Buy Sell	Buy
Calendar	NYC
Coupon Type	Fixed
Currency	USD
First Coupon Date	11/15/1988
Interest Accrual Date	5/15/1988
Issue Date	5/16/1988
Last Coupon Date	11/15/2017
Maturity Date	5/15/2018
Settlement Lag	1
Face Value	100
Pay Receive	Receive
Day Count	dcActAct
Payment Frequency	6M
Coupon	0.09125


References:
 
[More details](./FiBond-10.pdf)
 
[Check](https://finpricing.com/lib/FiBond.html)  
 
[FlipHtml5 bond](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamcDM0cjNyETPkl0av9mY)
 
[Zenodo bond](https://zenodo.org/record/3958026/files/FiBond-10.pdf)
 
[Pubpub bond](https://fixedincome.pubpub.org/pub/j5k0ljcd/download/pdf)
 
[Github bond](https://github.com/alanwhite1203/fiBond/raw/main/FiBond-10.pdf)
 
[Gitlab bond](https://gitlab.com/finance15/fibond/-/raw/master/FiBond-10.pdf)
 
[Bitbucket bond](https://bitbucket.org/cmrm11/fibond/downloads/FiBond-10.pdf)
 
[OSF bond](https://osf.io/gtcma/download)

[Pub bond](https://fixedincome.pubpub.org/pub/j5k0ljcd/release/1)

[Pub bond pdf](https://assets.pubpub.org/f1rpbaty/21596458284937.pdf)

[Github bond](https://github.com/alanwhite1203/fiBond/raw/main/FiBond-10.pdf)
