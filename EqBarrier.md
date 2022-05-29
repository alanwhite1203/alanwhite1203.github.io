## Barrier Option Valuation
   
Barrier options are set up conditionally, so that within the life of the option, a barrier may or may not be reached. The barrier option is dependent on an “extreme” price, either high or low, attained by the underlying. If a barrier is reached, or touched, the constraints are triggered.

The two types of contracts, knock-in barrier options and knock-out barrier options, each respond differently when the barrier is "triggered". If a knock-out option's underlying touches the barrier, the option is eliminated and the holder receives a rebate. Conversely, a knock-in option touches the barrier to activate the option. If the knock-in option never reaches the barrier, the holder will receive a rebate.

For single barrier option, there are four possible variations to the barrier:
•	Up and In
•	Up and Out
•	Down and In
•	Down and Out
The option is considered knocked-in (knocked-out) if, on a barrier observation date, the underlying asset’s closing price exceeds (for up-barriers) or falls below (for down-barriers) the barrier level corresponding to that observation date.

Once knocked-in (knocked-out), the option’s status is no longer subject to further modification by subsequent barrier observation events. Payoff at maturity may take the form of a Call, Put or Note. The payoff is contingent on the option having been knocked in (in the case of knock-in option), or having not been knocked out (in the case of a knock-out option), on some barrier observation date prior to maturity.

For European barrier options, a vanilla option is equal to the sum of the premiums for a knock-in and its corresponding knockout (assuming no rebates and equivalent input parameters). Since at expiration, only one option can have a value. 

The Double Barrier is a discretely-observed barrier option on a single asset. An initial stock price can be fixed at some future date. The option is said to be triggered when the stock price, relative to its initial price, exceeds the high barrier or falls below the low barrier on any barrier observation date. 

The option may be Knock-In (where triggering enables the payoff) or Knock-Out (where triggering disables the payoff). For Knock-Out options, a rebate amount may be specified to be paid if the option becomes triggered. The payoff at maturity, if active, may be a relative-return call or put payoff on the deal Notional.

An average Barrier is a call or put option on the average of the asset level over a discrete set of observation dates, with a knock-in or knock-out barrier applied to the running average on a subset of those dates.

More precisely, the option is said to be triggered when the running average of the asset price exceeds the high barrier or falls below the low barrier on any barrier observation date. In the case of a knock-in barrier, the buyer of the option receives the call/put payoff at maturity if the option has been triggered, and receives zero otherwise.  In the case of knock-out barrier, the buyer receives the call/put payoff at maturity if the option was not triggered during the lifetime of the deal, while the buyer receives a knock-out rebate (at the barrier date or at maturity) if the option is triggered.

The option is said to be triggered when the asset level exceeds the high barrier or falls below the low barrier at any time within a barrier observation interval (or on a barrier observation date). 

The option may be Knock-In (where triggering enables the payoff) or Knock-Out (where triggering disables the payoff). For Knock-Out options, a rebate amount may be specified to be paid if the option becomes triggered. The payoff at maturity, if active, may be a call, a put, a digital call, or a digital put payoff on the deal Notional. 

In-out parity
There are some relationships among knock-in, knock-out, and vanilla options.



References:
   
[More details](./EqBarrier-11.pdf)     
   
[Zenodo barrier](https://zenodo.org/record/5759655#.YpPJoMPMKUk)
   
[OSF barrier](https://osf.io/ymt8n/download)

[hcommons barrier](https://hcommons.org/deposits/download/hc:38410/CONTENT/eqbarrier-11.pdf)

[gitbook barrier](https://deripricing.gitbook.io/barrier-option-pricing/)

[science-media barrier](https://science-media.org/userfiles/1020/presentations/1020_presentation_508.pdf)