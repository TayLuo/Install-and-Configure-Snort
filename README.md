# Introduction-with-Snort
This is an introduction of Snort. The following guide will show how to install Snort, 
configure and write custom rules. Snort has three primary uses: As a packet sniffer 
like tcpdump, as a packet logger — which is useful for network traffic debugging, 
or it can be used as a full-blown network intrusion prevention system.
If you want to learn more about Snort, click [here](https://www.snort.org/)

- [Introduction of the Project](https://github.com/TayLuo/Deploy-Windows-VM----Sentinel-SIEM-/blob/main/The%20purpose%20of%20the%20Project)

<h2>Prerequisites</h2>

- <b>Create Resource Group</b> 
- <b>Virtual Machine</b>
- <b>Log Analystic Workspace</b>
- <b>Microsoft Sentinel</b>

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
