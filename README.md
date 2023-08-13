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
<img width="615" alt="Screenshot 2023-08-13 at 4 20 44 PM" src="https://github.com/AhbasShah/osticket-prereqs/assets/141075365/34c95703-d482-4f3c-9721-e28a38dcfbbd">
</p>
<p>
On your local machine, search for "Remote Desktop Connection" (or use an alternative RDP client).
Enter the public IP address of your Azure VM.
Provide the username and password you set during VM creation.
</p>
<br />

<p>
<img width="856" alt="Screenshot 2023-08-13 at 6 34 31 PM" src="https://github.com/AhbasShah/osticket-prereqs/assets/141075365/80b0bc18-1206-4a0c-988c-5afdb65f5a06">
</p>
<p>
Once connected to the VM through Remote Desktop, you're inside the VM's environment.
Install a web server, database server, and PHP (such as XAMPP or WAMP for Windows).
</p>
<br />

<p>
<img width="543" alt="Screenshot 2023-08-13 at 6 36 39 PM" src="https://github.com/AhbasShah/osticket-prereqs/assets/141075365/8d40f3dc-0897-4646-b514-6592abcc50ed">
</p>
<p>
Inside the VM's Remote Desktop session, open a web browser.
Navigate to the official osTicket website.
Download the latest version of osTicket.
</p>
<br />

<p>
<img width="318" alt="Screenshot 2023-08-13 at 6 44 28 PM" src="https://github.com/AhbasShah/osticket-prereqs/assets/141075365/e58237d8-2b66-4cf0-b342-ed2309d58f15">
</p>
<p>
Set up a MySQL server or use an existing one.
Create a database and user for osTicket.
</p>
<br />

<p>
<img width="538" alt="Screenshot 2023-08-13 at 6 48 09 PM" src="https://github.com/AhbasShah/osticket-prereqs/assets/141075365/ce70abc5-c61f-4bf0-b6a8-f004fdfb65d9">
</p>
<p>
Open a web browser within the VM's Remote Desktop session.
Navigate to the VM's public IP address or domain name.
Follow the on-screen instructions in the osTicket installation page, providing the necessary database and admin user details.
</p>
<br />






