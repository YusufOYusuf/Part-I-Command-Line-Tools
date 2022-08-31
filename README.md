<h1>Capturing a Packet Using Wireshark</h1>



<h2>Description</h2>
In this lab, I learned to use the ping, ipconfig, and tracert commands. The ping command is one of the most commonly used command line commands that is used to check IP (Internet Protocol) connectivity between two network devices. The ping command uses ICMP (Internet Control Message Protocol), which is a Layer 4 protocol. The ipconfig command is used to display IP address configuration parameters on a PC. The tracert command displays every router hop along the path from a source host to a destination host on an IP network.


<br />



<h2>Environments Used </h2>

- <b>Windows Server 2016 Standard</b> 


<h2>Languages and Utilities</h2>

- <b>Windows Powershell<b>

<h2>Program walk-through:</h2>

<p align="center">
From the desktop go to the start and from there open up windows powershell: <br/>
<img src="https://i.postimg.cc/1tD4z97x/Screen-Shot-2022-08-31-at-10-52-36-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
<br>
Type in "ping" and any website you wish (I chose to ping www.google.com):<br>
<img src="https://i.postimg.cc/ydppkHDP/Screen-Shot-2022-08-31-at-10-54-47-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
Now I will try to "ping" a private address to show that it will not ping:</br>
<img src="https://i.postimg.cc/NMGTZ2fJ/Screen-Shot-2022-08-31-at-10-57-49-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
Now lets try the "ipconfig" command:  <br/>
<img src="https://i.postimg.cc/L6mhHgd2/Screen-Shot-2022-08-31-at-10-59-45-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />


<br />
Now I will try the "ipconfig /all" command to view all information about a network adapter:  <br/>
<img src="https://i.postimg.cc/cCppLnCZ/Screen-Shot-2022-08-31-at-11-02-51-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />



<br />
Now lets try the "Tracert" command followed by any website you choose :  <br/>
<img src="https://i.postimg.cc/vmwSxyG7/Screen-Shot-2022-08-31-at-11-06-43-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />





















</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
