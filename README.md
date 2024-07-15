<h1>Setting up and OSPF network</h1>

<h2>Description</h2>
This project involves setting up and configuring an Open Shortest Path Frist (OSPF) network using Cisco Packet Tracer. The network consists of four routers, each connected to a PC, with OSPF enabled to allow dynamic routing. The configuration includes assigning IP addresses, enabling OSPF, and verifying connectivity through neighbor relationships and routing tables.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Cisco Packet Tracker</b> 
- <b>Ping and Traceroute Commands</b>

<h2>Program walk-through:</h2>

<p align="center">
To start, I launched Cisco Packet Tracer and created a new network topology, adding four routers and four PCs to the workspace: <br/>
<img src="https://i.imgur.com/EUO2WR3.png" height="80%" width="80%" alt="Launching Cisco Packet Tracer"/>
<br/>
<br/>
Next I added NM-2FE2W modules to each router: <br/>
<img src="https://i.imgur.com/RJd8sne.png" height="80%" width="80%" alt="Adding NM-2FE2W modules"/>
<br />
<br />
Next, I connected each PC to its respective router using the FastEthernet0/0 interface: <br/>
<img src="https://i.imgur.com/OohlLqO.png" height="80%" width="80%" alt="Connecting PCs to routers"/>
<br/>
<br/>
Configured Router 0: Assign IP addresses to FastEthernet0/0 and FastEthernet0/1 interfaces: <br/>
<img src="https://i.imgur.com/qt3Mwav.png" height="80%" width="80%" alt="Configuring Router 0"/>
<br />
<br />
Configured Router 1: Assign IP addresses to FastEthernet0/0, FastEthernet0/1, and FastEthernet1/0 interfaces: <br/>
<img src="https://i.imgur.com/0no5cfE.png" height="80%" width="80%" alt="Configuring Router 1"/>
<br />
<br />
Configured Router 2: Assign IP addresses to FastEthernet0/0, FastEthernet0/1, and FastEthernet1/0 interfaces: <br/>
<img src="https://i.imgur.com/RCvIiUC.png" height="80%" width="80%" alt="Configuring Router 2"/>
<br />
<br />
Configured Router 3: Assign IP addresses to FastEthernet0/0, FastEthernet0/1, and FastEthernet1/0 interfaces: <br/>
<img src="https://i.imgur.com/u99ulvh.png" height="80%" width="80%" alt="Configuring Router 3"/>
<br />
<br />
Enabled OSPF on Router 0: <br/>
<img src="https://i.imgur.com/QVbQHgF.png" height="80%" width="80%" alt="Enabling OSPF on Router 0"/>
<br />
<br />
Enabled OSPF on Router 1: <br/>
<img src="https://i.imgur.com/ZWl8W85.png" height="80%" width="80%" alt="Enabling OSPF on Router 1"/>
<br />
<br />
Enabled OSPF on Router 2: <br/>
<img src="https://i.imgur.com/kpKbva5.png" height="80%" width="80%" alt="Enabling OSPF on Router 2"/>
<br />
<br />
Enabled OSPF on Router 3: <br/>
<img src="https://i.imgur.com/0sI7snf.png" height="80%" width="80%" alt="Enabling OSPF on Router 3"/>
<br />
<br />
Now it was time to test! I verified OSPF neighbors: <br/>
<img src="https://i.imgur.com/NaMAnhM.png" height="80%" width="80%" alt="Verifying OSPF neighbors"/>
<img src="https://i.imgur.com/oyK9n4n.png" height="80%" width="80%" alt="Verifying OSPF neighbors pt 2"/>
<br />
<br />
Verified OSPF routes: <br/>
<img src="https://i.imgur.com/oLu6cXm.png" height="80%" width="80%" alt="Verifying OSPF routes with Traceroute"/>
<br />
<br />
Pinged between PCs to test connectivity: <br/>
<img src="https://i.imgur.com/XbRBmjF.png" height="80%" width="80%" alt="Ping between PCs to test connectivity"/>
<br />
<br />
And lastly, performed traceroute to verify the network path: <br/>
<img src="https://i.imgur.com/Y9qgsv1.png" height="80%" width="80%" alt="Performing traceroute"/>
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
