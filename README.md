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

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
With the osTicket configuration complete, we can now set up new roles and teams within the ticketing system, each with different access levels to manage tickets.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure new roles, go to the admin panel, navigate to the Agents tab, and select 'Add Role.' The user's access level depends on whether they are an agent or an admin.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure departments, go to the admin panel, navigate to the Agent tab, and select 'departments.' Example departments include Help Desk, SysAdmins, and Networking. 

</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure teams, go to the admin panel, navigate the Agent tab, and select 'teams.' This would allow collaboration between multiple departments. 

</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The current osTicket system only allows registered users to generate a ticket. In order to change that head over to the Admin Panel, navigate the settings tab, then user settings, and uncheck the option 'require registration and login to create tickets.' This would allow unregistered users to submit tickets without through email, phone call, and portal. 

</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure agents, go to the Admin Panel, navigate the Agent tab, and select add new. User information such as agent's name, email, assigned role, department, and permissions will be filled out here. 

</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure customer, go to the Admin Panel, navigate the users tab, and select add new. Enter the customer's name and email and they will be able to simulate ticket creation.

</p>
<br /># post-install-config


