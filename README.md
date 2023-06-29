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

- Installed / Enabled IIS in Windows WITH CGI and Common HTTP Features AND IIS Management Console
- Downloaded and installed PHP Manager for IIS 
- Downloaded and installed the Rewrite Module
- Created a PHP Directory and downloaded PHP 7.3.8 and unzip the contents into the PHP directory
- Downloaded and installed VC_redist.x86.exe
- Downloaded and installed MySQL 5.5.62
- Downloaded and installed HeidiSQL
- Downloaded and extracted osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://imgur.com/D4PqdIy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is a picture of my freshly created vitual machine called "vmostickets" using microsoft Azure. I will then connect the virtual machine to a remote destop where I will be doing the post installations and setting up osTicket.
</p>
<br />

<p>
<img src="https://imgur.com/7ICu6oJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After signing in my vmostickets using a RD, I installed and enabled IIS in windows with CGI, IIS management console and HTTP features as seen on the picture
</p>
<br />

<p>
<img src="https://imgur.com/1DZQZW1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Dowloaded and installed prerequisite files that will be needed to install osTicket. Created a PHP folder on local disk C where I unzipped "Php7.3 .8" content in to it. After installing all the files I then downloaded and extracted osTicket
</p>
<br />
