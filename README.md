<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Active Directory Model</h2>

<img src="https://i.imgur.com/h6oWwXc.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>   <img src="https://i.imgur.com/VdApwUY.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>

- Create Resource Group
- Create Virtual Network And Subnet
- Create Domain Controller Virtual Machine (Windows Server 2022) Named DC-1
- Set Domain Controller NIC's Private IP Addresses To "Static"
- Create The Client Virtual Machine (Windows 10) Named "Client-1)


<img src="https://i.imgur.com/8yAGtXV.png" height="70%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/UzSVso4.png" height="70%" width="50%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/2WEiXRd.png" height="70%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Login To "Client-1" And Ping DC-1's IP Address
- The Ping Will Fail
- Login To Domain Controller And Enable ICMv4 On Local Windows Firewall
- Check "Client-1" Again To Make Sure "Ping" Was Successful

</p>
<br />

<p>
<img src="https://i.imgur.com/kBoBzdF.png" height="70%" width="70%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/mN19ET5.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/kyzeDhD.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Login To DC-1, Install Active Directory Domain Services
- Promote As a DC, Create Domain.
- Program Will Restart, Log Back Into The DC

</p>
<br />

<p>
<img src="https://imgur.com/a/agn8Wg1" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/AGx8AHN.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/zu4ldNl.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/2MzDcqu.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>



- In Active Directory Users And Computers, Create An Organizational Unit Called "Employees
- Create A New OU Named "Admins"
- Create A New Employee Named "Jane_Admins"
- Add Jane_Admins To The "Domain Admins"
- Log Out/ Close Connection To DC-1 And Log Back In As "mydomain.com/Jane_Admins"

<br />


<p>
<img src="https://i.imgur.com/nElbLB0.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/6nB8ibl.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/cxsFIkK.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/dC2GubE.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/XiuUM8O.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/cTZIBed.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ib8yhpx.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
