## Cliquet Option Valuation
   
A cliquet option, also called ratchet option, consists of a series of forward start options, each struck at the money on the date it becomes active. Typically, each option begins on the date corresponding to the expiry of the previous option. The cliquet is a series of at-the-money options, with periodic settlement, resetting the strike value at the then current price level, at which time, the option locks in the difference between the old and new strike and pays that out as the profit. The profit can be accumulated until final maturity, or paid out at each reset date.

Cliquet options are widely traded in many retail-structured products. They consist of financial derivatives which provide a guaranteed minimum return in exchange for a capping of the maximal return over the life of the contract. A cliquet option is equivalent to a series of forward-starting at-the-money options, which may be globally and locally floored and capped. 

Cliquet options are appealing to investors because they can protect themselves against downside risks. Possible variants include reverse cliquet which amounts to a cash flow minus a capped cliquet of puts, and digital cliquet, where the forward-starting options are digital options.

The Cliquet option may have an optional Lock feature, that pays at maturity a Total Coupon equal to a guaranteed Coupon plus the sum (the Coupon Sum) of a series of Weighted Individual Coupons, where this Coupon Sum is subject to both a Global Floor and a Global Cap. 

The Weighted Individual Coupons are calculated as an Individual Coupon times an Individual Participation Rate, then subject to an Individual Coupon Cap and Individual Coupon Floor adjustment, and finally multiplied by an Individual Weight Factor.  The Individual Coupon amount is the return of the underlying asset over and above a specified Individual Strike for the individual period.  Note that each “Individual” parameter (Participation Rate, Coupon Cap, Coupon Floor, Weight Factor, Strike) can be specified uniquely for each period.  

The Lock feature allows the specification of, effectively, a variable Global Floor which is determined by (but not necessarily equal to) the maximum value, over the life of the deal, of the Cumulative Sum to date.  See below for details.

Compound cliquets are also popular. A compound cliquet is an option on a cliquet option. The lifetime of a compound cliquet is divided into K periods. The product payoff in each period is determined by the excess return above a local hurdle k h , and constraint by a local cap k c and a local floor k f . A CC accumulates all these payoffs at the expiry date with no compounding. At expiry, the total payoff depends on the excess return above a global hurdle h . It may also be constraint by a global cap c and a global floor f .

The lifetime of a Compound Cliquet is divided into K periods that are defined by the expiry dates of the options contained in the underlying cliquet. The product payoff in each of these periods is determined by the rate of return on the underlying asset during that time interval. Specifically, the payoff in the kth period (where 1 ≤ k ≤ K) depends on the excess return realized above a local hurdle, hk

As the Compound Cliquet matures, the payoff for each period accumulates with no compounding. At expiry, the total payoff is found by applying the excess accumulated return above the global hurdle, h, to the face value of the option, A. The total payoff may also be constrained by a global cap, c, and floor, f. Given this payoff structure, the Compound Cliquet product can be viewed as a cliquet option with a modified payoff wrapped inside a principal protection option.

The Compounding Compound Cliquet product is also an option on a cliquet option involving a single underlying asset. In this case, the total return that is applied to the face value of the option at maturity is found by compounding the payoff from each period.

Cliquets are volatility-sensitive products. A good volatility model not only has to be able to calibrate to the spot implied volatilities but also to the forward start options.


References:
   
[More details](./EqCliquet-12.pdf)     
   
[Zenodo cliquet](https://zenodo.org/record/4609253#.YpPNDMPMKUk)
   
[OSF cliquet](https://osf.io/swbg4/download)

[gitbook cliquet](https://deripricing.gitbook.io/cliquet-option-valuation/)

[github American](https://github.com/timxiao1203/AmericanBondOption)

