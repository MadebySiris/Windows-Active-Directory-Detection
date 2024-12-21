# <h1> 🪟 Windows Active Directory Threat Detection </h1>

 ### [Medium Walkthrough](https://youtu.be/7eJexJVCqJo)


## The TDE101 Lab Topology

<img src="https://github.com/collinsmc23/tde101/blob/main/Notes/images/The%20Threat%20Detections%20Engineering%20Project%20101%20Netork%20Toplogy.png" width="751" height="662">


### <h2>TDE101 Breakdown</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
