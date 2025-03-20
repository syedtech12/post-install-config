<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%"alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />
<h2>Environments and Technologies Used</h2>

- Microsoft Azure Cloud (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

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
  Senior Admin:
  </p>
<p>
  <img src="https://i.imgur.com/NiBa1nD.png" height="75%" width="100%" alt="Definitions"/>
  <img src="https://i.imgur.com/kxmUizV.png" height="75%" width="100%" alt="Permissions"/>
  <img src="https://i.imgur.com/x5Re1Gm.png" height="75%" width="100%" alt="More Permissions"/>
  <img src="https://i.imgur.com/0tdX2mB.png" height="75%" width="100%" alt="Even More Permissions"/>
  <img src="https://i.imgur.com/hNgwaAA.png" height="75%" width="100%" alt="Sys Admin Success"/>
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
  <img src="https://i.imgur.com/nEoB5i9.png" height="75%" width="100%" alt="System Administrators"/>
  <img src="https://i.imgur.com/h7NHeHW.png" height="20%" width="100%" alt="System Administrators"/>
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
  <img src="https://i.imgur.com/C96XlDs.png" height="75%" width="100%" alt="Level II Support"/>
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
  <img src="https://i.imgur.com/dyZ30cJ.png" height="75%" width="100%" alt="ticket creations"/>
</p>
<br />
<br />
<h3 align="center">Configure Agents (workers)</h3>
<br />
<p>
  Admin Panel -> Agents -> Add New.
</p>
<p>
  Jane Doe (Senior Admin):
</p>
  <img src="https://i.imgur.com/PF6vVnC.png" height="75%" width="100%" alt="agent one access"/>
<p>
  John Doe (Support):
</p>
<p>
  <img src="https://i.imgur.com/DTxirsn.png" height="75%" width="100%" alt="agent two"/>
  <img src="https://i.imgur.com/Wa3I6GB.png" height="75%" width="100%" alt="agent two access"/>
</p>
<h3 align="center">Configure Users (customers)</h3>
<br />
<p>
  Admin Panel -> Users -> Add New.
</p>
<p>
  Ken User:
</p>
  <img src="https://i.imgur.com/BpMBxta.png" height="75%" width="100%" alt="user access"/>
<p>
  Repeat the same above for Karen User.
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
  <img src="https://i.imgur.com/uJvM0ZG.png" height="75%" width="100%" alt="sev one"/>
  <img src="https://i.imgur.com/MtwzeAm.png" height="75%" width="100%" alt="sev two"/>
  <img src="https://i.imgur.com/fWTuzS7.png" height="75%" width="100%" alt="sev three"/>
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
</p>
<p>
  Personal Computer Issues.
</p>
<p>
  Equipment Request.
</p>
<p>
  Password Reset.
</p>
<p>
  <img src="https://i.imgur.com/5cIlsC5.png" height="75%" width="100%" alt="business critical outage"/>
  <img src="https://i.imgur.com/Jin9OgY.png" height="75%" width="100%" alt="personal computer issues"/>
  <img src="https://i.imgur.com/6KYZAVD.png" height="75%" width="100%" alt="equipment request"/>
  <img src="https://i.imgur.com/8rhU5Fx.png" height="75%" width="100%" alt="password reset"/>
</p>
<br />
<p>
  This now fully configures our osTicket. I hope this guide was able to help clarify and assist you in setting up your osTicket. It is recommended to practice triaging and solving tickets.
</p>
<p>
  This is a very important skill to have for any help desk specialist, as they are the first line of communication between a company and it's customers when it comes to handling issues regarding a product or service they provide.
</p>
