<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

-OS: Windows 10
-Web Server: Apache 2.4
-PHP Version: 8.1
-Database: MySQL 
-Email Server: Gmail SMTP (or an internal mail server)


<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Azure Resource Group
- Azure Virual Machine 
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Setting up a Virtual Machine in Azure for osTicket Installation
Log in to Azure Portal

Navigate to Azure Portal.
Ensure you have sufficient permissions to create resources.
Create a New Virtual Machine

Go to the Virtual Machines service.
Click + Create and select Azure Virtual Machine.
Configure Basic Settings

Subscription: Select your Azure subscription.
Resource Group: Create a new resource group or select an existing one.
Virtual Machine Name: Provide a descriptive name, e.g., osTicketVM.
Region: Choose the region closest to your users or infrastructure.
Image: Select a Windows Server image (e.g., Windows 10 Pro ).
Size: Choose a VM size based on your performance needs (e.g., Standard_B2s for small setups, I personally recommend Standard_D2sv3 or whatever is available in your selected Zone at minimum of 2vcpus with 8 GiB for speed).

Administrator Account

Set a username and password for accessing the VM.
(****Ensure you save these credentials securely as they will be used for Remote Desktop Protocol (RDP) access.)

Disk Configuration 

Use the default managed disk or adjust based on storage requirements.

Networking Configuration

Configure the network interface:
Ensure a new Virtual Network was autmatically created [\ it should reflect (new)*nameofosticketvm-vnet*]
Subnet leave at default
Public IP will generage a new ip once deployed
NIC: Basic
Public Inbound Ports: Allow Selected Ports
Ensure RDP (Port 3389) is open in the inbound rules for remote desktop access.

Storage Configuration


Review and Create the VM

Review your settings and click Create to deploy the VM.

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
