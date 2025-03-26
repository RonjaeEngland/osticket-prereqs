<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- PHPmangerforIIS_1.5.0
- rewrite_amd64_en-US
- php-7.3.8-nts-win32-VC15-x86
- VC_redist.x86
- Mysql-5.5.62-win32
- osTicket-v.1.15.8
- Heidi5Q_12.3.0.6589_Setup

  
<h2>Installation Steps</h2>

<p>
</p>
<p>
Create an Azure Virtual Machine Windows 10, 4 vCPUs
</p>
<br />

<p>
<img width="633" alt="image" src="https://github.com/user-attachments/assets/eab6fcfc-fd78-4874-b094-ba53d44ff0af" />

</p>
<p>
Log into the VM with Remote Desktop<br />
<img width="308" alt="image" src="https://github.com/user-attachments/assets/e7231e0d-884b-49fc-87c0-d27fefb770b5" />

Install / Enable IIS in Windows WITH CGI

<img width="343" alt="image" src="https://github.com/user-attachments/assets/30596492-0386-42b5-bdb4-931e375945a2" />

install PHP Manager for IIS

<img width="319" alt="image" src="https://github.com/user-attachments/assets/30e87b21-ce42-44a3-bd87-4eb92037a580" />

install the Rewrite Module

<img width="318" alt="image" src="https://github.com/user-attachments/assets/022e8f44-ffd5-4a42-8280-d1de19babf5a" />

Create a new folder name "PHP" put it on the locate C:drive and extract php-7.38-nts-win32-VC15-86 into it

<img width="473" alt="image" src="https://github.com/user-attachments/assets/61f966b3-4e71-4ca5-b998-aa9c5d421a34" />

Install VC_redist.x86

<img width="323" alt="image" src="https://github.com/user-attachments/assets/81e8b32d-0dc6-47cf-bfad-c4e7f75968e3" />

install MySQL 5.5.62 (mysql-5.5.62-win32.msi)

<img width="323" alt="image" src="https://github.com/user-attachments/assets/5d7d83a0-dfe8-47fd-82a2-5bbf1c13ddd7" />

Open IIS as an Admin

<img width="255" alt="image" src="https://github.com/user-attachments/assets/9f4cff4d-a7c0-490a-b6dd-9740f705021f" />

Register PHP from within IIS (PHP Manager -> C:\PHP\php-cgi.exe)

<img width="510" alt="image" src="https://github.com/user-attachments/assets/be5c5e34-f4e2-443f-b65a-ad50d7677aa2" />

Reload IIS (Open IIS, Stop and Start the server)

<img width="949" alt="image" src="https://github.com/user-attachments/assets/3ace2911-237a-4a12-8ac3-5fe8495dd613" />


Install osTicket v1.15.8
From the “osTicket-Installation-Files” folder, unzip “osTicket-v1.15.8.zip” and copy the “upload” folder into “c:\inetpub\wwwroot”
Within “c:\inetpub\wwwroot”, Rename “upload” to “osTicket”

<img width="318" alt="image" src="https://github.com/user-attachments/assets/185719cf-4dfb-49a7-99f5-7b69f21b62ee" />

<img width="446" alt="image" src="https://github.com/user-attachments/assets/6597aaf9-0a42-43f8-8502-083c7a1994d9" />

<img width="461" alt="image" src="https://github.com/user-attachments/assets/91e47a50-43d4-40f5-bdd7-53052a03208a" />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
