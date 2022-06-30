## Puttable Bond Valuation

A puttable bond is a bond in which the investor has the right to sell the bond back to the issuer at specified times for a specified price. At each puttable date prior to the bond maturity, the investor may get the investment money back by selling the bond back to the issuer. The underlying bonds can be fixed rate bonds or floating rate bonds. A puttable bond can therefore be considered a vanilla underlying bond with an embedded Bermudan style option. Puttable bonds protect investors. Therefore, a puttable bond normally pays investors a lower coupon than a non-callable bond. 

Although a puttable bond is a higher cost to the investor and an uncertainty to the issuer comparing to a regular bond, it is actually quite attractive to both issuers and investors. For investors, puttable bonds allow them to reduce interest costs at a future date should rate increase. For issuers, puttable bonds allow them to pay a lower interest rate of return until the bonds are sold back. If interest rates have increased since the issuer first issues the bond, the investor is like to call its current bond and reinvest it at a higher coupon. This presentation gives an overview of puttable bond and valuation model. 

	At the bond maturity T, the payoff of a puttable bond is given by


V_p (T)={■(F+C                    if not ptted@〖max⁡(P〗_p,F+C)        if putted)┤
where 
F – the principal or face value; 
C – the coupon; 
	P_p – the put price; 
max (x, y) – the maximum of x and y
T -  the maturity date;


	The payoff of the puttable bond at any call date T_i can be expressed as

V_p (T_i )={■(¯V_(T_i )                                  if not putted@max⁡(P_p,¯V_(T_i ) )                        if putted)┤
where 	
¯V_(T_i ) – continuation value at T_i
P_p – the put price; 
max (x, y) – the maximum of x and y
T_i -  the i-th call date;


	The dynamics of LGM model is given by
dX(t)=α(t)dW
	Where X is the single state variable; W is the Wiener process.
	The numeraire is given by
N(t,X)=(H(t)X+0.5H^2 (t)ζ(t))/D(t)
	The zero coupon bond price is
B(t,X;T)=D(T)exp(-H(t)X-0.5H^2 (t)ζ(t))

At time t, X(0)=0 and H(0)=0. Thus Z(0,0;T)=D(T). In other words, the LGM automatically fits today’s discount curve.
	Select a group of market swaptions.
	Solve parameters by minimizing the relative error between the market swaption prices and the LGM model swaption prices.





References:


[More details](./FiPuttableBond-16.pdf)

[Zenodo puttable](https://zenodo.org/record/6484069#.YpU428PMKUk)

[archive puttable](https://ia803402.us.archive.org/22/items/fi-puttable-bond-16/FiPuttableBond-archive.pdf)

[gitbook putable](https://cmrm11.gitbook.io/puttable-bond/)

[OSF puttable](https://osf.io/veqj3/download)

[Zenodo chooser](https://zenodo.org/record/6546805#.YpDu9KgpDq4)

[github principal](https://github.com/cfrm17/PrincipalNote-)

