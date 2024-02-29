<h1>OSPF Single Area</h1>

<h2>Description</h2>
This lab will configure the OSPF routing protocol(Single Area). All IP addresses have beeen configured on the router interfaces.
<br />

<h2>Environments Used </h2>

- <b>Packet Tracer</b>

<h2>Lab walk-through:</h2>

<p align="center">
<h4>Lab Topology:</h4>
In this Lab topology there are 6 routers. OSPF will be configred between the routers and connection will be established between the subnets. <br/>
<img src="https://i.imgur.com/WrWJsR9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h4>Before OSPF:</h4> 
R1 only has it's connected routes and local routes in it's routing table.  <br/>
<img src="https://i.imgur.com/8u8hyc0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
PC2 cannot ping the end devices in the other subnets. <br/>
<img src="https://i.imgur.com/cU7FixL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />

<h4>After OSPF:</h4> 
R1 all the routes to the subnets in the private network. <br/>
<img src="https://i.imgur.com/bBUSSPN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
PC2 cannot ping the end devices in the other subnets. <br/>
<img src="https://i.imgur.com/f7fbpUn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

