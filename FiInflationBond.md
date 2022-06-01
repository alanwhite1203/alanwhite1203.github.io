## Inflation Linked Bond Valuation

Inflation indexed bonds, also called inflation linked bonds or real return bonds, are bonds where the principal is indexed to inflation or deflation on a daily basis in terms of a reference index, such as Consumer Price Index (CPI). The CPI is the proxy for inflation that measures price changes in a basket of goods and services. 

The main idea of inflation indexed bonds is that investing in the bond will generate a certain real return. Inflation indexed bonds pay a periodic coupon that is equal to the product of the daily inflation index and the nominal coupon rate. Therefore, even though the nominal value of the coupons and principal may change, the real return of these remains the same. Unlike regular (nominal) bonds, inflation indexed bonds assure that your purchasing power is maintained regardless of the future rate of inflation. 

An inflation indexed bond is designed to hedge the inflation risk of the bond. Since inflation indexed bonds offer investors a very high level of safety, their coupons are typically lower than high-yield bonds. It is an important vehicle for investors whose liabilities indexed to changes in inflation or wages. Inflation indexed bonds have favorable performance and lower volatility relative to other risk assets. It is favorable to retirement planning and pension funds given its inflation protection. Inflation indexed bonds are less liquid than regular bonds. This presentation provides an overview of inflation indexed bond product and valuation. 


	Inflation Indexed Bond Introduction
	Inflation indexed bonds, also called inflation linked bonds or real return bonds, are bonds where the principal is indexed to inflation or deflation on a daily basis in terms of a reference index, such as Consumer Price Index (CPI).
	The CPI is the proxy for inflation that measures price changes in a basket of goods and services.
	The main idea of inflation indexed bonds is that investing in the bond will generate a certain real return.
	Inflation indexed bonds pay a periodic coupon that is equal to the product of the daily inflation index and the nominal coupon rate.
	Therefore, even though the nominal value of the coupons and principal may change, the real return of these remains the same.
	Unlike regular (nominal) bonds, inflation indexed bonds assure that your purchasing power is maintained regardless of the future rate of inflation.


	The use of Inflation Indexed Bonds
	Inflation indexed bonds are designed to hedge the inflation risk of a bond.
	Since inflation indexed bonds offer investors a very high level of safety, their coupons are typically lower than high-yield bonds.
	It is an important vehicle for investors whose liabilities indexed to changes in inflation or wages.
	Inflation indexed bonds have favorable performance and lower volatility relative to other risk assets.
	It is favorable to retirement planning and pension funds given its inflation protection.
	Inflation indexed bonds are less liquid than regular bonds.


	Valuation
	The present value of an inflation indexed bond is given by

	 


 		PV(t)=∑_(i=1)^n▒C ̅_i  D_i+(P_n ) ̅D_n
where
	t	the valuation date
	(C_i ) ̅=C*CPI(T_i )/CPI(T_I)	the inflation adjusted coupon at payment  date T_i                      
	(P_n ) ̅=P*CPI(T_n )/CPI(T_I)	the inflation adjusted principal at maturity date T_n
	CPI(t)	the base reference CPI at time t.
	CPI(T_i )/CPI(T_I)	the CPI ratio at T_i
	T_I	the issue date.
	D_i=D(t,T_i)	the discount factor from T_i to t.


	Practical Guide
	First construct inflation curve by bootstrapping either breakeven inflation swap rates or treasury inflation protected securities (TIPS).
	Compute the base reference CPIs at the issue date and each payment date.
	Adjust the coupons and principal based on CPI ratio at each payment date.
	Discount all the coupons and principal to the valuation date.
	The bond price is the sum of all the present values.



References:


[More details](./FiInflationBond-15.pdf)

[FlipHtml5 inflation](https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamADM3QjM5ITPkl0av9mY)

[Zenodo inflation](https://zenodo.org/record/6484024#.YpU4jcPMKUk)

[archive inflation](https://ia903408.us.archive.org/33/items/fi-inflation-bond-15/FiInflationBond-archive.pdf)

[OSF inflation](https://osf.io/f2qm9/download)

[Zenodo caption](https://zenodo.org/record/6561073#.YpDwZagpDq4)


