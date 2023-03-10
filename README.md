# eDiscovery-hold
Perform an eDiscovery hold on Teams/SharePoint/Exchange content containing the keyword "Stock"

<h2>Description</h2>
Lab consists of a create and perform an eDiscovery hold for Content Search by using Compliance Purview Portal. Microsoft Purview eDiscovery (Standard) in Microsoft Purview provides a basic eDiscovery tool that organizations can use to search and export content in Microsoft 365 and Office 365.  can also use eDiscovery (Standard) to place an eDiscovery hold on content locations, such as Exchange mailboxes, SharePoint sites, OneDrive accounts, and Microsoft Teams.
<br />


<h2>Environments Used </h2>

- <b>Microsoft Compliance Purview Portal</b> 

<h2>Prerequisites</h2>

-<b> Configuration Profile can be created or modified by anyone assigned the following roles:
 - eDiscovery Manager
 - eDiscovery Administrator
 - Case Management
 - Global Administrator
 </b>
- <b> Licenses: Exchange online Plan 2 or  Microsoft 365 E3 OR Office 365 E3 license or higher OR Office 365 E1 license with a SharePoint Online Plan 2 OR OneDrive for Business Plan 2 add-on license</b>

<h2>Program walk-through:</h2>

<h3>Steps: </h3>

1.  Go to Microsoft Purview Compliance portal --> go to eDiscovery 
2.  Select Standard eDiscovery --> create a case --> name it --> save
3.  Go to ‘hold’ tab -->  + create -> name it --> next
4.  Choose locations (Email, SharePoint, Teams)
5.  Query section --> keywords ‘Stock’ 
6.  Review settings --> create

	
<h3>Screenshots:</h3>

<p align="center">
Purview Portal & eDiscovery Standard:  <br/>
<img src="eDiscovery.png" height="50%" width="50%" />
<br />
<br />
Create New & Give Name: <br/>
<img src="new case.png" height="50%" width="50%" />
<br />
<br />
Check active status & go to hold tab: <br/>
<img src="active status of case.png" height="50%" width="50%"/>
<br />
<br />
Choose Locations: <br/>
<img src="locations.png" height="65%" width="50%"/>
<br />
<br />
Query Section: <br/>
<img src="query.png" height="65%" width="50%"/>
<br />
<br />
Review & Submit: <br/>
<img src="review.png" height="65%" width="50%"/>
<br />
<br />
Result: <br/>
<img src="result.png" height="65%" width="50%"/>
<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
