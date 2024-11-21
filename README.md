<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1> Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Preparing AD infrastructure in Azure
- Deploying Active Directory
- Creating Users with Powershell
- Group Policy and Managing Accounts

<h2>Deployment and Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/c1c64a9f-8603-4112-9bfe-8a4f1a40f3c5)

<p>
 Create a resource group , virtual network and virtural machince containing the virutal network as your newtork domain. Once the virtual netowrk is created you want to set the IP address of your domain to be static in the "Edit IP Configuration" section ( shown in picture). Once that is completed you can sign into the domain with the user and password that you created when setting up the virtual machince credentials. 
  
</p>
<br />

![image](https://github.com/user-attachments/assets/d6020c7c-8ffb-41e4-8ba7-22b33d810b00)

![image](https://github.com/user-attachments/assets/4d5f8b5c-d544-4099-a5d4-3f782bea4639)

![image](https://github.com/user-attachments/assets/fc8ecf86-7e1a-48ad-8889-86ac85eceb28)

![image](https://github.com/user-attachments/assets/47655bb7-6a96-4a8f-944b-18cd226a55f8)

<p>
First we want to remote into DC-1 with the remote IPaddress and install Active Directory Services. Click on add roles and features -> Active Directory Servers. Once the domain is made from the branch right click on the domain -> New -> Organzational Unite (OU). Then create two OU's one named "_Admins" and  "_Employees". In the Admins OU create a new user named "Jane Doe" and added her to the "Domain Admins" security group
</p>
<br />

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

