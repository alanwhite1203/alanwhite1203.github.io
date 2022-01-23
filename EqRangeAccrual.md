## Callable Range Accrual Valuation

FinPricing provides valuation models for
	Equity Range Accrual Note
	Callable Equity Range Accrual Note
	Libor Range Accrual
	Callable Libor Range Accrual Note

Range accrual products can be categorized as interest rate range accrual, equity range accrual, and FX range accrual. 

A LIBOR range accrual swap is an interest rate swap where in the payoff is dependent on the reference rate (LIBOR) falling within a particular range. A callable LIBOR range accrual swap is a LIBOR range accrual swap in which the party paying the coupon (structured) leg has the right to cancel on any coupon date after a lock-out period expires.

An equity range accrual note is a principal-protected note that pays out a series of coupons based on the performance of an underlying stock, index, or basket of assets. The holder receives these coupons on a set of scheduled payment dates, but only if the value of the underlying asset on that date is between a lower and upper threshold. More specifically, at each observation date, a coupon is accrued and added to the total accrued coupon for that period. When a coupon determination date is reached the total accrued coupon is paid and is reset to zero for the next period. As such, the coupons are effectively a series of digital-style options that pays a fixed amount when the asset price is within the specified range.

A callable range accrual note contains an embedded option that allows the issuer to exercise a call on the note on a particular date or set of dates prior to maturity. This can be used by the issuer to limit the return that is paid to the note holder. On these exercise dates, the issuer may purchase the note back from the holder for a predetermined cash amount, which is typically equal to or greater than the face value of the note. 

For example, a callable range accrual with 5 business days notice can be called on any coupon date, starting on the third anniversary, provided the appropriate notice is given 5 days before the coupon date.
When a call is exercised on a coupon payment date, the coupon for that date is still paid to the holder.

There must be at least one coupon determination date that must be equal to the last observation date. The coupon accrues by some deterministic rate on specified Observation Dates whenever the level of the reference underlying closes either 
	A) inside a specified range on an observation date, or 
	B) outside of that range.
 
If Recall Dates are specified, the issuer has the option of recalling the option at these dates in exchange for the corresponding, pre-determined recall price.

The product can be structured as a note, in which case the issuer pays the note holder the Notional amount at maturity. In the case of a callable note, exercising the recall feature cancels the redemption of Notional at maturity; hence the recall prices should include the Notional amount to be returned. 

Due to the complexity of the product, the note is normally priced via Monte Carlo simulation. 



References:

[More details](./EqRangeAccrual-27.pdf)

[Zenodo range accrual](https://zenodo.org/record/4683873/files/EqRangeAccrual-27.pdf)

[Pubpub range accrual](https://david.pubpub.org/pub/lodsaaco/release/1)

[archvie range accrual](https://ia903407.us.archive.org/23/items/eq-range-accrual-27/EqRangeAccrual-archive.pdf)

[OSF range accrual](https://osf.io/476gc/download)

[hcommons range accrual](https://hcommons.org/deposits/download/hc:41502/CONTENT/eqrangeaccrual-27.pdf)

[gitbook range accrual](https://davidlee1203.gitbook.io/callable-range-accrual-note/)

[science-media range accrual](https://science-media.org/userfiles/1020/presentations/1020_presentation_524.pdf)