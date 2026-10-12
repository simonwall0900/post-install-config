<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This Project outlines the Post-installation configuration of the help desk ticketing system osTicket. It covers the essential configuration tasks required after instlling osTicket, including system settings, user roles, departments, permissions, and other administrative featres needed to prepare osTicket for day-to-day IT support.  <h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Create a Azure Virtual Machine
- Log into VM with Remote Desktop
- Install/Enable IIS
- Create the directory 
- Install osTicket

<h2>Configuration Steps</h2>

<p>
<img width="1284" height="753" alt="IMG_5039" src="https://github.com/user-attachments/assets/940b6cd9-b383-4fa5-b763-034ca56896a8" />

</p>
<p>
To begin the osTicket deployment process, I created a Virtual Machine (VM) to serve as the environment for installing and configuring the application.

VM Setup Process Created and provisioned the Virtual Machine. Installed the required operating system on the VM. Connected to the VM using Remote Desktop (RDP). Prepared the VM for the osTicket installation. Began installing the required software dependencies and configuring the system. Understanding Virtual Machines

A virtual machine is a computer system that runs inside another physical computer. It has its own operating system, storage, memory, and network configuration.

For example, a Windows virtual machine can be created and used on a Mac computer without replacing the Mac's operating system.

Result

The virtual machine was successfully created and configured as the installation environment for osTicket. This provided an isolated system where the required software could be installed and the help desk application could be deployed and tested.
</p>
<br />

<p>
<img width="1284" height="731" alt="IMG_5040" src="https://github.com/user-attachments/assets/8bc04a66-87ad-4d8a-a451-164e5b93be85" />

</p>
<p>
To access and manage the Windows Virtual Machine, I used Remote Desktop Protocol (RDP). RDP allowed me to connect to the VM remotely and interact with the Windows operating system.

Remote Desktop Process Opened the Remote Desktop application on my computer. Entered the IP address or hostname of the Windows VM. Entered the required login credentials. Connected to the Windows VM through the Remote Desktop session. Used the remote Windows environment to install and configure the software required for osTicket. Result

The Remote Desktop connection provided remote access to the Windows VM, allowing me to manage the system as if I were physically working on the machine. This allowed me to complete the osTicket installation and configuration remotely.
</p>
<br />

<p>
<img width="882" height="495" alt="IMG_5041" src="https://github.com/user-attachments/assets/dfcbe13b-e1ee-4b2e-a2cc-090ed1a4aa22" />

</p>
<p>
Internet Information Services (IIS) was used as the web server for the osTicket application. IIS processes web requests and provides the environment needed for osTicket to run on the Windows virtual machine.

IIS Configuration

IIS was configured to:

Host the osTicket website and application files. Process incoming web requests. Manage website resources. Support the services required for osTicket to operate. Provide access to the osTicket application through a web browser. Result

IIS was successfully configured to support the osTicket environment. This allowed the Windows VM to host the application and respond to web requests from users accessing the help desk system.


</p>
<br />
