<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial walks through the steps for post-installation configuration with osTicket. Meant to be done right after the installation process of osTicket System.
<br />

<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Protocol (RDP)
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow Anyone To Create Tickets
- Configure Agents
- Configure Users
- Configure Service Level Agreements (SLA)
- Configure Help Topics

<h2>Configuration Steps</h2>


<p align="center">
Browse to these two sites as we will be working with them to accomplish this tutorial:
<br/>
Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php
<br/>
End Users osTicket URL: http://localhost/osTicket 
<br/>
Notice which one is the agent panel and which one is the admin panel
</p>
<br/>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>


<h3 align="center"> Configure Roles </h3>
<br/>
<p align="center">
Configure the roles for grouping permissions. Admin Panel > Agents > Roles > Add New Role > Name: Supreme Admin > Permissions: Give permissions for every single thing under Tickets, Tasks, and Knowledgable tabs 
</p>
<br/>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>

<h3 align="center"> Configure Departments </h3>
<br/>
<p align="center">
Configure the Departments for grouping permissions. Admin Panel > Agents > Departments > Add New Department > Name: SysAdmins > Parent: Top Level Department > Create Dept
</p>
<br/>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>

<h3 align="center"> Configure Teams </h3>
<br/>
<p align="center">
Configure the Departments for grouping permissions. Admin Panel > Agents > Teams > Add New Team > Name: SysAdmins > Parent: Online Banking > Create Team
</p>
<br/>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>

<h3 align="center"> Allow Anyone to Create Tickets  </h3>
<br/>
<p align="center">
Admin Panel > Settings > Users > Uncheck "Require registration and login to create tickets"
</p>
<br/>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>

<h3 align="center"> Configure Agents </h3>
<br/>
<p align="center">
Configure the Agents for grouping permissions. Admin Panel > Agents > Add New AGent > Name: Jane Doe, Email: fake email (save it), Username: Jane > Access: Sys Admins / Supreme Admin > Teams: Online Banking > Name: John Doe, Email: fake email (save it), Username: John > Access: Sys Admins / Supreme Admin > Teams: Online Banking
<br/>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>

<h3 align="center"> Configure Users (customers) </h3>
<br/>
<p align="center">
Configure the Users. Admin Panel > Users > Add User > Name: SysAdmins > email: fake email (save in notepad), name: karen > Add User
</p>
<br/>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>

<h3 align="center"> Configure Service Level Agreement (SLA) </h3>
<br/>
<p align="center">
Configure the SLA's. Admin Panel > Manage > SLA > Add three new SLA panels:
<br/>
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
<br/>
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
<br/>
Sev-C (Grace Period: 8 hours, Business Hours)
<br/>

</p>
<br/>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>


