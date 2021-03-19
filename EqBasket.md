## Equity Basket Option Valuation
 
A Basket Option is an option whose payoff depends on the value of a portfolio or basket of assets. The assets in an equity basket option could be equity indices or individual equities. A basket option can be used to hedge the risk exposure to or speculate the market move on the underlying stock basket. 

A basket option can be used to hedge the risk exposure to or speculate the market move on the underlying stock basket. Because it involves just one transaction, a basket option often costs less than multiple single options. The most important feature of a basket option is its ability to efficiently hedge risk on multiple assets at the same time. Rather than hedging each individual asset, the investor can manage risk for the basket, or portfolio, in one transaction. The benefits of a single transaction can be great, especially when avoiding the costs associated with hedging each and every component of the basket or portfolio.


Buying a basket of shares is an obvious way to participate in the anticipated rapid appreciation of a sector of the stock market, without active management. An investor bullish on a sectr but wanting downside protection may favor a call option on a basket of shares from that sector. A trader who think the market overestimates a basket’s volatility may sell a butterfly spread on the basket. A relatively risk averse investor may favor a basket buy or write. A trader who anticipates that the average correlation among different shares is going to increase might buy a basket option, hedge against a change in volatility by selling options on the component shares, and delta-hedge the remaining exposure to the underlying shares. This presentation gives an overview of equity basket option definition and valuation.


Keywords
Basket option, equity basket option, option, valuation, risk, pricing model


	Equity Basket Option Introduction
	A basket option is a financial contract whose underlying is a weighted sum or average of different assets that have been grouped together in a basket.
	The assets in an equity basket option could be equity indices or individual equities.
	A basket option can be used to hedge the risk exposure to or speculate the market move on the underlying stock basket.
	Because it involves just one transaction, a basket option often costs less than multiple single options.
	The most important feature of a basket option is its ability to efficiently hedge risk on multiple assets at the same time. 
	Rather than hedging each individual asset, the investor can manage risk for the basket, or portfolio, in one transaction. 
	The benefits of a single transaction can be great, especially when avoiding the costs associated with hedging each and every component of the basket or portfolio.

	The Use of Basket Options
	A basket offers a combination of two contracdictory benefits: focus on an investment style or sector, and diversification across the spectrum of stocks in the sector.
	One advantage of Asian options is that these reduce the risk of market manipulation of the underlying instrument at maturity. 
	Another advantage of Asian options is the cheaper price compared to European or American options, because of the averaging feature that reduces the price volatility. 
	Buying a basket of shares is an obvious way to participate in the anticipated rapid appreciation of a sector of the stock market, without active management.
	An investor bullish on a sectr but wanting downside protection may favor a call option on a basket of shares from that sector.
	A trader who think the market overestimates a basket’s volatility may sell a butterfly spread on the basket.
	A relatively risk averse investor may favor a basket buy or write.
	A trader who anticipates that the average correlation among different shares is going to increase might buy a basket option, hedge against a change in volatility by selling options on the component shares, and delta-hedge the remaining exposure to the underlying shares.


	Payoffs
	In a basket option, the payoff is determined by the weighted average prices of the underlying stocks in a basket. This is different from the case of the usual European option and American option, where the payoff of the option contract depends on the price of the only one underlying instrument at exercise. 
	Trading desks use this type of option to construct the payoff structures in various Equity Linked Notes to issue. 
	The payoff for a basket call option is given by

〖Payoff〗_C (T)=N∙P∙max⁡(R-K,0)                                                           
where
R=∑_(i=1)^n▒〖w_i S_i/F_i 〗	the weighted average of the basket return
N	the notional amount
P	the option participation rate
wi	the weight for asset  ,  
Fi	the InitialFixing for asset  ,   
K	the basket percentage strike
Si	the spot price for asset   at time T

	The payoff for a basket put option is given by

〖Payoff〗_P (T)=N∙P∙max⁡(K-R,0)


	Valuation
	The Asian basket option payoff function can be solved either analytically or using sample paths generated with the independent Monte Carlo engine.
	In this paper, we focus on the analytical solution. It assumes that the basket price can be approximated by a lognormal distribution with moments matched to the distribution of the weighted sum of the individual stock prices. The model includes two- and three-moment matching algorithms.
	The model also can be used to price an Asian basket option by including a period of dates in the averaging schedule.
	The payoff types covered by the model include calls and puts, as well as digital calls and digital puts.
	It is well known that the sum of a series of lognormal random variables is not a lognormal random variable. The weighted summation R is approximated by a shifted lognormal random variable (SLN). 

R~SLN=c+d∙exp((Z-a)/b)
where Z~N(0,1) follows a standard normal distribution.

	We solve for   by matching central moments between  .
	The central moments of SLN are

	M_1=c+d∙exp(1/(2b^2 )-a/b)
	M_2=d^2 exp(1/b^2 -2a/b)(exp(1/b^2 )-1)
	M_3=b^3 exp(3/(2b^2 )-3a/b) (exp(1/b^2 )-1)^2 (exp(1/b^2 )+2)

	The solved a, b, c, d are given by


	b=[ln(∛(1+θ/2+√(θ+θ^2/4)) +∛(1+θ/2-√(θ+θ^2/4)) -1)]^(-0.5)
 	θ=(M_3^2)/(M_2^3 )
	d=sign(M_2/M_3 )
a=b∙ln(M_2/M_3 ∙d∙exp(1/(2b^2 ))(exp(1/b^2 )-1)(exp(1/b^2 )+2))
c=M_1-d∙exp(1/(2b^2 )-a/b)



	After some math, we get the present value of a call basket option as

	〖PV〗_C=(c-K)(1-Φ(b∙ln((K-c)/d)+a))D
		+d∙exp(-a/b+1/(2b^2 ))(1-Φ(b∙ln((K-c)/d)+a-1/b))D
	where D is the discount factor.

	Practical Guide
	This model assumes that the basket price can be approximated by a lognormal distribution with moments matched to the distribution of the weighted sum of the individual stock prices.
	The asset value can be accurately expressed using a volatility skew model. This represents best market practice.
	Interest rates are deterministic.
	The model can be easily extended to price an Asian basket option by including a period of dates in the averaging schedule, i.e.,

R=∑_(j=1)^m▒∑_(i=1)^n▒〖w_i 〖W_j S〗_ij/F_i 〗
where Wj is the weight for schedule time  ,  

	A Real World Example

Face Value	87.5
Currency	USD
Digital Rebate	1
Maturity Date	6/16/2017
Call or Put	Call
Buy or Sell	Sell
Position	-21800
Underlying Assets	Initial Fixing
CTXS.O	87.5
LOGM.O	87.5

 
 
 References:
 
  [More details](./EqBasket-3.pdf)
  
  [FlipHtml5 basket option](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamIzMygjM5ITPkl0av9mY)
  
  [Zenodo basket](https://zenodo.org/record/3945086/files/EqBasket-3.pdf)
  
  [Pubpub basket](https://david.pubpub.org/pub/iycnkfjo/download/pdf)
  
  [Github basket](https://github.com/alanwhite1203/EqBasket/raw/master/EqBasket-3.pdf)
  
  [Gitlab basket](https://gitlab.com/finance15/eqbasket/-/raw/master/EqBasket-3.pdf)
  
  [Bitbucket basket](https://bitbucket.org/cmrm11/eqbasket/downloads/EqBasket-3.pdf)
  
  [OSF basket](https://osf.io/cjzba/download)
  
  [Pub basket](https://david.pubpub.org/pub/iycnkfjo/release/1)
  
  [Pub basket pdf](https://david.pubpub.org/pub/iycnkfjo/download/pdf)
  
  [Github basket](https://github.com/alanwhite1203/EqBasket/raw/master/EqBasket-3.pdf)
  
  [gitbook basket](https://captim.gitbook.io/eqbasket/)
 
  [science-media basket](https://science-media.org/userfiles/1020/presentations/1020_presentation_498.pdf)