<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### <p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Create Azure Virtual Machine Windows Account</h2>

- Log into the VM and Remote Desktop
-   Download the os ticket-installation-File-Zip onto my desktop
-   Install/Enable IIS in Windows with CGI
-   From the OS Ticket Installation File/Folder I will install PHP Manager for IIS, Rewrite Module, VVC_redist.x86.exe, and MySQL 5.5.62, then I would  unzip PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) into the “C:\PHP” folder. Create Username and passwords
-   Open IIS as an Admin
-   Register PHP from IIS, then Reload IIS
-   Install OS Ticket - from here being in the osticket-installation-file-folder I would unzip osTicket-v1.15.8.zip” and copy the “upload” folder into “c:\inetpub\wwwroot”
-   Reload IIS and go to the OS Ticket site - right click on Browse. I would have to rename ost-config From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php To: C:\inetpub\wwwroot\osTicket\include\ost-config.php
-   Assign permission to ost-config.php - I would disable inheritance - remove all, and give permission to all
-   Install  HeidiSQL from the OS Ticket Folder
-   Open Heidi SQL, create a new session, connect to the session and then create a database called "OS Ticket" continue to complete this where I;m setting up my SQL database, username and password. Then I will Install

<p>
<img width="2539" height="1262" alt="image" src="https://github.com/user-attachments/assets/cf9a767c-ea52-4cee-836f-7f5e97a6765c" />

Installation and Post Set Up - making sure that all sites are working properly 
-    This includes Admin/Analyst page
-    End Users Tab
-    Agent Panel and Admin Panel - creating accounts that includes passwords and access
-    Configuring Roles/Permissions, Department, Teams, Agents/Users, Service Level Agreement (SLA), and Help Topics (includes grace periods 1, 4, and 8 hours that are scheduled within 24 hour/business hours) - creating accounts that includes passwords, access to different departments/Online Banking

<img width="975" height="756" alt="image" src="https://github.com/user-attachments/assets/a165ad1e-7b80-4543-b9b4-064f5d37ab4f" />


<img width="752" height="231" alt="image" src="https://github.com/user-attachments/assets/db801e0c-c72d-460c-9274-3fca97197a5a" />


<img width="975" height="348" alt="image" src="https://github.com/user-attachments/assets/28ee60de-a3ef-4384-ba28-1020e3bfa660" />

<img width="975" height="647" alt="image" src="https://github.com/user-attachments/assets/09fd9b57-1786-49a2-bc62-dcbf64fab4af" />

<img width="975" height="403" alt="image" src="https://github.com/user-attachments/assets/52b71f13-93d5-4db3-8230-95634f91a558" />

<img width="975" height="590" alt="image" src="https://github.com/user-attachments/assets/770ea6f9-5999-467b-8b65-c05a78f5044d" />

Creating Tickets inside of OS Ticket under a End User

- Pretending to be a User I will create a issue in the OS Ticket site in the portal section, this includes the priority, department, service level agreement, and assign the ticket to a admin department.

<img width="975" height="481" alt="image" src="https://github.com/user-attachments/assets/d9fec5e3-6ccd-4df2-a243-91cc15512753" />

Help Desk Agent - I'm the agent now and I log into admin role and I look at the ticket I would see all comments related to the issue which was reported. "Online Banking branch is offline" I as the admin would test as the Read Only access, contacted end users to confirm that the entire system is down, stated this is "Business Critical" escalated to System Admin department. 

- The online backing system backend server was accidentally restarted during business hours due to the configuration issue, as the team will check the settings and attempt to restart the system. While continuing with the restart the servers have successfully came back online, as this ticket is successfully Resolved

<img width="975" height="355" alt="image" src="https://github.com/user-attachments/assets/6a9292ad-ba34-47f1-b9aa-fe9f94a47001" />
















