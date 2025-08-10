## Portfolio Aggregation 
   
The portfolios and aggregation set include agreements and limit structures. These constitute different partitions of the trade population. While agreements indicate the exposure aggregation rules 
(netting, collateral, etc…), the aggregation sets define the on which partition the risk measures (EE, PFE, etc…) will be defined on. Each aggregation set may also include one or more limits.

Agreements are sets of trades which directly influence the aggregated exposure calculation at aggregation sets (defined later on). A portfolio can include multiple agreements. Aggregation sets 
correspond to a reporting structure and are in effect just another partition of trades, independently defined as agreements 

The agreements specify the trades they include and the business logic they rely on for trade inclusion criteria unless manually specified/modified.

The aggregation sets specify the trades they include and the business logic they rely on for trade inclusion criteria unless manually specified/modified. Drilling down through the aggregation sets 
and visualizing it through breadcrumbs.

Each aggregation set may have one or more limits attached to it. The limit structure consists in a set of limit attached to the aggregation sets the portfolio includes. It allows for a quick view 
of breaches when multiple limits are setup for various measures.

Risk measures can be attached to any aggregation sets levels and their risk profile are visible.



References:
   
[Zenodo fra](https://zenodo.org/record/6493996/files/Zenodo-IrFra.pdf)
   
[OSF fra](https://osf.io/k8v2q/download)

[Zenodo performance](https://zenodo.org/record/6547457)

[github mbs](https://github.com/cfrm17/MBSPassThrough)

