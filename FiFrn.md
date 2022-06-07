## Floating Rate Note Valuation

A floating rate note has variable coupons, depending on a money market reference rate, such as LIBOR, plus a floating spread. When interest rate raises, the coupons of an FRN increases in line with the increase of the forward rates, which means its price remains relatively constant. Therefore, FRNs bear small interest rate risk. On the other hand, FRNs carry lower yields than fixed rate bonds of the same maturity. They also have unpredictable coupon payments. 

The price of an FRN has very low sensitivity to changes in interest rates because the floating coupon increases but the discounting also increases as interest rate rises. An investor who wants conservative investments may choose floating rate bonds. FRNs become more popular when interest rates are expected to increase. An FRN carry lower yield than fixed rate bonds of the same maturity and has unpredictable coupon payments. This presentation gives an overview of FRNs valuation. 

Floating Rate Note Introduction
A floating rate note (FRN) is a bond in which the investor will receive coupons paid by the issuer at a floating coupon equivalent to a money market reference rate, such as LIBOR or federal fund rate plus a spread at specified dates before bond maturity.
The bond principal will be returned at maturity date.
Almost all FRNs have quarterly coupons.
FRNs are usually issued by corporations, federal agencies, municipalities and states/provinces to finance a variety of projects and activities. 

The Use of Floating Rate Notes
A FRN carry little interest rate risk as its duration is close to zero due to periodic reset.
The price of a FRN has very low sensitivity to changes in interest rates because the floating coupon increases but the discounting also increases as interest rate rises.
An investor who wants conservative investments may choose floating rate bonds. 
FRNs become more popular when interest rates are expected to increase.
A FRN carry lower yield than fixed rate bonds of the same maturity.
FRNs have unpredictable coupon payments.



Practical Guide
The present value of a bond computed by any pricing models is the dirty price of the bond. To purchase a bond, the buyer pays this dirty price.
Although investors pay dirty prices, bonds are typically quoted in terms of clean prices. 
Dirty Price = Clean Price + Accrued Interest
The Yield-To-Maturity Model is a good tool to compute the present value or the fair value of a bond. But it is very difficult to calculate risk, such as term structure sensitivities, that is more important than the fair value in trading, hedging and risk management. Therefore, we introduce the Credit Spread Model for computing both risk and fair value.
Intuitively,   e^(-(r+s)T)   can be regarded as a credit risk adjusted discount factor.
To use the model, one should first calibrate the model price to the market quoted price by solving the credit spread. Comparing to curve construction or calibration for exotic products, the solving here is very simple.
After making the model price equal to the market price, one can calculate sensitivities by shocking interest rate curve and credit spread.
We use LIBOR curve plus credit spread rather than bond specific curves for discounting because bond specific curves rarely exist in the market, especially issued by small entities. Using LIBOR curve plus credit spread not only accounts for credit/issuer risk but also solves the missing data issue.
Usually the forecasting curve is different from the discounting curve. For instance, the forecasting curve is the treasury curve but the discounting curve is the LIBOR curve plus credit spread.




References:


[More details](./FiFrn-14.pdf)

[FlipHtml5 frn](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamkzM1ITM5ITPkl0av9mY)

[Zenodo frn](https://zenodo.org/record/5765104#.YpU4QsPMKUk)

[archive frn](https://ia903406.us.archive.org/13/items/fi-frn-14/FiFrn-archive.pdf)

[OSF frn](https://osf.io/yrbnh/download)

[Zenodo capped frn](https://zenodo.org/record/6558277#.YpDwUqgpDq4)




