<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install-configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>


- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Roles.
- Departments.
- Teams.
- Agents(Workers).
- Users(Customers).
- SLA.

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/4xfIm7X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure "Roles" Click Admin Panel on the top right hand side ->Agents ->Roles.
</p>
<br />

<p>
<img src="https://i.imgur.com/LYlJ8B6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Give a name Example "Supreme Admin" and give all permissions.
</p>
<br />

<p>
<img src="https://i.imgur.com/sKP40EY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After give all permissions, Check all the Tasks and knowlegebase boxes as well and click Add role.
</p>
<br />

<p>
<img src="https://i.imgur.com/ZEQUIMl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure "Departments" Admin Panel -> Agents -> Departments -> New Department. 
</p>
<br />

<p>
<img src="https://i.imgur.com/eBU387n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Add new Department "System Administrators" click create Dept.
</p>
<br />

<p>
<img src="https://i.imgur.com/vdMutBg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure "Teams" Admin Panel -> Agents -> Teams -> Add New Team.
</p>
<br />

<p>
<img src="https://i.imgur.com/7DPJjup.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name: Level II Support - Level III Support and click on create Team.
</p>
<br />

<p>
<img src="https://i.imgur.com/mF329vK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow anyone to create tickets: Admin Panel -> Settings -> User Settings Registration Required: make sure the box is unchecked Require registration and login to create tickets.
</p>
<br />

<p>
<img src="https://i.imgur.com/GzeeU1G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (workers) Admin Panel -> Agents -> Add New
Jack
John
Click on set Password.
</p>
<br />

<p>
<img src="https://i.imgur.com/umwbCws.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Uncheck the box -> create a new password and set.
</p>
<br />

<p>
<img src="https://i.imgur.com/f9N2ATl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After set a new password go to Access tab and select Department, Role, Teams according to your requirements and click create. 
</p>
<br />

<p>
<img src="https://i.imgur.com/1yXHZTP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users (customers) Agent Panel -> Users -> Add New.
</p>
<br />

<p>
<img src="https://i.imgur.com/OFnG2Eb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a New users.
Ken
Karen
</p>
<br />

<p>
<img src="https://i.imgur.com/0wXLpZk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours) Save Changes.
</p>
<br />

<p>
<img src="https://i.imgur.com/cgsx0LQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics: Admin Panel -> Manage -> Help Topics -> Add New Help Topics.
</p>
<br />

<p>
<img src="https://i.imgur.com/aKPbihl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Set a New help Topics is make easier for Customers to access a particular topic.   
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Your osTicket is set now and anyone can create a new ticket, so all these settings you did is as an Admin.  
</p>
<br />



