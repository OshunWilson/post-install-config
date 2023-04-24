<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow Anyone To Create Tickets
- Configure Agents (Workers)
- Configure Users (Customers) 
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/J45hV2v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Roles
  
a. Admin Panel -> Agents -> Roles
  
b. Supreme Admin
</p>
<br />

<p>
<img src="https://i.imgur.com/PaVFXq7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Departments
  
a. Admin Panel -> Agents -> Departments
  
b. System Administrators
</p>
<br />

<p>
<img src="https://i.imgur.com/8ZHAzps.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Configure Teams
  
  Admin Panel -> Agents -> Teams
  
  1. Level I Support
  
  2. Level II Support
</p>
<p>
<img src="https://i.imgur.com/nb6g2oW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow anyone to create tickets 
  
a. Admin Panel -> Settings -> User Settings 
  
b. Registration Required: Require registration and login to create tickets  
</p>
<br />
<p>
<img src="https://i.imgur.com/dgQh541.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (workers) - 
Admin Panel -> Agents -> Add New
  
1. Jane
</p>
<br />
<p>
<img src="https://i.imgur.com/UNVgncW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users (customers) 
  
Agent Panel -> Users -> Add New
  
1. Ken
</p>
<br />
<br />
<p>
<img src="https://i.imgur.com/QqI8mAM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA
  
Admin Panel -> Manage -> SLA
  
    1. Sev-A (1 hour, 24/7)
  
    2. Sev-B (4 hours, 24/7)
  
    3. Sev-C (8 hours, business hours)
  SLA Plan is to provide a length of time in which the help desk Admin expects tickets to be closed.
</p>
<br />
<p>
<img src="https://i.imgur.com/3TrjB0v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics
Admin Panel -> Manage -> Help Topics
  
    1. Business Critical Outage
  
    2. Personal Computer Issues
  
    3. Equipment Request
</p>
<br />
