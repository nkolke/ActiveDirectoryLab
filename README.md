<h1>Active Directory Home Lab</h1>


<h2>Description</h2>
In this lab I created an Active Directory home lab environment using Oracle Virtual Box. Configuring and running this lab definitely helped develop my understanding of how active directory and windows networking works so I would highly recommed investing time into something like this.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2019</b>  (Domain Controller)
- <b>Windows 10 Pro</b>  (Client)

<h2>Program walk-through:</h2>

<p align="center">
Overview of the end goal: <br/>
<img src="https://imgur.com/rx6HyRV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
Label the NIC's. _INTERNET_ = Connects to the internet(external); X_Internal_X = Connects to internal network: <br/>
<img src="https://imgur.com/yXmOJsd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
Properties of X_Internal_X NIC: <br/>
<img src="https://imgur.com/sTKR7Py.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
Domain is setup: <br/>
<img src="https://imgur.com/zm5lboV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
Made myself an admin in the domain: <br/>
<img src="https://imgur.com/YzJNJqS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
Set up routing and remote access: <br/>
<img src="https://imgur.com/lg1RMEl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
DHCP is set up with the scope: <br/>
<img src="https://imgur.com/CvEae5n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
Scope options: <br/>
<img src="https://imgur.com/LVuGAwb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
Script to add users to the domain using a plaintext file called "names": <br/>
<img src="https://imgur.com/ve9bMR4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
Users added to the domain after running the script: <br/>
<img src="https://imgur.com/1yPT9ld.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
Client successfully connected to the DC and the external internet(can ping google.com): <br/>
<img src="https://imgur.com/KQQW00C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
Client computer is now a part of the domain and can be used by any user that is also a part of the domain: <br/>
<img src="https://imgur.com/btog4Mn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
Client computer has activated the lease of 8 days: <br/>
<img src=https://imgur.com/lfLnFlw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
