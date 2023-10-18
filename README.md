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
- Allow anyone to create tickets
- Configure Users (customers) and Agents (workers)
- Configure Help Topics and SLA Agreements

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/TDUk3TJ.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you have installed and finished setting up osTicket, log in to the admin account to start configuring roles, departments, teams, etc. I started by going into the admin panel next to where it says “welcome, juan”, then to Agents tab, click on Roles and: Add New Role. Here I set up the Supreme Admin role and gave this role all permissions. On the same Agents tab I clicked on Departments and added the Systems administrators.
</p>
<br />

<p>
<img src="https://i.imgur.com/i7mY8v5.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
For Teams, I created the Level I and Level II support teams. Teams allow you to bring together Agents from other departments together to solve any Issues.

To allow anyone to create tickets to this, you can go to the Settings tab, then click Users and unchecked Registration Required.
</p>
<br />

<p>
<img src="https://i.imgur.com/NmlN8MW.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
The Agents that you add and osTicket can be assigned to teams and departments. I created an account for Jane & John. I also added some users who create some ticket examples, Karen & Ken.
</p>
<br />

<p>
<img src="https://i.imgur.com/xksLhoo.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Added some Service Level Agreements: these are agreements that set deadlines for the tickets to be completed. I made 3, for the levels of severity.
</p>
<br />

<p>
<img src="https://i.imgur.com/WbExjuu.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, I changed the default help topics and added some new ones for when tickets get submitted. The configuration is done and we can see some mock tickets get placed and closed in the next section.
</p>
<br />
