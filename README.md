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
To add Departments, from the Admin Panel, select the Agents tab, then Departments and then click on "+Add New Departments". Name the department. Leave all other default settings as-is for now. Click "Create Department".
</p>
<br />
</p>
<br />
<img src="https://i.imgur.com/YlFn7IZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You should see a "successfully added" notification and see the new department under "Name" on the screen.
  </p>
<br />
<p>
<img src="https://i.imgur.com/FzEBFBX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To add Teams, from the Admin Panel, select the Agents tab, then Teams and then click on "+Add New Team". 

<p>
<img src="https://i.imgur.com/F9Nsk93.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
  
On the screen above, Name the Team. Add Members if you choose. Leave all other default settings as-is for now and click "Create Team".
<p>
<img src="https://i.imgur.com/ws8iWdj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
 The above screen will show your "successfully added" notification.
 </p>
<p>
  
<img src="https://i.imgur.com/ZNHFC0W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
After creating teams, you would need to allow anyone to create tickets. From the admin panel, go to Settings > User > User Settings. Uncheck the "Registration Required" box and then select "Save Changes"
</p>
<br />
 </p>
<p>
  <img src="https://i.imgur.com/TmKEYUP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
Next, in order to configure Agents, from the admin panel, go to Agents > +Add New Agent. Fill in the account information and select "set Password".
<p>
<br />
</p>
<p>
  <img src="https://i.imgur.com/OoeYSKo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
Next, in the "Set Password" window, un-check both boxes and then add the new password, confirm it and click "Set".
<p> 
<br />
</p>
<p>
  <img src="https://i.imgur.com/dnV1Ltv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
You have now added an Agent.  After adding the agent, you can make your selections from the Access , Permissions and Teams Tabs and Create/ Save. Repeat the previous steps to add more agent accounts.
<br />
</p>
<p>
 <img src="https://i.imgur.com/do8XUBT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
 <img src="https://i.imgur.com/4tVe8eJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<p>
After setting up the Agent(s) accounts, you can now configure the Users (customers). From the AGENT panel, go to User > +Add User. Fill in the account information and select "Add User" Repeat the previous steps to add more User accounts.  
<p> 
<br />
</p>
<p>
  <img src="https://i.imgur.com/imjQ6Ua.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
The next step will be to add SLAs (Service Level Agreements). From the ADMIN Panel, go to Manage, from the drop down menu, select SLA. Open it and select add New SLA Plan. Name the plan, add a grace period and a schedule, select "Add Plan" 

 
  <img src="https://i.imgur.com/HvMoKPT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
  
 Repeat the previous steps to add more SLAs.   
<p> 
<br /
</p>
<p>
  <img src="https://i.imgur.com/bwhceuC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
The final configuration step will be to configure Help Topics. From the ADMIN Panel, go to Manage, Help topics, and click on "+Add New Help Topics". Add the topic desired and click "Add Topic".
   
 <p> 
<br /
</p>
<p>
  <img src="https://i.imgur.com/OsbULJF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
Repeat the previous steps to add more Help Topics.
  
You have now succesfully completed Post Configuration.
</p>
<p>  
