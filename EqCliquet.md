## Counterparty Risk System Permission
   
This document lists the general Security and Permissions requirements for the counterparty risk system. Specifically, it lists the Permissions requirements needed for the system.  
It may also contain requirements for processes immediately surrounding or connecting to Adaptiv so that the existing functionality can be replicated. 

The defined level of access to any feature of the system which will have permission settings, and these permission settings will be set as granular as for each given user. 
Permissions also influence how users are able to interact with a workflow process within the system. A user requires a combination of permissions to Business Branches, Products, Workflow 
Transitions, and Accessible Views in order to perform actions in the system. Users can be given access to a permission via Groups and Roles as in the below diagram. 

Trade Viewing Permissions. Permissions are given at the “Business Branch level or higher”. Branches allow a user to view deals booked for each of the transits that are a child of the branch. 

Trade booking permissions. Trade booking permissions are given ONLY at the “Transit level”, and the trade booking permissions allow a user to book new deals at a given transit.

Every user Permission in the system is separated out line by line in the Role settings. In order for a user to be able to perform a given action, the associated Permission must be set to “enabled” 
in a Role profile, and the user must have be connected to that user role profile via the user or via an appropriate Group. 

Access within Detailed Record View. With respect to viewing a record’s details, the ability to view any tab within the record’s detailed view, every view will be set to either edit, view, 
or hide (where appropriate) for a given user role.

A “named delegate” allows the system “approval workflows ownership” to be transferred from a “delegator user” to a “delegate user” during an absence or vacation. Subject to an approval process, 
the permissions can be transferred to another proxy user.

Clone User Rights Settings. An administrator/Credit Risk Reporting Analyst will be able to appropriately clone a given user’s User Right settings in order to create a new user. Copy User Rights 
Settings. An administrator must be able to easily copy the User Right settings of a given user, and add these User Right settings to another user. The “copied to” user will have the set of 
settings that is the union of the user’s previous settings and “copied settings”. Each set of attributes for an entity can be copied independently, e.g. copying Roles for a given User can be 
done and the Groups will not be copied



References:
   
   
[Zenodo cliquet](https://zenodo.org/record/4609253)
   
[OSF cliquet](https://osf.io/swbg4/download)

[gitbook cliquet](https://deripricing.gitbook.io/cliquet-option-valuation/)

[github American](https://github.com/timxiao1203/AmericanBondOption)

