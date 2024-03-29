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

- Azure Resource Group
- Azure Virtual Machine
- Remote Desktop Connection

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/nj3X1FY.png" alt="1st Image"/>

</p>
<p>
Create a virtual machine in Azure and then connect to it via Remote Desktop connection in your Windows machine. Paste in the public IP address of the Virtual Machine and connect using the username and password you created along with your virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/U8WMMAW.png" alt="2nd Image"/>

</p>
<p>
Next, we must enable IIS (Internet Information Services) on your VM. This will essentially enable the VM to act as a server and host a website. We need this in order to properly run osTicket. Right click on Start, then navigate to Run> Control Panel > Programs > Turn Windows Features on or off > Internet Information Services.
</p>
<br />

<p>
<img src="https://i.imgur.com/667oSs6.png" alt="2nd Image"/> 

</p>
<p>
After setting up all pre-requisite files and installing osTicket using IIS, set up your account like so. Remember to record your information in a notepad so as to not forget your credentials. 
</p>
<br />
