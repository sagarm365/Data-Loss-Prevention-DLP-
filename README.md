# Data-Loss-Prevention-DLP-
Create a DLP policy for PII only for Exchange. Set encrypt content to enable.

<h2>Description</h2>
Project consists of a creating a Risk-based access policies as a part of Azure AD Identity Protection policies. Risk-based access policies, there are two types of risk policies in Azure Active Directory (Azure AD) Conditional Access we can set up to automate the response to risks and allow users to self-remediate when risk is detected: Sign-in risk policy and User-risk policy. In this practical, it is auto applying for High risk level.
<br />


<h2>Environments Used </h2>

- <b>Microsoft 365 Defender portal</b> 

<h2>Prerequisites</h2>

-<b> DLP policy for cloud apps can be created or modified by anyone assigned the following roles:
 - Security Administrator
 - Global Administrator
 </b>
- <b> Licenses: at-least Azure Active Directory Premium P1</b>

<h2>Program walk-through:</h2>

<h3>Steps: </h3>

1.  Microsoft Purview portal --> Data loss prevention --> create policy
2.	‘Privacy’ category -> select template ‘US: PII’
3.	Give name and description and choose location ‘Exchange’ only
4.	Next -> Restrict access in Ms 365 locations
5.	Test policy 
6.	Review & create
	


<h3>Screenshots:</h3>

<p align="center">
Create policy and choose info to protect: <br/>
<img src="dlp create.png" height="50%" width="50%" />
<br />
<br />
Give Name: <br/>
<img src="name.png" height="50%" width="50%" />
<br />
<br />
Choose Location: <br/>
<img src="locations.png" height="50%" width="50%"/>
<br />
<br />
Choose Info to protect: <br/>
<img src="settings.png" height="65%" width="50%"/>
<br />
<br />
Restrict Access: <br/>
<img src="restrict access.png" height="65%" width="50%"/>
<br />
<br />
Review & Create: <br/>
<img src="review.png" height="65%" width="50%"/>
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
