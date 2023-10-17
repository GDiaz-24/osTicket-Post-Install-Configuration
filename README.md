<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%"alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial goes over the post-install configuration of the open-source help desk ticketing system osTicket.<br />



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
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<h3 align="center">Configure Roles</h3>
<br />
<p>
  Admin Panel -> Agents -> Roles.
</p>
<p>
  Supreme Admin:
</p>
<p>
  <img src="https://imgur.com/yacKoOo.png" height="75%" width="100%" alt="Definitions"/>
  <img src="https://imgur.com/llaYQnG.png" height="75%" width="100%" alt="Permissions"/>
  <img src="https://imgur.com/llaYQnG.png" height="75%" width="100%" alt="More Permissions"/>
  <img src="https://imgur.com/c8rrW7V.png" height="75%" width="100%" alt="Even More Permissions"/>
  <img src="https://imgur.com/Oe4czS4.png" height="75%" width="100%" alt="Sys Admin Success"/>
</p>
<br />
<br />
<h3 align="center">Configure Departments</h3>
<br />
<p>
  Admin Panel -> Agents -> Departments.
</p>
<p>
  System Administrators:
</p>
<p>
  <img src="https://imgur.com/E4gkLyt.png" height="75%" width="100%" alt="System Administrators"/>
</p>
<br />
<br />
<h3 align="center">Configure Teams</h3>
<br />
<p>
  Admin Panel -> Agents -> Teams.
</p>
<p>
  Level II Support:
</p>
<p>
  <img src="https://imgur.com/HQJIOCA.png" height="75%" width="100%" alt="Level II Support"/>
</p>
<br />
<br />
<h3 align="center">Allow anyone to create ticket</h3>
<br />
<p>
  Admin Panel -> Settings -> User Settings.
</p>
<p>
  Make sure "Require registration and login to create tickets" is not selected:
</p>
<p>
  <img src="https://imgur.com/0oj9m01.png" height="75%" width="100%" alt="ticket creations"/>
</p>
<br />
<br />
<h3 align="center">Configure Agents (workers)</h3>
<br />
<p>
  Admin Panel -> Agents -> Add New.
</p>
<p>
  Jane Doe:
</p>
  <img src="https://imgur.com/URsSDqw.png" height="75%" width="100%" alt="agent one access"/>
  <img src="https://imgur.com/pc6p2Y6.png" height="75%" width="100%" alt="agent one access"/>
<p>
  John Doe:
</p>
<p>
  <img src="https://imgur.com/Ie9Npac.png" height="75%" width="100%" alt="agent two"/>
  <img src="https://imgur.com/fo8jzJa.png" height="75%" width="100%" alt="agent two access"/>
</p>
<h3 align="center">Configure Users (customers)</h3>
<br />
<p>
  Admin Panel -> Users -> Add New.
</p>
<p>
  Karen Smith:
</p>
  <img src="https://imgur.com/KQwMbcA.png" height="75%" width="100%" alt="user access"/>
<p>
  Repeat the same above for Ken Smith.
</p>
<br />
<br />
<h3 align="center">Configure SLA</h3>
<br />
<p>
  Admin Panel -> Manage -> SLA.
</p>
<p>
  Sev-A (1 hour, 24/7).
</p>
<p>
  Sev-B (4 hours, 24/7).
</p>
<p>
  Sev-C (8 hours, business hours):
</p>
<p>
  <img src="https://imgur.com/bzrMa6i.png" height="75%" width="100%" alt="sev one"/>
  <img src="https://imgur.com/I82OC4J.png" height="75%" width="100%" alt="sev two"/>
  <img src="https://imgur.com/k6Un9pj.png" height="75%" width="100%" alt="sev three"/>
  <img src="https://imgur.com/rdrvX2H.png" height="75%" width="100%" alt="sla plan"/>
</p>
<br />
<br />
<h3 align="center">Configure Help Topics</h3>
<br />
<p>
  Admin Panel -> Manage -> Help Topics.
</p>
<p>
  Business Critical Outage.
  <img src="https://imgur.com/undefined.png" height="75%" width="100%" alt="business critical outage"/>
</p>
<p>
  Personal Computer Issues.
  <img src="https://imgur.com/dlqWtMV.png" height="75%" width="100%" alt="personal computer issues"/>
  
</p>
<p>
  Equipment Request.
  <img src="https://imgur.com/7HJub1i.png" height="75%" width="100%" alt="equipment request"/>
</p>
<p>
  Password Reset.
  <img src="https://imgur.com/77tHUMk.png" height="75%" width="100%" alt="password reset"/>
</p>

<br />
<br />
<p>
  And that's it! This now fully configures our osTicket. I hope this guide was able to help clarify and assist you in setting up your osTicket. You can practice triaging and solving tickets.
</p>
<p>
  I believe this is a very important skill to have for any help desk specialist, as they are the first line of communication between a company and it's customers when it comes to handling issues regarding a product or service they provide.
</p>




