## Fixed Forward Option 
   
The fixed forward call/put contracts are options on forward equity contracts. The option buyer has the right, but not obligation to enter into an equity forward contract, which starts on the expiration date of the option and matures on a later date further into the future.  The fixed forward call/put contracts can be priced using standard option pricing methodologies such as closed form Black-Scholes model or lattice tree model. 

A fixed forward call (put) option is a contract that the option holder has the right, but not obligation, to enter into a forward contract with strike   at a future time  .  The forward contract starts at time   and matures at time  . At the option maturity date, the option holder may or may not exercise the option, all depending whether the forward contract is in the money or out of the money. 

To value the fixed forward call/put option, first one needs to find the value of the forward contract. Suppose at time  , the stock price is  . The value of the forward contract will be  

Consider two cases, (a) the stock pays a continuous dividend such as in the case of a stock index and (b) the stock pays a series of discrete dollar dividends. The forward stock price will be different under the two cases. 

It is clear that the option payoff can be rewritten as a standard equity option, adjusted by the multiplier. Pricing of the options is then similar to pricing an ordinary European option with a modified strike price, and then adjusted by the multiplier. 

Two pricing approaches can be generally used for the forward call/put product, the closed form Black-Scholes formula and the lattice tree model. The Black-Scholes model is straightforward to understand, we will omit the details here. We only explain the details of the lattice tree model.


References:

   
[ResearchGate fixed forward option pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369899083_Fixed_Forward_Option_Model/links/6431c9a9609c170a1302eb82/Fixed-Forward-Option-Model.pdf)
   
[ResearchGate fixed forward option](https://www.researchgate.net/publication/369899083_Fixed_Forward_Option_Model)

[OSF cms spread](https://osf.io/9db5u/download)

[core digital pdf](https://core.ac.uk/download/534871215.pdf)

[core digital](https://core.ac.uk/works/127933862)
   