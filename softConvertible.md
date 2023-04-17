## Convertible Bond Model with Soft Call
   
A convertible bond is a coupon paying corporate bond that can be converted into company stock at the discretion of the holder. Pricing convertible bond is a challenging task, because it is a hybrid instrument with an equity component and a bond component. 

These two components are subject to different credit risk, because a company can always issue more of its stock, but not necessarily come up with sufficient cash to meet bond obligations. Furthermore, in reality, even the most basic convertible bonds often incorporate various additional features, such as call and put provisions, strike reset features, mandatory or restricted conversion, etc.

We developed and implemented a pricing model for convertible bonds using the semi-continuous tree method.  Either ex-dividend or cum-dividend processes for stock price movement can be employed.  

For stocks with discrete dollar dividends, the ex-dividend process for stock price dynamics treats dividends as a riskless component, and reduces the spot stock price by the present value of all the dividends during the life of the contract.  At each dividend payment date, the present value of future dividends is added back to the stock price.  While with the cum-dividend process, the stock price is considered random, but jumps down by the amount of dividend at each ex-dividend date.  Although the ex-dividend process is classical and widely used, the cum-dividend process has gained popularity in recent years.

The convertible bond issuer can call the bond back at a given call amount and at a specified time period only when the underlying stock price goes beyond a pre-specified barrier.  If the barrier is zero, this call becomes a hard call (unconditional call).  On the other end, if the barrier is considerably high, it is as if there is no call at all.  We use a smoothing technique when dealing with convertible bond with soft call under the semi-continuous tree method.  Its effectiveness and limitation have been investigated.

The semi-continuous tree model treats the possible prices of the underlying stock as continuous but adopts an adaptive discrete time stepping that allows the treatment of discrete dividends and coupon payments and discrete time schedules for conversion and call and put features in an efficient way.


References:

   
[ResearchGate soft convertible pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369898784_Convertible_Bond_Model_with_Soft_Call/links/6431a429ad9b6d17dc44cea0/Convertible-Bond-Model-with-Soft-Call.pdf)
   
[ResearchGate soft convertible](https://www.researchgate.net/publication/369898784_Convertible_Bond_Model_with_Soft_Call)

[OSF hw vol](https://osf.io/k3wc9/download)

[Bitbucket model](https://bitbucket.org/timxiao1203/dividendmodel/downloads/DividendModel.pdf)

[core callable bond pdf](https://core.ac.uk/download/534868178.pdf)

[core callable bond](https://core.ac.uk/works/127932547)
   