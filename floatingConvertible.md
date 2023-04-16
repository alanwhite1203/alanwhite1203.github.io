## Floating Rate Convertible Bond 
   
A convertible bond is a bond with convertible options to the investor such that debt can be converted to the underlying stock in a future date if the stock price performs well. When stock price rises high, the bondholder can ride on the high stock prices and exercise the convertible option. When stock price deteriorates, the bondholder can still receive stable coupon payment if no default occurs.  In general, a convertible bond consists of two components: bond and equity option.  

Floating rate convertible bond pays floating rate coupons, which differentiate itself from the fixed rate convertible bond. The coupon rates are reset periodically based on market reference rates such as LIBOR plus or minus a spread. Similar to other convertible bond types, call and put features may be applied.   

In the implementation, we have call/put features, continuous and discrete dollar dividend features. All these features are tested. 

Following general market pricing practice, pricing of convertible bonds uses lattice trees for the stock price with the interest rate curves static just like pricing a conventional bond. This is the so-called one-factor (stock price) model. The call/put feature of the bond therefore has price effect mainly contributed by the stock price movement rather than the interest rate movement. A two-factor tree model may be considered if the call/put option on bond has considerable weight on the convertible price. 

The tree can be constructed using the standard tree model as discussed in the last subsection without dividend yield. The tree is then modified using the standard approach as described in John Hull (2000).

At each time node prior to the ex-dividend date, the tree remains unchanged. For time nodes after the ex-dividend date, the tree node prices are subtracted by the proportion amount of the dividend yield

With the tree model for stock prices, convertible bonds are valued using the standard tree approach backward from the final time node of the tree, while keeping the interest term structure unchanged. It is known that at the maturity of the bond, the bond pays the redemption value plus the final coupon interest

At any other node before the final time node, the convertible value is the expected value at the next time node, adjusted by credit risk expenses depending on whether the convertible is hedged by an asset swap or a credit default swap


References:

   
[ResearchGate floating convertible pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369881130_Floating_Rate_Convertible_Bond_Model/links/64305ecfad9b6d17dc41399e/Floating-Rate-Convertible-Bond-Model.pdf)
   
[ResearchGate floating convertible](https://www.researchgate.net/publication/369881130_Floating_Rate_Convertible_Bond_Model)

[OSF hw bb](https://osf.io/6dn54/download)

[Bitbucket futures](https://bitbucket.org/timxiao1203/pmfutures/downloads/PreciousMetalFutures.pdf)

[core zero bond pdf](https://core.ac.uk/download/534868225.pdf)

[core zero bond](https://core.ac.uk/works/127933340)
   