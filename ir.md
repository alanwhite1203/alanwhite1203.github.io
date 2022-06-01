## Interest Rate Derivative Products

### Amortizing and Accreting Cap and Floor

An amortizing cap is an interest rate cap whose notional principal amount declines during the life of the contract whereas an accreting cap is an interest rate cap whose notional principal amount increases during the life of the contract. Similarly, an amortizing floor is an interest rate floor whose notional principal amount declines during the life of the contract whereas an accreting floor is an interest rate floor whose notional principal amount increases during the life of the contract. 

An interest rate cap is a financial contract between two parties that provides an interest rate ceiling or cap on the floating rate payments. It consists of a series of European call options (caplets) on interest rates. An amortizing cap is an interest rate cap whose notional principal amount declines during the life of the contract whereas an accreting cap is an interest rate cap whose notional principal amount increases during the life of the contract.


[More details](./IrAmortizingCap.md)

[OSF amortizing cap](https://osf.io/rfa8e/download)

[Science-media amortizing cap](https://science-media.org/userfiles/1020/presentations/1020_presentation_542.pdf)




### Amortizing and Accreting Swap  

An amortizing swap is an interest rate swap whose notional principal amount declines during the life of the contract whereas an accreting swap is an interest rate swap whose notional principal amount increases instead. The notional amount changes could be one leg or two legs, but typically on a fixed schedule. The notional principal is tied to an underlying financial instrument with a declining principal, such as a mortgage or an increasing principal, such as a construction fund. 

The notional principal of an amortizing swap is tied to an underlying financial instrument with a declining principal, such as a mortgage. On the other hand, the notional amount of an accreting swap  is tied to an underlying instrument with an increasing principal, such as a construction fund. The notional principal schedule of an amortizing or an accreting swap may decrease or increase at the same rate as the underlying instrument. Both amortizing and accreting swaps can be used to reduce or increase exposure to fluctuations in interest rates. This presentation gives an overview of amortizing or accreting swap product and valuation model. 
 
 
[More details](./IrAmortizingSwap.md)

[Zenodo amortizing swap](https://zenodo.org/record/4015549/files/IrAmortizingSwap-26.pdf)

[OSF amortizing swap](https://osf.io/mgc83/download)

[Science-media amortizing swap](https://science-media.org/userfiles/1020/presentations/1020_presentation_543.pdf)

 
 
 
### Basis Swap 
 
A basis swaps is an interest rate swap that involves the exchange of two floating rates, where the floating rate payments are referenced to different bases. Both legs of a basis swap are floating but derived from different index rates (e.g. LIBOR 1 month vs 3 month).  Basis swaps are settled in the form of periodic floating interest rate payments. They are quoted as a spread over the reference index. For example, 3-month LIBOR is frequently used as a reference. Spreads are quoted over it. 

A basis swap can be used to limit interest rate risk that a firm faces as a result of having different lending and borrowing rates. Basis swaps help investors to mitigate basis risk that is a type of risk associated with imperfect hedging. Firms also utilize basis swaps to hedge the divergence of different rates. Basis swaps could involve many different kinds of reference rates for the floating payments, such as 3-month LIBOR, 1-month LIBOR, 6-month LIBOR, prime rate, etc. There is an active market for basis swaps. This presentation gives an overview of interest rate basis swap product and valuation model. 

 
[More details](./IrBasisSwap.md)

[Zenodo basis swap](https://zenodo.org/record/4015555/files/IrBasisSwap-27.pdf)

[FlipHtml5 basis swap](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamgTO3gDN3ITPkl0av9mY)

[OSF basis swap](https://osf.io/zcyuq/download)

[Science-media basis swap](https://science-media.org/userfiles/1020/presentations/1020_presentation_544.pdf)

  
 
  
### Interest Rate Bermudan Swaption
  
An interest rate Bermudan swaption gives the holder the right but not the obligation to enter an interest rate swap at predefined dates. It is one of the fundamental ways for an investor to enter a swap. Comparing to regular swaptions, Bermudan swaptions provide market participants more flexibility and control over the exercising of an option and less restriction.

Given those flexibilities, a Bermudan swaption is more expensive than a regular European swaption. In terms of valuation, it is also much more complex. This presentation provides practical details for pricing Bermudan swaption. 
 
  
[More details](./IrBermudan.md)

[Zenodo bermudan](https://zenodo.org/record/4019675/files/IrBermudan-28.pdf)

[OIS bermudan](https://osf.io/5dz4u/download)

[Science-media bermudan](https://science-media.org/userfiles/1020/presentations/1020_presentation_545.pdf)

  

   
### Interest Rate Cancelable Swap 
   
A cancelable swap provides the right but not the obligation to cancel the interest rate swap at predefined dates. Most commonly traded cancelable swaps have multiple exercise dates. Given its Bermudan style optionality, a cancelable swap can be represented as a vanilla swap embedded with a Bermudan swaption. Therefore, it can be decomposed into a swap and a Bermudan swaption. Most Bermudan swaptions in a bank book actually come from cancelable swaps. This presentation provides practical details for pricing cancelable swaps.   
   
   
[More details](./IrCancelableSwap.md)

[Zenodo cancelable swap](https://zenodo.org/record/4019681/files/IrCancelableSwap-29.pdf)

[FlipHtml5 cancelable swap](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamYzMwgDM5ITPkl0av9mY)

[OSF cancelable swap](https://osf.io/v7whf/download)

[Science-media cancelable swap](https://science-media.org/userfiles/1020/presentations/1020_presentation_546.pdf)

   
   
   
### Interest Rate Caps and Floors 
   
An interest rate cap is a financial contract between two parties that provides an interest rate ceiling or cap on the floating rate payments. It actually 
consists of a series of European call options (caplets) on interest rates.  The buyer receives payments at the end of each period when the interest rate 
exceeds the strike.  In return, the buyer needs to pay an up-front premium to the seller.

[More details](./IrCap.md) 

[Zenodo cap](https://zenodo.org/record/4019685/files/IrCap-30.pdf)

[FlipHtml5 cap](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamgDOygDM5ITPkl0av9mY)

[OSF cap](https://osf.io/kvbyz/download)

[Science-media cap](https://science-media.org/userfiles/1020/presentations/1020_presentation_547.pdf)

   
   
   
### Capped Swap
   
A capped swap is an interest rate swap with an interest rate cap option where the floating rate of the swap is capped at a certain level while a floored swap is an interest rate swap with a floor option where the floating rate of the swap is floored at a certain level. Capped swaps or floored swaps limit the risk of the floating rate payer or receiver to adverse movements in interest rates. A capped swap can be decomposed into a swap and a cap whereas a floored swap can be decomposed into a swap and a floor. 

A capped swap can be decomposed into a swap and a cap whereas a floored swap can be decomposed into a swap and a floor. Given the optionality, an up-front fee or premium has to be paid by the floating rate payer for a capped swap and an up-front fee or premium has to be paid by the floating rate receiver for a floored swap. This presentation gives an overview of capped/floored swap product and valuation.
   
   
[More details](./IrCappedSwap.md)

[FlipHtml5 capped swap](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamQTOygDM5ITPkl0av9mY)

[OSF capped swap](https://osf.io/jskhm/download)

[Science-media capped swap](https://science-media.org/userfiles/1020/presentations/1020_presentation_548.pdf)

   
   
   
### Compounding Swap
   
A compounding swap is an interest rate swap in which interest, instead of being paid, compounds forward until the next payment date. Compounding swaps can be valued by assuming that the forward rates are realized. Normally the calculation period of a compounding swap is smaller than the payment period. For example, a swap has 6-month payment period and 1-month calculation period (or 1-month index tenor). An overnight index swap (OIS) is a typical compounding swap. This presentation gives an overview of compounding swap product and valuation model.    
   
   
[More details](./IrCompoundingSwap.md)

[FlipHtml5 compounding swap](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamkzN5UjM5ITPkl0av9mY)

[OSF compounding swap](https://osf.io/dqepj/download)

[Science-media compounding swap](https://science-media.org/userfiles/1020/presentations/1020_presentation_549.pdf)


   

   
### Forward Rate Agreement
   
A forward rate agreement, or FRA, is a forward contract between two parties in which one party will pay a fixed rate while the other party will pay a reference interest rate for a set future period. Similar to a swap, a FRA has two legs: a fixed leg and a floating leg. But each leg only has one cash flow. The party paying the fixed rate is usually referred to as the borrower, while the party receiving the floating rate is referred to as the lender.

Some people believe that a FRA is equivalent to a one-period vanilla swap. That is not completely true from valuation perspective. A FRA is usually settled and paid at the end of a forwarding period, called settle in arrear, while a regular swaplet is settled at the beginning of the forward period and paid at the end. Strictly speaking, FRAs need convexity adjustment. However, given FRA is such a simple product, the adjustment is very simple as well. 

   
[More details](./IrFra.md)

[OSF frn](https://osf.io/k8v2q/download)

[Science-media frn](https://science-media.org/userfiles/1020/presentations/1020_presentation_550.pdf)

   

   
### Interest Rate Futures
   
An interest rate future is a futures contract between the buyer and seller to deliver an interest bearing asset, that allows the buyer and seller to lock in the price of the interest bearing asset for a future date. The most popular interest rate future is Eurodollar future.

Eurodollar futures contract is a cash-settled futures contract. The underlying instrument in Eurodollar futures is a Eurodollar time deposit having a principal value of $1,000,000 with a three-month maturity. Eurodollar futures prices are expressed numerically using 100 minus the implied 3-month U.S. dollar LIBOR interest rate. In this way, a Eurodollar future price of $98 reflects an implied settlement interest rate of 2%.
   
   
[More details](./IrFuture.md)

[Zenodo futures](https://zenodo.org/record/4031743/files/IrFuture-34.pdf)

[FlipHtml5 futures](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamIDO5UjM5ITPkl0av9mY)

[OSF futures](https://osf.io/j9apv/download)

[Science-media futures](https://science-media.org/userfiles/1020/presentations/1020_presentation_551.pdf)
   

   
   
### Future Option
   
An interest rate future option gives the holder the right but not the obligation to buy or sell an interest rate future at a specified price on a specified date. It is usually traded in an exchange. The buyer normally can exercise the option on any business day (American style) prior to expiration by giving notice to the exchange. Option sellers (writer) receive a fixed premium upfront and in return are obligated to buy or sell the underlying asset at a specified price.

Interest rate future options can be used to hedge against adverse changes in interest rates. In general futures markets tend to be more liquid than underlying cash markets. This presentation gives an overview of interest rate future option product and pricing model. 
   
   
[More detials](./IrFutureOption.md)

[Zenodo future option](https://zenodo.org/record/4038197/files/IrFutureOption-35.pdf)

[OSF future option](https://osf.io/gbzj3/download)

[Science-media future option](https://science-media.org/userfiles/1020/presentations/1020_presentation_552.pdf)

   
   
   
### Interest Rate Swap 
   
An interest rate swap is an agreement between two parties to exchange future interest rate payments over a set period of time. It consists of a series of payment periods, called swaplets. The most popular form of interest rate swaps is the vanilla swaps that involve the exchange of a fixed interest rate for a floating rate, or vice versa. There are two legs associated with each party: a fixed leg and a floating leg. Swaps are OTC derivatives that bear counterparty credit risk beside interest rate risk. 

Interest rate swaps are the most popular OTC derivatives that are generally used to manage exposure to fluctuations in interest rates. Swaps can be also used to obtain a marginally lower interest rate. Thus they are often utilized by a firm that can borrow money easily at one type of interest rate but prefers a different type. They also allow investors to adjust interest rate exposure and offset interest rate risks. Speculators use swaps to speculate on the movement of interest rates. More and more swaps are cleared through central counterparties nowadays (CCPs). This presentation gives an overview of interest rate swap product and valuation model. 

   
[More details](./IrSwap.md)

[Github swap](https://github.com/alanwhite1203/irSwap)

[OSF swap](https://osf.io/kx5q2/download)

[Science-media swap](https://science-media.org/userfiles/1020/presentations/1020_presentation_553.pdf)

   
 
   
### Swaption
   
An interest rate swaption or interest rate European swaption is an OTC option that grants its owner the right but not the obligation to enter an underlying interest rate swap. There are two types of swaptions: a payer swaption and a receiver swaption.

An payer swaption is also called a right-to-pay swaption that allows its holder to exercise into a swap where the holder pays fixed rates and receives floating rates, while a receiver swaption is also called right-to-receive swaption that allows its holders to exercise into a swap where the holder receives fixed rates and pays floating rates.

   
[More details](./IrSwaption.md)
   
[Github swaption](https://github.com/alanwhite1203/irSwaption)

[Zenodo swaption](https://zenodo.org/record/4038217/files/IrSwaption-37.pdf)

[FlipHtml5 swaption](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamEzN4gzM5ITPkl0av9mY)

[OSF swaption](https://osf.io/f7yw9/download)

[Science-media swaption](https://science-media.org/userfiles/1020/presentations/1020_presentation_554.pdf)

   
   