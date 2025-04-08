<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
In this project lab I will be showcasing how to create an Active Directory Home Lab Envionrment using Oracle VirtualBox. Configuirng and running thourgh this lab gave me a better understanding of how active directory and windows networking works. In this lab I did come across a few issues however I was able to work through them. I originally struggled with setting up the virtual machine and to get it to run correctly but I had to tweak a few settings and it eventually worked. I also had an issue with the client machine not being able to ping www.google.com. This was happening because the client was referring to the wrong adapters DNS address. Everything came to together in the end and worked out. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle VirtualBox</b>

<h2>Environments Used </h2>

- <b>Windows 10 ISO</b> 
- <b>Server 2019 ISO</b>

<h2>Project walk-through:</h2>

<p align="center">
Setting up the Internet Adapters on the Domain Controller (DC): <br/>
<img src="https://i.imgur.com/VOX8Y7s.png" height="60%" width="60%" alt="DC Internet"/>
<img src="https://i.imgur.com/Knd14xX.png" height="60%" width="60%" alt="DC Internet"/>
<img src="https://i.imgur.com/iIDBPuJ.png" height="60%" width="60%" alt="DC Internet"/>
<br />
<br />
<br />
Adding an _ADMINS Organizational Unit to Active Directroy Users and Computers:  <br/>
<img src="https://i.imgur.com/qiK7ZNL.png" height="50%" width="50%" alt="DC Admins"/>
<br />
<br />
<br />
Choosing the right Internet Adapter for our Domain Controller (DC): <br/>
<img src="https://i.imgur.com/nIEHAWB.png" height="60%" width="60%" alt="DC Internet choice"/>
<br />
<br />
<br />
Configuring our DHCP by giving it a IP address range, Mask, and DNS address:  <br/>
<img src="https://i.imgur.com/5jtpuC2.png" height="60%" width="60%" alt="DC DHCP Config"/>
<img src="https://i.imgur.com/hgtaFdC.png" height="60%" width="60%" alt="DC DHCP Config"/>
<br />
<br />
<br />
Using a PowerShell Script to Create 1000 Random Users:  <br/>
<img src="https://i.imgur.com/UaqUqwR.jpeg" height="60%" width="60%" alt="DC PS Script/Use"/>
<img src="https://i.imgur.com/bG9WmyF.jpeg" height="60%" width="60%" alt="DC PS Script/Use"/>
<img src="https://i.imgur.com/FWjGvOE.jpeg" height="60%" width="60%" alt="DC PS Script/Use"/>
<br />
<br />
<br />
On the Client VM using the terminal to check if the IP and DNS addresses are correct as well as pinging www.google.com:  <br/>
<img src="https://i.imgur.com/BJU65sm.png" height="60%" width="60%" alt="Client Terminal"/>
<img src="https://i.imgur.com/nOHUV7h.png" height="60%" width="60%" alt="Client Terminal"/>
<br />
<br />
<br />
Back on the Domain Controller (DC) checking if the client machine is connected to the DC and shows up in the Active Directroies Computers List:  <br/>
<img src="https://i.imgur.com/cq9uQER.png" height="60%" width="60%" alt="DC Checking DHCP and AD"/>
<img src="https://i.imgur.com/VnmPTHX.png" height="60%" width="60%" alt="DC Checking DHCP and AD"/>
<br />
<br />
<br />
</p>

