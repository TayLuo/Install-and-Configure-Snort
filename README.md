In this part of project, I will walk you through how to install and configure Snort on a Ubuntu server in [Azure](https://azure.microsoft.com/en-us/get-started/azure-portal), 

You need a trail account to do this project on the Cloud, or you could follow the exactly steps on a VirtualBox.
This project is about install, configure Snort, want to learn more about what Snort can do, click [here](https://www.snort.org/)

1. Sign up an Azure Account, and Create a Ubuntu VM. [Click Here](https://learn.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-portal?tabs=ubuntu)
2. Once follow the previous steps how to create a VM, using a putty or Window PowerShell to access the Virtual Machine.
3. After login, the first thing is to "update" the system, so the new version Snort is compatiable with the VM.
   Run the Following Command:
<p align="center">
<img src="https://imgur.com/HXJid7u.png" height="80%" width="80%" >

4. It is time to install Snort on the Server:
<p align="center">
<img src="https://imgur.com/WsumxTM.png" height="80%" width="80%" >

5. First thing need to find out the interface and the IP address before moving to next:
<p align="center">
<img src="https://imgur.com/F5aTwuz.png" height="80%" width="80%" >

6. After download Snort, a screen will pop out, put the IP range there, click OK
<p align="center">
<img src="https://imgur.com/nQB6jgq.png" height="80%" width="80%" >

7. Verify Snort is downloaded sucessfully and check out its version
<p align="center">
<img src="https://imgur.com/dYeOBeq.png" height="80%" width="80%" >

8. Once everything congifured, type the following command "cd /etc/snort" file
   copy the snort.conf file. (It is always a good practice to copy a configuration file.)
<p align="center">
<img src="https://imgur.com/a0RIvml.png" height="80%" width="80%" >







   
<h2>Prerequisites</h2>

- <b>Create Resource Group</b> 
- <b>Virtual Machine</b>
- <b>Log Analystic Workspace</b>


<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Microsoft Sentinel</b>




<p align="center">
Create Recource Group: <br/>
<img src="https://imgur.com/731vDl5.png" height="80%" width="80%" >
<br />
<br />
<h2>Create Windows Virtual Machine</h2>
Steps to create a VM:  <br/>
Go to Virtual Machine > Create Virtual Machine.
Choose a new Resource Group, set the region (e.g., West US3), and configure the VM details.

<img src="https://imgur.com/m2t3cI1.png" height="80%" width="80%">
<br />
<br />
<img src="https://imgur.com/NapHG6s.png" height="80%" width="80%">
<br />
<br />
<img src="https://imgur.com/gHmPVxV.png" height="80%" width="80%">
<br />
<br />
<b>Security Group Configuration</b> <br /> <br />
