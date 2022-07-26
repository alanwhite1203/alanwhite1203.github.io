## Amortizing Bond Valuation


An amortizing bond is a bond whose principal (face value) decreases due to repaying part of the principal along with the coupon payments. Each payment to the amortizing bond holder consists of a portion of interest and a portion of principal. While an accreting bond is a bond whose principal increases during the life of the deal. Each payment to the accreting bond holder is just a part of interest. The other part of coupon is added to the principal of the bond. 

An amortizing bond is used specifically for tax purposes as the amortized principal is treated as part of a company’s interest expense. An accreting bond is used to improve the profit of the existing bond and make it more marketable. Pension funds and insurance companies are major investors in accreting bonds.  This presentation gives an overview of amortizing bonds and accreting bonds. 

	The analytics are similar to a fixed rate bond except the principal amount used for each period may be different. 
	The present value of an amortizing bond or accreting bond is given by
V(t)=∑_(i=1)^n〖cP_i e^(-(r_i+s) T_i )+P_n e^(-(r^n+s) T_n ) 〗
where
	t – valuation date
i – ith cash flow from 1 to n
	r_i – continuous compounded interest rate for period (t,T_i)
T_i – coupon payment date of the ith  cash flow
s – credit spread
P – principal amount or face value
c - coupon rate

	Although investors pay dirty prices, bonds are typically quoted in terms of clean prices. 
Dirty Price = Clean Price + Accrued Interest
	The Yield-To-Maturity Model is a good tool to compute the present value or the fair value of a bond. But it is very difficult to calculate risk, such as term structure sensitivities, that is more important than the fair value in trading, hedging and risk management. Therefore, we introduce the Credit Spread Model for computing both risk and fair value.
	Intuitively,   e^(-(r+s)T)   can be regarded as a credit risk adjusted discount factor.
	To use the model, one should first calibrate the model price to the market quoted price by solving the credit spread. Comparing to curve construction or calibration for exotic products, the solving here is very simple.
	After making the model price equal to the market price, one can calculate sensitivities by shocking interest rate curve and credit spread.

 


References:


[More details](./FiAmortizingBond-9.pdf)

[Zenodo amortizing bond](https://zenodo.org/record/6484737/files/Zenodo-FiAmortizingBond.pdf)

[OSF amortizing bond](https://osf.io/qrc8n/download)

[Zenodo digital](https://zenodo.org/record/6549248)

[Gitbook amortizing bond](https://davidlee1203.gitbook.io/amortizing-bond/)

[github basis](https://github.com/timxiao1203/MoneyMarketBasisCurve)

