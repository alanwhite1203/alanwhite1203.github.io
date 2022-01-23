## Callable Exotics Valuation
   
A callable note allows the issuer to exercise a call option on the note on a specified date or set of dates prior to maturity.

Callable note or callable exotics are among the most challenging derivatives to price. These products are loosely defined by the provision that the holder or issuer has the right to call the product or exercise into various underlying instruments after a lock-out period expires.

There are several popular types of callable exotics

1.	Callable (basket) options
A callable option is a European option (Call, Put, Binary Call, Binary Put) option with a provision that the issuer has the right to recall the note on pre-determined dates for a pre-determined price.

The option may be structured as a note where the principal amount is collated upfront and return at maturity, or upon early recall. The option can be based on single name or a basket.

A management fee may be charged in which a fee accrues on the periodically observed level of the asset (or basket). The fee is applied as a reduction of the value of the reference asset (or basket) level used to compute the final payoff at maturity.

2.	Callable range accrual
A range accrual note is a principal-protected note that pays out a series of coupons based on the performance of an underlying stock, index, or basket of assets. The holder receives these oupons on a set of scheduled payment dates, but only if the value of the underlying asset on that date is between a lower and upper threshold. As such, the coupons are effectively a series of digital-style options that pay a fixed amount when the asset price is within the specified range.

The Range Accrual structure pays an accrued coupon on one or more Coupon Dates. More specifically, at each observation date, a coupon is accrued and added to the total accrued coupon for that period. When a coupon determination date is reached the total accrued coupon is paid and is reset to zero for the next period. There must be at least one coupon determination date that must be equal to the last observation date. The coupon accrues by some deterministic rate on specified Observation Dates whenever the level of the reference underlying closes either 
	A) inside a specified range on an observation date, or 
	B) outside of that range.

A callable range accrual note contains an embedded option that allows the issuer to exercise a call on the note on a particular date or set of dates prior to maturity. This can be used by the issuer to limit the return that is paid to the note holder. The exercise dates may correspond to some, but not necessarily all, of the coupon payment dates. On these exercise dates, the issuer may purchase the note back from the holder for a predetermined cash amount, which is typically equal to or greater than the face value of the note (a premium is often paid to compensate the holder for the call option). When a call is exercised on a coupon payment date, the coupon for that date is still paid to the holder. 

The product can be structured as a note, in which case the issuer pays the note holder the Notional amount at maturity. In the case of a callable note, exercising the recall feature cancels the redemption of Notional at maturity; hence the recall prices should include the Notional amount to be returned. 

3.	Autocallable note
An autocallable notes are usually issued on a basket of stocks. It may contain auto call provision, range accrual provision, and maturity barrier provision. All the provisions are based on basket levels. These levels can be independent of each other.

For instance, an autocallable yield generator note that provides periodic coupons that are linked to the performance of a basket of equities. There is a knock-out barrier level for the total coupon amount; if reached, the notional is returned and the deal is cancelled.

4.	Reverse convertible autocallable swap
There are several swap dates. On each swap date, two parties exchange a floating coupon with a fixed coupon. On certain coupon dates, the swap may be cancelled. Should the swap be cancelled on coupon date t, the coupons due on coupon date t will be paid and all further cash flows are terminated.

Cancellation is based on a single reference asset. The swap is called if its price at some observation date, relative to its initial price, exceeds the cancellation trigger level. The initial price is averaged over a short period after inception of the deal. This averaged price may be ‘reset’; that is, should the stock price on some ‘reset date’ be lower than the previously averaged price, the initial price is replaced by the price on the reset date.

The fixed coupon can vary between two states: a high coupon and a low coupon. Each coupon date is preceded by a corresponding ‘fixed coupon observation date’, which determines the size of the fixed coupon. If the stock drops below the ‘fixed coupon barrier’ on the observation date, the low coupon will be paid; otherwise, the high coupon is paid instead.

Should the structure remain alive up to maturity, the floating coupon receiver receives a put option on the reference asset. This put option must first be ‘knocked-in’ by the reference asset having fallen below some barrier on one or more of its observation dates.

Callable valuation is based on numeric approaches, such as FPE or Monte-Carlo.


References:
   
[More details](./EqCallable-15.pdf)     
  
   
[Zenodo callable](https://zenodo.org/record/5759660/files/Zenodo-EqCallable.pdf)
   
[Pubpub callable](https://david.pubpub.org/pub/qeg8gemk/release/1)
   
[OSF callable](https://osf.io/khrcb/download)

[archive callable](https://ia803403.us.archive.org/32/items/eq-callable-15/EqCallable-archive.pdf)  

[hcommons callable](https://hcommons.org/deposits/download/hc:38496/CONTENT/eqcallable-15.pdf)