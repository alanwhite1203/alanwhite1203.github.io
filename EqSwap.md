## Equity Swap Valuation
   
An equity swap is an OTC contract between two parties to exchange a set of cash flows in the future. Normally one party pays the return based on capital gains and dividends realized on an equity security and the other party pays the return based on a floating interest rate plus a spread. 

An equity swap can be used to transfer both the credit risk and the market risk of an underlying asset. Equity swaps can be also used to avoid transaction costs (including Tax), to avoid locally based dividend taxes, limitations on leverage (notably the US margin regime) or to get around rules governing the particular type of investment that an institution can hold. Equity swaps can make investment barriers vanish and help an investor create leverage. 

Equity swaps allow parties to potentially benefit from returns of an equity security without the need to own its shares. In general, a party enters an equity swap with the objective of either obtaining return exposure or hedge existing equity risk for a period of time. 

The two cash flows are usually referred to as "legs" of the swap. The leg referred to as the floating leg is pegged to a floating rate such as LIBOR. The other leg of the swap referred to as the equity leg is based on the performance of either a share of individual stock or stock index. 

The party receiving the total returns gains exposure to the performance of the reference asset without actually owning the asset; hence this instrument can be used to obtain a leveraged exposure. On the other hand, the party receiving payments based on the reference rate receives protection against a loss in the value of the underlying equity. Unlike other swap types, the equity swap notional resets on each cash flow reset date, depending on the performance of the underlying asset.

Equity swaps allow parties to potentially benefit from returns of an equity security without the need to own its shares. In general, a party enters an equity swap with the objective of either obtaining return exposure or hedge existing equity risk for a period of time. This presentation gives an introduction to equity swap product and valuation. 


	There are two legs in an equity swap: an equity leg and a floating interest leg. 
	The payoff for both legs could be set at every reset date or at maturity; or could be one side at maturity and the other at every reset date. 
	The price of the swap is the difference between the present values of both legs' cash flows. In other words, the present value of swap is net of present value of "equity leg" and "money market leg".

The present value of an equity leg is given by
〖PV〗_equity (t)=N∑_(i=1)〖[(S_i-S_(i-1))/S_(i-1) ] D_i 〗
where
	t   –  the valuation date
	N  – the notational principal amount
	i  –  the ith cash flow from 1 to n
	D_i=D(t,T_i)  –  the discount factor
S_i=[S-〖PV〗_i (D)] e^(r_i (T_i-t) )   - the equity forward price
	S – the equity spot price at valuation date
	〖PV〗_i (D)=∑_(t<τ<T_i)〖d_τ e^(-r_τ (τ-t) ) 〗   - the present value of all dividends between t and T_i
	d_τ – the discrete dividend paid at τ where t ≤ τ ≤ T
	r_i – the continuously compounded interest rate from t to T_i

The present value of a floating interest rate leg can expressed as
〖PV〗_floating (t)=N∑_(i=1)〖(F_i+s)τ_i D_i 〗
where
	t   –  the valuation date
	N  – the notational principal amount
	i  –  the ith cash flow (swaplet) from 1 to n
	τ_i=τ(T_(i-1),T_i) – the accrual period (T_(i-1),T_i) of the ith cash flow.
	D_i=D(t,T_i)    –  the discount factor
	   F_i=1/τ_i  (□(D_(i-1)/D_i -1))- the simply compounded forward rate
	s  - the floating spread

The present value of the equity swap from the equity receiver perspective is given by

	PV(t)=〖PV〗_equity (t)-〖PV〗_floating






References:
   
[More details](./EqSwap-7.pdf)
   
[Zenodo swap](https://zenodo.org/record/3948310)

[OSF swap](https://osf.io/72693/download)

[Fliphtml5 swap](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamYTNxgDN5ITPkl0av9mY)

[gitbook swap](https://deripricing.gitbook.io/total-return-swap-valuation/)

[Zenodo double cms](https://zenodo.org/record/6578517)

[github Asset backed](https://github.com/timxiao1203/AssetBackedNote)


