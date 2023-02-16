<p align="center">
<img src=https://i.imgur.com/uC0VxMv.png alt="Traffic Examination"/>
</p>

<h1>Network File Shares and Permissions</h1>
In this lesson, we'll use Wireshark to monitor various network traffic going to and coming from Azure Virtual Machines and practice using Network Security Groups. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Shared Network Files
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Windows Server 2022 (Azure Edition)


<h2>Actions and Observations</h2>

<p>
<img src= https://i.imgur.com/Y1jB16x.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We will setup shared network files and permissions in this lab. We'll make folders in the DC-1 VM and share them over to the network, and specific files will have specific rights.Specific rights such as, read, write, no access, and accounting. Log into your DC Vm as an Admin, then log into your CLient Vm as non admin user from under your employees file in Server manager. Go into your DC VM-> windows c file-> create 4 folders in the name of read, no access, and accounting.  
</p>
<br />

<p>
<img src=https://i.imgur.com/3BcBiv4.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we will Assign the "Domain Users" group the following rights. On the Domain Controller Vm, set permission for read access folder by a right click then tap properties-> share-> add group domain users-> set permission to read. For write access folder, add domain users as the group-> set permission for read/write. For no-access folder, add domian admins as the group-> set permission for read/write.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
