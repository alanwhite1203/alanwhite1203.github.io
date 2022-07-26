## Reverse Convertible Autocallable Swap
   
A reverse convertible autocallable swap allows two parties exchange floating coupons with fixed coupons on certain future dates. On some coupon dates, the swap may be cancelled. Should the swap be cancelled on coupon date t, the coupons due on coupon date t will be paid and all further cash flows are terminated.

The decision to cancel the option is made based on the performance of an underlying asset, index, or basket of assets. The swap is called if its price at some observation date, relative to its initial price, exceeds the cancellation trigger level. The initial price is averaged over a short period after inception of the deal. This averaged price may be ‘reset’; that is, should the stock price on some ‘reset date’ be lower than the previously averaged price, the initial price is replaced by the price on the reset date.

The fixed coupon can vary between two states: a high coupon and a low coupon. Each coupon date is preceded by a corresponding ‘fixed coupon observation date’, which determines the size of the fixed coupon. If the stock drops below the ‘fixed coupon barrier’ on the observation date, the low coupon will be paid; otherwise, the high coupon is paid instead.

Should the structure remain alive up to maturity, the floating coupon receiver receives a put option on the reference asset. This put option must first be ‘knocked-in’ by the reference asset having fallen below some barrier on one or more of its observation dates.

A reverse convertible bond is a bond with an embedded put option that allows the issuer to purchase the note back for a predetermined quantity of cash, debt, or stock. The decision to exercise the option is made based on the performance of an underlying asset, index, or basket of assets.

The payoff from a simple reverse convertible is defined with respect to the put option strike price and knock‐in barrier level. At maturity, if the return realized on the underlying asset is above the strike, the holder receives the principal. If the underlying asset return is below the strike, the payoff is determined by the status of the barrier – if the barrier was not breached during the monitoring period, the holder receives the principal. However, if a breach did occur, the bond is converted to cash or shares according to the terms defined at inception.
.


References:
   
[More details](./EqReverse-18.pdf)   
   
[Zenodo reverse](https://zenodo.org/record/6480239/files/Zenodo-EqReverse.pdf)
   
[OSF reverse](https://osf.io/y6r57/download)

[gitbook reverse](https://deripricing.gitbook.io/reverse-convertible-autocallable-swap/)

[Zenodo xccy swaption](https://zenodo.org/record/6588375)

[github hw vol](https://github.com/timxiao1203/HullWhiteVolatilityCalibration)
