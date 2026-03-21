<h1>Active Directory</h1>

<h2>Description</h2>
This project demonstrates the deployment of a Windows Server 2025 instance in AWS and remote administration using Remote Desktop Protocol (RDP). Within the environment, Active Directory is configured to manage users by creating accounts, assigning group memberships, resetting passwords, and unlocking locked accounts. This lab highlights foundational system administration and identity management skills in a cloud-based environment.
<br />


<h2> Utilities Used</h2>

- <b>Amazon Web Services (AWS) EC2</b>
- <b>Windows Server 2025</b>
- <b>Active Directory Domain Services (AD DS)</b>
- <b>Remote Desktop Protocol (RDP)</b>

<h2>Environments Used </h2>

- <b>Amazon Web Services (Cloud Environment)</b>
- <b>Windows Server Enviornment (Active Directory Domain)</b>
- <b>Local Windows Machine (for RDP access)</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch AWS Windows2025 EC2 Instance: <br/>
<img src="https://i.imgur.com/Hrvhzd5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
RDP from personal computer to Windows2025 EC2 Instance:  <br/>
<img src="https://i.imgur.com/HR8yBUr.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating new user: <br/>
<img src="https://i.imgur.com/JxlPhxc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
New User = John Doe:  <br/>
<img src="https://i.imgur.com/5QbmNgb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created new group (IT New Hire) | Added user (John Doe) to new group:  <br/>
<img src="https://i.imgur.com/HAPazka.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Resetting user password:  <br/>
<img src="https://i.imgur.com/fWVGqfR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Unlocking users account, requiring password change at next login:  <br/>
<img src="https://i.imgur.com/QAN22Ik.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
