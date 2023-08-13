<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
Installing osTicket on Microsoft Azure through a Remote Desktop connection involves utilizing Azure's virtual machine (VM) services and accessing the VM using Remote Desktop Protocol (RDP). Here's a step-by-step guide on how to set up osTicket using Azure's services and accessing the VM via Remote Desktop

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

1. Set Up a Virtual Machine (VM)
  2. Remote Desktop Connection
  3. Prepare the Environment
  4. Download osTicket
  5. Database Setup
  6. Install osTicket via Web Interface
     

<h2>Installation Steps</h2>

<p>
<img width="1250" alt="Screenshot 2023-08-01 at 8 29 00 PM" src="https://github.com/AhbasShah/VirtualMachine/assets/141075365/7a663d27-2245-4770-888d-905a2e5d8087">
</p>
<p>
Log in to the Azure Portal.
Click on "Create a resource" and select "Virtual Machine."
Fill out the VM details, including OS (choose Windows Server) and configuration.
Set up the networking settings, including a public IP address.
Once your VM is deployed, make sure you note down the public IP address, as you'll need it to connect via RDP.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On your local machine, search for "Remote Desktop Connection" (or use an alternative RDP client).
Enter the public IP address of your Azure VM.
Provide the username and password you set during VM creation.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once connected to the VM through Remote Desktop, you're inside the VM's environment.
Install a web server, database server, and PHP (such as XAMPP or WAMP for Windows).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Inside the VM's Remote Desktop session, open a web browser.
Navigate to the official osTicket website.
Download the latest version of osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Set up a MySQL server or use an existing one.
Create a database and user for osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open a web browser within the VM's Remote Desktop session.
Navigate to the VM's public IP address or domain name.
Follow the on-screen instructions in the osTicket installation page, providing the necessary database and admin user details.
</p>
<br />






