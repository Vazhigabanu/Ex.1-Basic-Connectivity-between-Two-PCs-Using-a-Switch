## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 27/10/26		

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

Insert the network topology from Packet Tracer (Screenshot or drawing)

<img width="1456" height="816" alt="Screenshot 2026-10-27 175232" src="https://github.com/user-attachments/assets/ef085fbd-7bdf-40c8-9c7f-3f47950bc706" />


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

Insert screenshots showing ping success, configuration, or simulation results.

#CONFIGURATION:

<img width="1455" height="818" alt="Screenshot 2026-10-27 175311" src="https://github.com/user-attachments/assets/80222e41-d039-4134-a522-bf6904c15086" />

<img width="1448" height="821" alt="Screenshot 2026-10-27 175321" src="https://github.com/user-attachments/assets/124eb6f9-9e1c-4956-8f63-3be8b1549f49" />

<img width="1447" height="815" alt="Screenshot 2026-10-27 175341" src="https://github.com/user-attachments/assets/50f7c546-3eab-4dc9-affe-8daf41377eb7" />

PING:

<img width="1452" height="820" alt="Screenshot 2026-10-27 175246" src="https://github.com/user-attachments/assets/214455cd-1225-47d7-91c5-b83ad85911a8" />

<img width="1452" height="816" alt="Screenshot 2026-10-27 175258" src="https://github.com/user-attachments/assets/350aeffc-51b5-4d50-9740-c3a56df86717" />


SWITCH CONFIG:

_<img width="1462" height="821" alt="Screenshot 2026-10-27 175332" src="https://github.com/user-attachments/assets/4caf68a7-0990-486e-b61c-dd92545b45a5" />

_______________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
