<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This guide outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- HeidiSQL

<h2>Operating Systems Used </h2>

- Windows 10</b>

<h2>List of Prerequisites</h2>

- The first thing that you will start off doing is creating a resource group.
- Next, you will need to create a virtual machine within the newly created resource group.
- Once you have created your virtual machine and resource groups, the next step will be to log into your newly created virtual machine using Remote Desktop Connection. Locate your virtual machines public IP address and use it to log into the Remote Desktop Connection. You will also want to enable IIS through pc settings.
- Once you are logged into your virtual machine via Remote Desktop, you shall install all the required files for OsTicket which consist of the following files: HeidiSQL, MySQL, OsTicket, php-7.3.8, PHP Manager for IIS, rewrite and VC_redist. Install all files using standard configurations.
- Using HeidiSQL, set up password for OsTicket.
- Log into OsTicket using the username and password you created in SQL and you should be ready to begin using OsTicket!

<h2>Installation Steps</h2>


</p>
<p>
STEP 1: First step is to create a resource group.
</p>
<br />

<p>
<img src="https://i.imgur.com/EFZmwZ7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 2: The next step will be to create a virtual machine within the resource group that you just created.
</p>
<br />

<p>
<img src="https://i.imgur.com/NvlHDuc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 3: Next, you will be required to install all of the following files as depicted in the illustration below.
  The files consist of: HeidiSQL, MySQL, OsTicket, php-7.3.8, PHP Manager for IIS, rewrite and VC_redist. Install all files using standard configurations.
</p>
<br />

<p>
<img src="https://i.imgur.com/Y138nFI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 4: You will want to enable CGI in Windows features. Go to Control Panel> Programs> Turn windows features on or off> World Wide Web Services> Application Development Features> CGI.
</p>
<br />

<p>
<img src="https://i.imgur.com/uPyjJh7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 5: Enable php-cgi through the Internet Information Services (IIS) for the OsTicket system.
</p>
<br />

<p>
<img src="https://i.imgur.com/9It4kT1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 6: For the last steps, you will use HeidiSQL to create a username and password for OsTicket. Afterwards, you should be all ready to log in and begin using OsTicket!
</p>
<br />

<p>
<img src="https://i.imgur.com/h0X3VGe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/4FfZDFH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Good luck!
