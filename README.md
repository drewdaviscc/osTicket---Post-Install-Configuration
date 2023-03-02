<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. This lab is part II to the OsTicket-Prerequisites and Installation lab<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments & Teams
- Allow Users to Create Tickets
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
  
https://imgur.com/gallery/1cJ9rA5

Log into the OsTicket browser and make sure you are on the admin panel. Click agents>roles> add new role> create a supreme admin who can do every task and has all permissions.
</p>
<br />


Create two new test agents ex: Jane Doe and John Doe. Assign Jane to System Administrators department with Supreme admin permissions level. Also add her to the Level II support team. All of these options are located under the Next add John Doe.
</p>
<br />
https://imgur.com/v9gdtQa

Next, a "Service Level Agreement" (SLA) needs to be created. Here are the layouts: Sev-A Level I - tickets must be responded to within 1 hour on a 24/7 schedule. Sev-B- ticket response time must be within 4 hours on a 24/7 schedule. Sev-C- within 8 hours on a regular business hour time frame. Go to admin panel>manage>SLA. 
