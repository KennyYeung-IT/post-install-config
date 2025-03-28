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
With the osTicket configuration complete, we can now set up new roles and teams within the ticketing system, each with different access levels to manage tickets.

</p>
<br />

![image](https://github.com/user-attachments/assets/60088867-5652-4559-8f2a-c3f1db20db38)

<p>
To configure new roles, go to the admin panel, navigate to the Agents tab, and select 'Add Role.' The user's access level depends on whether they are an agent or an admin.

</p>
<br />

![image](https://github.com/user-attachments/assets/57f48c19-e19f-434c-900f-3a436728a1d4)

<p>
To configure departments, go to the admin panel, navigate to the Agent tab, and select 'departments.' Example departments include Help Desk, SysAdmins, and Networking. 

</p>

![image](https://github.com/user-attachments/assets/558daa54-1a74-4233-8364-8cd2a23bc4c2)

<p>
To configure teams, go to the admin panel, navigate the Agent tab, and select 'teams.' This would allow collaboration between multiple departments. 

</p>

![image](https://github.com/user-attachments/assets/3b4f1fcd-5c79-4063-85a4-cf23d122b2bc)

<p>
The current osTicket system only allows registered users to generate a ticket. In order to change that head over to the Admin Panel, navigate the settings tab, then user settings, and uncheck the option 'require registration and login to create tickets.' This would allow unregistered users to submit tickets without through email, phone call, and portal. 

</p>

![image](https://github.com/user-attachments/assets/118c99ec-9480-438e-895b-b55a60ccae3b)

![image](https://github.com/user-attachments/assets/972d8334-e729-48ff-922f-7cc72b6e11d5)

<p>
To configure agents, go to the Admin Panel, navigate the Agent tab, and select add new. User information such as agent's name, email, assigned role, department, and permissions will be filled out here. 

</p>

![image](https://github.com/user-attachments/assets/45181cf4-be26-4cb4-92bc-7086b2084fc5)

<p>
To configure customer, go to the Admin Panel, navigate the users tab, and select add new. Enter the customer's name and email and they will be able to simulate ticket creation.

</p>
<br /># post-install-config


