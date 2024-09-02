AIM:
 The objective of this exercise is to design and configure a network topology that includes both LAN (Local Area Network) and WAN (Wide Area Network) using Cisco 
 Packet Tracer. The topology will include 10-15 computers, switches, and routers. The exercise involves setting up and configuring the LANs, connecting them via a 
 WAN, and simulating the transmission of data between different networks.
PROCEDURE:
TOPOLOGY DESIGN:
 LAN Configuration:
 Switch 1: Connects 5 PCs (PC1-PC5) using straight-through cables.
 Switch 2: Connects the remaining 5 PCs (PC6-PC10) using straight-through cables.
 Inter-Switch Connection: Connect the two switches using a straight-through cable between one of the GigabitEthernet or FastEthernet ports.
 WAN Configuration:
 Router 1 (R1): Connects to Switch 1.
 Router 2 (R2): Connects to Switch 2.
 Inter-Router Connection: Connect R1 and R2 using a cross-over cable between their GigabitEthernet0/0 interfaces.\
NETWORK SETUP IN CISCO PACKET TRACER:
 Add Devices:
 Place 10 computers and label them PC1 to PC10.
 Add two switches (Switch 1 and Switch 2).
 Add two routers (Router 1 and Router 2).
CONNECT DEVICES:
 LAN Configuration:
 Switch 1: Connect PC1 to PC5 using straight-through cables to FastEthernet ports.
 Switch 2: Connect PC6 to PC10 using straight-through cables to FastEthernet ports.
 Inter-Switch Connection: Connect Switch 1 to Switch 2 using a straight-through cable between FastEthernet0/24 ports.
IP ADDRESS CONFIGURATION:
 Assign IP Addresses:
 For LAN 1 (Switch 1 - PCs 1-5):
 Use the 192.168.1.0/24 subnet.
 Assign 192.168.1.1 to Router 1’s GigabitEthernet0/0 as the default gateway.
 For LAN 2 (Switch 2 - PCs 6-10):
 Use the 192.168.2.0/24 subnet.
 Assign 192.168.2.1 to Router 2’s GigabitEthernet0/0 as the default gateway.
CONFIGURATION SETUP:
 LAN Configuration:
 Connect computers to the switches.
 Configure IP addresses on each computer.
 Connect switches with each other as needed.
 WAN Configuration:
 Connect routers to each other.
 Configure router interfaces with IP addresses.
 Set up routing (static or dynamic) to ensure connectivity between the LANs.
SIMULATION:
 Simulate Message Transmission:
 Use simulation mode to send a message from a computer in LAN 1 (PC1) to a computer in LAN 2 (PC6).
 Verify that the message successfully traverses through the routers and reaches the destination.

SCREENSHOT:
![Screenshot 2024-09-02 212656](https://github.com/user-attachments/assets/668db447-063d-48de-8ba8-10938d6930f4)

![Screenshot 2024-09-02 213835](https://github.com/user-attachments/assets/efd815f7-d577-4e1f-bdc5-ae603989652b)
