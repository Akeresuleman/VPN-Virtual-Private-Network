<p align="center">
<img src="https://cdn.vectorstock.com/i/preview-1x/55/49/internet-vpn-shield-icon-vector-47035549.webp.png" alt="osTicket logo"/>
</p>

<h1>VPN Setup and Utilization</h1>
This project is to show how to setup a vpn inside a virtual machine and use it to remotely change our geographic location.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Use VPN](https://youtu.be/6J7ASqxDAZs)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- VPN provider(Proton VPN)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Setup a virtual machine running windows 10 os and name in VM1
- Take Note of the location of the Virtual machine
- Login VM1 using remote destop on my local computer
- Setup a vpn traffic tunnel using proton vpn and connect it to different locations

<p>
  
<img src="https://imgur.com/kYpXSjF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The image above show a validation page of the virtual machine(VM1) I created running windows 10 and West US 3 as the location of the virtual machine.
I then login to the vm using the remote desktop application on my local computer. 
</p>
<br />


<p>
<img src="https://imgur.com/RzuSoCO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/xwvvE1P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/
</p>
<p>
After login in to the vm successfully using the RD,I verified the geographical location associated with the IP address of my vm inside RD VM and later verified that of my local computer as well on the local computer it self by using the website "whatismyip.com". The geographical location of my VM shows that I am in Arizona United States while that of my local computer is Lodon United Kingdom since that's my present location as shown on the two images above
</p>
<br />


<p>
<img src="https://imgur.com/Ejotenn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
<img src="https://imgur.com/GgtwCAr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://imgur.com/tHwIyqf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Setup a VPN traffic tunnel using proton vpn. downloaded, installed and setup Proton vpn and connected to different location, that is Japan and Netherlands respectively and and also verify their geographical location using "whatismyip.com" and noticed they all reflect to the location to which the proton vpn was connected.
Therefore VPN can be used to by pass geographical restrictions and also enable remote access to private networks. The images above shows the geographic location of the vm when the proton vpn is connected to Japan and Netherland
</p>
<br />
