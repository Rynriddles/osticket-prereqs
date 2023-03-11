<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1: Create a virtual machine in azure with the windows 10 operating system
- Item 2: Create a PHP directory. Download PHP files and place them in that folder
- Item 3: Enable PHP within IIS
- Item 4: Download OSTicket and place the upload folder into inetpub\wwwroot folder
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/7exdQ2O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The first thing that we need to do is create a virtual machine in azure. We create this machine with the windows 10 operating system. We will then remote desktop into the virtual machine. 
</p>
<br />

<p>
<img src="https://i.imgur.com/O7JJIEc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/0JDaPFv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
</p>
<p>
We then open the control panel and navigate to programs. From there, we select "turn windows features on and off". We navigate to IIS (internet information services) and enable the CGI option. This will allow us to install PHP manager. 
</p>
<br />

<p>
<img src="https://i.imgur.com/MNiBg7T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we open IIS and register PHP from inside IIS. 
</p>

<p>
<img src="https://i.imgur.com/Cjby5js.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We download OSTicket. When OSTicket is downloaded, we extract the upload folder into the inet>wwwroot folder.  
</p>

<p>
<img src="https://i.imgur.com/Cjby5js.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We download OSTicket. When OSTicket is downloaded, we extract the upload folder into the inet>wwwroot folder.  
</p>

<br />
