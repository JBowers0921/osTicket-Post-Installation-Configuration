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
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/YcAcSsI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In order to begin Post Installation Setup, log into Azure and connect remotely to VM1 (created in Pre-Instalation). Open a browser to your osTicket login page: http:/localhost/osTicket/scp/login.php. (lab training link). Use your credentials from the previous Installation step.
</p>
<br />

<p>
<img src="https://i.imgur.com/nwUuxsr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After loggin in, you will be on the "AGENT" panel. Go to the upper left and click on "Admin Panel" to display the Systems Settings screen.
</p>
<br />

<p>
<img src="https://i.imgur.com/OlZZVaV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To add Roles, from the Admin Panel, select the Agents tab, then Roles and then click on "+Add New Roles".
</p>
<br />

<p>
<img src="https://i.imgur.com/VqqzIZO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/QoqIK6B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
On the next screen, add the name of an agent of your choosing on the Definition tab, select the Permissions tab. Add the desired Tickets, Tasks And Knowledgebase selections and click "Add Role" . The next pop up will show the role you added.
</p>
<br />
<p>
<img src="https://i.imgur.com/taYvRMW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To add Departments, from the Admin Panel, select the Agents tab, then Departments and then click on "+Add New Departments". Name the department. Leave all other default settings as-is for now. Click "Create Department"
</p>
<br />
</p>
<br />
<p>
<img src="https://i.imgur.com/YlFn7IZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You should see a "successfully added" notificationd and see the new depaprtment under "Name" on the screen.
  </p>
<br />
<p>
<img src="https://i.imgur.com/FzEBFBX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To add Teams, from the Admin Panel, select the Agents tab, then Teams and then click on "+Add New Team". Name the Team. Add Members if you choose. Leave all other default settings as-is for now and click "Create Team"

<p>
