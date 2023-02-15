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

- Windows 10 Virtual Machine with 2-4 Virtual CPUs 
- Windows IIS with CGI
- PHP Manager for IIS
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/iCIyqzo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In Azure, create a Windows 10 virtual machine wich 2-4 virtual CPUs. 
</p>
<br />

<p>
<img src="https://i.imgur.com/kJ0D4bB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Inside the virtual machine, open control panel, navigate to the features panel, and check the IIS box. 
</p>
<br />

<p>
<img src="https://i.imgur.com/hnyN1PU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Use the dropdown boxes to navigate to CGI, and enable it. This is necessary for the installation of PHP manager. Then, click the 'OK' button. 
</p>
<br />
