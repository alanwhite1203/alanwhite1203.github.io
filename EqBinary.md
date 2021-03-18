## Binary Option
   
A binary option is an option with a predetermined payoff, triggered only if the underlying price meets the strike price. These are also commonly referred to as “all or nothing” or “digital options”. Binary call pays a fixed amount if the underlying price ends up above the strike price, while binary put pays off a fixed amount if the underlying price is below the strike price at option maturity.

The payoff of a digital option or binary option is either some fixed amount of some asset or nothing at all. The two main types of binary options are the cash-or-nothing binary option and the asset-or-nothing binary option. The cash-or-nothing binary option pays some fixed amount of cash if the option expires in-the-money while the asset-or-nothing pays the value of the underlying security.

For a call, the underlying price must be higher than the strike at expiry to trigger the rebate or receipt of the underlying. For a put, the underlying price must be lower than the strike at expiry to trigger the rebate or receipt of the underlying. 

The risk sensitivities, especially Gamma, may be unstable when at the money or near the exercise date due to the discontinuous property inherent in digital option. Risk sensitivities become less meaningful near discontinuities and kinks. As Vega may change signs near the strike, it is probably difficult to create a conservative estimate of the volatility.

Binary options can be valued using the Black-Scholes models. The PV is calculated as the product of fixed payment times call price (c) or put price (p) where:

Cash-or-nothing:
 
 
Asset-or-nothing:
 
 
where
d_1=(ln⁡(s/x)+(r+σ^2/2)t)/(σ√t)
 
       and
s is the current spot price
r is the risk free interest rate
t is the expiry date in years
σ is the implied volatility
Φ is the standard normal cumulative distribution function

The risk sensitivities, especially Gamma, is very unstable under the Black-Scholes. Therefore, the better solution is to represent a binary option as a tight option spread.



References:
   
[More details](./EqBinary-13.pdf)     
   
[FlipHtml5 binary](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamEjN4ETO3MTPkl0av9mY)
   
[Zenodo binary](https://zenodo.org/record/4615284/files/EqBinary-13.pdf)
   
[Pubpub binary](https://david.pubpub.org/pub/t9j3lz67/release/1)
   
[OSF binary](https://osf.io/e9u46/download)

[Pub binary pdf](https://assets.pubpub.org/di341tvq/21616078998541.pdf)

[Github binary pdf](https://github.com/alanwhite1203/EqBinary/releases/download/1/EqBinary-13.pdf)  