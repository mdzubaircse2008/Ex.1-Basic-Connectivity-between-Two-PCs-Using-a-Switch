## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 15/10/2026	

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="1912" height="1080" alt="image" src="https://github.com/user-attachments/assets/2bcce453-ffd3-4881-89a0-317ce944fbe5" />


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
## Configuration
<img width="1912" height="1080" alt="image" src="https://github.com/user-attachments/assets/9d40dccf-9ee6-4c8e-9051-2b038a35b2fc" />
<img width="1912" height="1080" alt="image" src="https://github.com/user-attachments/assets/12e7544b-b949-440a-81bb-5e9353ef8f1f" />

## Ping Success
<img width="1912" height="1080" alt="image" src="https://github.com/user-attachments/assets/1fa7e75e-1881-40de-bc84-61eef1055680" />

## Simulation Result
<img width="1912" height="1080" alt="image" src="https://github.com/user-attachments/assets/ff46cc4e-6d66-465c-bb76-1880d0dab641" />

________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
