# eDiscovery-hold
Perform an eDiscovery hold on Teams/SharePoint/Exchange content containing the keyword "Stock"

<h2>Description</h2>
Project consists of a creating a Device Configuration Profile with Intune as a part of Mobile Device Management. Microsoft Intune includes settings and features you can enable or disable on different devices within your organization. These settings and features are added to "configuration profiles". You can create profiles for different devices and different platforms, including iOS/iPadOS, Android device administrator, Android Enterprise, and Windows. Then, use Intune to apply or "assign" the profile to the devices. As part of this project we will Block Personalization Sales group and exclude Marketing group.

<br />


<h2>Environments Used </h2>

- <b>Microsoft Compliance Purview Portal</b> 

<h2>Prerequisites</h2>

-<b> Configuration Profile can be created or modified by anyone assigned the following roles:
 - Intune administrator
 - Global Administrator
 </b>
- <b> Licenses:  EMS E3/E5 or Microsoft 365 F1/F3/E3/E5 license</b>

<h2>Program walk-through:</h2>

<h3>Steps: </h3>

1.  Go to Microsoft Purview Compliance portal --> go to eDiscovery 
2.	Select Standard eDiscovery --> create a case --> name it --> save
3.	Go to ‘hold’ tab -->  + create -> name it --> next
4.	Choose locations (Email, SharePoint, Teams)
5.	Query section --> keywords ‘Stock’ 
6.	Review settings --> create

	
<h3>Screenshots:</h3>

<p align="center">
Create Configuration Profile <br/>
<img src="configuration profiles.png" height="50%" width="50%" />
<br />
<br />
Give Name: <br/>
<img src="name.png" height="50%" width="50%" />
<br />
<br />
Configuration Settings: <br/>
<img src="configure.png" height="50%" width="50%"/>
<br />
<br />
Review & Create: <br/>
<img src="review creae.png" height="65%" width="50%"/>
<br />
<br />
Result: <br/>
<img src="res.png" height="65%" width="50%"/>
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
