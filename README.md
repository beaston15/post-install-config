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

- Roles
- Departments
- Teams 
- Agents
- Users
- SLA
- Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/Au4ThmA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1: Login into the Admin Panel on osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/seLYyDO.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2: Under the "Agents" tab click on "Roles" then "Add New Role". Create an admin named "Supreme Admin" that has access to all tasks and permissions. 
</p>
<br />

<p>
<img src="https://i.imgur.com/ycB3uFO.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3: In the "Departments" tab, add a new department. Create a new department named "System Administrators".
</p>
<br />

<p>
<img src="https://i.imgur.com/UQYFGas.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 4: In the "Teams" tab, create a new team. Create a new team named "Level II Support".
</p>
<br />

<p>
<img src="https://i.imgur.com/u5aW03e.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 5: Click the "Settings" tab in the admin panel. In Settings go to the "Users" tab and enable the "require registration and login to create tickets". This will allow anyone that can login to create tickets. 
</p>
<br />

<p>
<img src="https://i.imgur.com/PEGmsA2.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 6: Go back to the "Agents" tab and in the "Agents" subsection click "Add New Agent". Give this agent the "Supreme Admin" role and put them into the "System Administrators" Department.
</p>
<br />

<p>
<img src="https://i.imgur.com/kfATpT5.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 7: Click the "Agent Panel" on the top right of the screen. Once in the agent panel under the "Users" tab click "Add User". When creating this user you can give this user any access, department, and team that you wish to give them.
</p>
<br />

<p>
<img src="https://i.imgur.com/nuPrldq.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 8: Go back to the Admin Panel. In the Admin Panel under the "Manage" tab click "SLA". Add a new SLA plan.
</p>
<br />

<p>
<img src="https://i.imgur.com/kg69Fmk.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 9: Create a couple SLA's. While creating them you can choose a "Grace period" which will allow you to show how urgent the tickets need to be completed and what days the tickets need to be completed on, for example 24/7 or business days.
</p>
<br />

<p>
<img src="https://i.imgur.com/VGJGkOi.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 10: Under "Help Topics" create a new help topic. When creating a help topic you can choose what department the ticket will be given too as well as what priority the ticket will have. 
</p>
<br />

<p>
<img src="https://i.imgur.com/1a4B0EJ.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As shown is the new help topics with their priority and departments they are assigned to.
</p>
<br />
