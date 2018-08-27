# fslCreateData

This app will create 20 Accounts for Pizza resturants/locations within the New York area.

Pressing the create button will start a Flow which will create the following

* 1 Work Order per Account (where the name contains FSL)
* 3 Work Order Line Items are assigned to the Work Order
* Work Types are set to each Work Order Line Item
* 1 Service Appointment is assigned to the Work Order
* **All variables can be configured within the Flow**
* The Flow will also make the same data for all the Accounts for Today+1 and Today+2
* After pressing create you will have 60 Work Orders (each with 3 WOLI and 1 Service Appointment) 
	* 20 Work Orders are created with a start date of Today, 
	* 20 are created with a start date of Today+1 (tomorrow)
	* 20 are created with a start date of Today+2 (2 days time)

<img src="https://github.com/daviddarkins/fslCreateData/blob/master/DATA/fslcreatedata_wo1.png"/>
<!--
<a href="https://githubsfdeploy.herokuapp.com?owner=daviddarkins&repo=fslCreateData">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a> -->

## unmanaged package link 
* Prod https://login.salesforce.com/packaging/installPackage.apexp?p0=04t0O000000Q7pc 
* Sandbox https://test.salesforce.com/packaging/installPackage.apexp?p0=04t0O000000Q7pc