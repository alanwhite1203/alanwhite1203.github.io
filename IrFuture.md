## Interest Rate Futures Valuation
   
An interest rate future is a futures contract between the buyer and seller to deliver an interest bearing asset, that allows the buyer and seller to lock in the price of the interest bearing asset for a future date. The most popular interest rate future is Eurodollar future.

Eurodollar futures contract is a cash-settled futures contract. The underlying instrument in Eurodollar futures is a Eurodollar time deposit having a principal value of $1,000,000 with a three-month maturity. Eurodollar futures prices are expressed numerically using 100 minus the implied 3-month U.S. dollar LIBOR interest rate. In this way, a Eurodollar future price of $98 reflects an implied settlement interest rate of 2%.

	Interest rate futures are used to hedge against interest rate risk. Investors can use Eurodollar futures to secure an interest rate for money it plans to borrow or lend in the future. Interest rate futures are mainly listed for 3-month Eurodollar, 1-month LIBOR, 1-month banker’s acceptance futures and 3-month banker’s acceptance futures.


The price of an interest rate future is quoted by the exchange. A model is mainly used for calculating sensitivities and managing market risk.

The present value of an interest rate future is given by
PV(t)=n(F_T-F_0 )
where
	F_T=100-y(t:T,T_u) – future contract price at the valuation date
	t – valuation date
	T – maturity date of the future contract
	T_u – maturity date of the underlying rate, usually T_u=T+3month
	y(t:T,T_u ) – annually compounded forward yield for forward period (T, T_u)
	n – contract size
	F_o – quoted future contract price at the trade date T_0, T_0≤t≤T





References:

   
[More details](./IrFuture-34.pdf)
   
[Zenodo futures](https://zenodo.org/record/5771055/files/Zenodo-IrFuture.pdf)
   
[OSF futures](https://osf.io/j9apv/download)

[Fliphtml5 futures](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamIDO5UjM5ITPkl0av9mY)

[Zenodo sheet](https://zenodo.org/record/6548879)

[github mbs](https://github.com/cfrm17/DigitalAdjustments)

