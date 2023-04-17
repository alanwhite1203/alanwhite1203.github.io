## Generic FX Option 
   
We present a generic FX option model that allows currency as a random object type. The main implication is that European and Asian FX (foreign exchange) options can now be priced. 

The underlying asset in a FX option contract is a number of units of some foreign currency. Let time 0 be the current valuation time, and   be the current spot price, measured in domestic currency, of one unit of the foreign currency (also called spot FX rate). Let   be the forward price (forward FX rate) for maturity T, measured in domestic currency, of one unit of the foreign currency. It is the fair strike price that makes the value of the contract 0 at time 0. 

Using Black-Scholes-Merton (BSM) assumptions, that is taking the expectation of the payoff under a forward risk neutral measure with respect to a domestic zero-coupon bond maturing at T 

There are two different pricing methodologies: Monte Carlo (MC, QMC) and closed form. Discretizing the original SDE, in the Monte Carlo simulation the essential step is:

We test the model in two cases: European and Asian FX options. The attribute terminology is borrowed from equity options, but the mapping is obvious: in particular the dividend file acts as foreign zero interest rate file. The cases studied can be obtained by commenting and uncommenting out the corresponding attributes. 


References:

   
[ResearchGate fx pdf](https://www.researchgate.net/profile/Tim-Xiao/publication/369899218_Generic_FX_Option_Model/links/6431bab4ad9b6d17dc44d429/Generic-FX-Option-Model.pdf)
   
[ResearchGate fx](https://www.researchgate.net/publication/369899218_Generic_FX_Option_Model)

[OSF gic](https://osf.io/tgd82/download)

[OSF bond American](https://osf.io/dt69v/download)

[core autocallable pdf](https://core.ac.uk/download/534868143.pdf)

[core autocallable](https://core.ac.uk/works/127933271)
   