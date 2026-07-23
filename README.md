## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 23/07/2026		

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="1920" height="1080" alt="Screenshot 2026-07-23 133657" src="https://github.com/user-attachments/assets/6183b423-95c4-41a3-ad8a-8650ce811720" />

________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results)

<img width="1918" height="1078" alt="Screenshot 2026-07-23 134032" src="https://github.com/user-attachments/assets/e95f8afe-a099-40dc-bfbf-0932a53980a2" />
<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/3b05aab7-5d99-4c86-ab1c-bc017707b8b2" />
_<img width="1920" height="1080" alt="Screenshot 2026-07-23 134258" src="https://github.com/user-attachments/assets/ab017bb3-c6ac-4171-863e-85ae368450fd" />
___________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
