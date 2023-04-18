## Futures Fair Value 
   
We developed a pricing model to calculate unwinding values of equity forward with dividend reinvestment.

The term ‘value’ of forward contract refers the unwinding value of the forward hereinafter. 

In general, owner of a forward contract does not receive dividends paid before the maturity of the contract. For simplicity in illustration, let us assume that there is only one dividend payment with amount D and payment date  . If the contract specifies that dividends will be reinvested and paid at maturity (DIV_REINVEST_IND set to YES), the dividend is invested by buying  shares of the underlying stock on the dividend payment date. Thus, forward contract owner gets  extra shares of stock at the maturity.  Thus, with zero settle date lag, the contribution of this dividend at time t should be  

For the quanto case, suppose the stock is in Canadian dollars and the forward contract is quantoed into US Dollars.  The forward contract value with the reinvestment adjustment is

The equations (4) and (5) can be generalized with multiple dividends and non-zero settle date lag as the following. For non-quanto case, let Pay be the contract payoff currency (= underlying currency) and Div the dividend currency, then we have

REI(Div) is the present value of the dividend reinvestment whose payment dates lie between the valuation date and the maturity date. The dividend that will go ex before maturity and be payable after maturity will not be invested. Rather, the cash (dividend) amount will be paid to the holder directly and, thus, only the discounted value at maturity T should be considered. It should be noted that this dividend amount should be discounted using the forward interest rate of the payoff currency.  


References:

   
[ResearchGate reinvestment pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369899100_Equity_Forward_with_Dividend_Reinvestment/links/6431d2e0609c170a1302ebe1/Equity-Forward-with-Dividend-Reinvestment.pdf)
   
[ResearchGate reinvestment](https://www.researchgate.net/publication/369899100_Equity_Forward_with_Dividend_Reinvestment)

[OSF quanto trs](https://osf.io/p7kn4/download)

[gitbook intraday](https://cmrm11.gitbook.io/intraday-replacement-risk/)

[core tree pdf](https://core.ac.uk/download/534871193.pdf)

[core tree](https://core.ac.uk/works/127931199)
   