<h1> Active-Directory-design-with-PowerShell</h1>

<h2>Description</h2>
 In this project I will demonstrate how to create a company environment in Active Directory via PowerShell. The first step in this project was to create a new Organizational unit as well as High level Organizational units via PowerShell. After that I created sub-Organizational units for each Department consisting of (Computers, Groups, Resources, Users).  Once the sub-organizational units were created, I added security groups for IT in different departments.  After setting up the necessary security groups, I proceeded to create user accounts and assign passwords using PowerShell.  As an example, I created a user named Alex and added him to the IT-HelpDesk as well as the Administrator security groups. Additionally, I created new computer objects within PowerShell, completing the setup of a realistic Active Directory environment. 
<br />

<h2>Project walk-through:</h2>

<p align="center">
Creation of GreenEnergy_OU as well as the departments within Green Energy (Business, Engineering, IT. Research and development) via PowerShell : <br/>
<img src="[https://i.imgur.com/a/fVPSjRN.png](https://imgur.com/a/fVPSjRN)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
