## Bond Futures Valuation
 
A bond future is a future contract in which the asset for delivery is a government bond. Any government bonds that meet the maturity specification of a future contract are eligible for delivery. All eligible delivery bonds construct the delivery basket where each bond has its own conversion factor. Conversion factors are used to equalise the coupon and accrued interest differences of all the deliverable bonds. 

The seller usually picks up the cheapest bond in the basket to deliver, called the cheapest-to-deliver (CTD). The CTD bond is normally delivered on the last delivery day of the month. 

Bond futures are exchange-traded with maturities of 2, 5, 10, 30 years, where the typical underlings are treasury notes or bonds. There are established global markets for bond futures. Bond futures provide a liquid alternative for managing interest rate risk. 

Investors use bond futures to hedge an existing bond portfolio against adverse interest rate movements or enhance the long-term performance of the portfolio. Arbitrageurs profit from the price difference between the spot bonds and the bond futures. Speculators use bond futures in the hope of making a profit on short-term movements in prices. This presentation provides an overview of bond future product and valuation. 


The present value of a bond future contract is represented as: 


PV(t)=nN((F_B (t,T))/CF-K)exp⁡(-t_T T)/100
where
	      t 	the valuation date
K	the delivery price
n	the number of contracts
N	the amount value for the bond future
F_B (t,T)=(P-C_Σ )  exp⁡(r_T T)-A   	the forward clean price of the delivered bond (CTD) at t
P	the bond dirty price at t
T	the future maturity date
   	the conversion factor for a bond to deliver in a bond futures contract
	       r_T		the continuously compounded interest rate between t and T
		       C_Σ=∑_(t_i≤T)〖Cexp(-r_i t_i)〗		the present value sum of all coupons of the 
underlying bond between t and T
	       A		the accrual interest before T.



	The key for pricing a bond future is to compute the forward clean bond price.
	The forward clean bond price is equal to the forward price of the underlying bond price at today t plus some coupon and accrual interest adjustment.

P exp⁡(r_T T)   is the forward price of the bond price P at t.

	〖C_Σ exp〗⁡(r_T T) 
	
is the forward price of all coupons between t and T. Those coupons should be excluded from the forward bond price at T.

	A is the accrual interest before.
	Bond clean price = bond dirty price – accrual interest



References:

[More details](./FiBondFuture-11.pdf)

[Zenodo bond futures](https://zenodo.org/record/6480530/files/Zenodo-FiBondFuture.pdf)

[OSF futures](https://osf.io/2vzq8/download)

[Fliphtml5 futures](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamMDO1gDM5ITPkl0av9mY)

[Zenodo knockout](https://zenodo.org/record/6551223)

[Gitbook bond futures](https://cmrm11.gitbook.io/bond-futures/)

[github black](https://github.com/timxiao1203/BlackOptionModel)



