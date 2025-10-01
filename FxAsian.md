## View Results

The system will allow the user to define a view that can be applied to a Calculator Framework Result set or any set of reference data to produce a single unified table of data representing 
a de-normalized view of the full set of data.

For example: Counterparty + Organization + Address + Agreement + Trade to create a list of all trades, their counterparties and addresses and their respective location in the organization tree.

The system will allow the user to define a view that can be applied to any snapshot of reference data anchoring to any one dimension for records and supplementing from other dimensions.

The system should allow the user to visually define the linking fields between data similar to a query definition system found in MS Access

The system should infer / have pre-defined links between all the standard data model entities (i.e. adding a Counterparty that has an Address ID should map to the Address Table to obtain all the 
Address fields of the Counterparty when the Address Dimension is added)

The system will allow the view to be applied to any snapshot of the system / database.  This will allow for cross comparison data views to be defined.

The system will have an object level set of views for reference domains not entered by users with the database level links pre-defined and all fields accessible.

The system will allow the user to save the current for future retrieval / changing.  This should be private (visible only to the user), semi-private (group of users) or public (visible by everyone)


References:



[Zenodo fx Asian](https://zenodo.org/record/6484837/files/Zenodo-FxAsian.pdf)

[OSF Asian](https://osf.io/g73qw/download)

[Zenodo bond abs](https://zenodo.org/records/15027036/files/BondAssetBacked.pdf)

[Zenodo exposure](https://zenodo.org/record/6539344)

[github var](https://github.com/cfrm17/HedgeFundVaR)



