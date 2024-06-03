# DCN_LAB_PROJECT-ALISHER_AND_ALI_AHMAD
 
Introduction to Cisco Packet Tracer:
Packet Tracer is a cross-platform visual simulation tool designed by Cisco Systems that allows users to create network topologies and imitate modern computer networks. The software allows users to simulate the configuration of Cisco routers and switches using a simulated command line interface. Packet Tracer makes use of a drag and drop user interface, allowing users to add and remove simulated network devices as they see fit. The software is mainly focused towards Cisco Networking Academy students as an educational tool for helping them learn fundamental CCNA concepts. Previously students enrolled in a CCNA Academy program could freely download and use the tool free of charge for educational use.

Devices:-
1.Router
2.switch
3.server
4.wires
5.Pc 
CONCEPT’S USED:-
1)OSPF ROUTING:
OSPF (Open Shortest Path First) is a link-state routing protocol used in Internet Protocol (IP) networks. It is designed to be efficient, scalable, and flexible. OSPF routers exchange topology information with their neighbors, allowing each router to have a complete map of the network, which it uses to determine the best path to each destination.
2) RIP:
Routing Information Protocol (RIP) is one of the oldest distance-vector routing protocols used in IP networks. It is designed to be simple and easy to configure, making it suitable for small to medium-sized networks. RIP uses hop count as its metric for path selection, with a maximum allowable hop count of 15, which limits the size of the network that RIP can support.
2)VLANs:
VLANs (Virtual Local Area Networks) are a technology used to create logically segmented networks within a physical network. This segmentation enhances security, reduces broadcast traffic, and allows for better management of network resources.
3)LAN:
A Local Area Network (LAN) is a network that connects computers and other devices within a limited geographical area, such as a home, school, office building, or closely positioned group of buildings. LANs are characterized by high data transfer rates, relatively low latency, and typically use Ethernet or Wi-Fi technologies.
4) VTP:

VLAN Trunking Protocol (VTP) is a Cisco-proprietary protocol that manages the addition, deletion, and renaming of VLANs on a network-wide basis to maintain VLAN configuration consistency across a switched network. VTP simplifies network management by allowing a network administrator to configure VLANs on one switch (the VTP server), which then propagates the changes to all other switches in the VTP domain.
7)MULTI POINT CONNECTION:
Multipoint connections, also known as multipoint communication or multipoint connectivity, refer to network setups where multiple devices or nodes are interconnected, allowing them to communicate with each other simultaneously. This contrasts with point-to-point connections, where communication occurs between only two devices.
8) DHCP:
DHCP is a network management protocol used on IP networks to automatically assign IP addresses and other communication parameters to devices on the network. This automation reduces the need for manual configuration of IP addresses, which can be error-prone and time-consuming.
9)  TFTP:
TFTP is a simple, lightweight file transfer protocol that provides a method for transferring files over a network. It is often used for transferring configuration files, firmware updates, and boot images to network devices.
10) Inter-VLANs:
Inter-VLAN routing is a process used to allow communication between different VLANs (Virtual Local Area Networks) within a network. Since VLANs segment a network into separate broadcast domains, devices in different VLANs cannot communicate with each other by default. Inter-VLAN routing overcomes this limitation by enabling traffic to be routed between VLANs, typically using a Layer 3 device such as a router or a Layer 3 switch.

Entire Network:
 
The Network is comprised of many parts. I’ll discuss each part individually.
OSPF and RIP:

For OSPF Configuration on router 26:
Show ip ospf:
This command displays general information about the OSPF (Open Shortest Path First) routing protocol on the router. It provides details such as:
OSPF process ID
Router ID
Number of areas in which the router is participating
Number of OSPF neighbors
OSPF area types and their respective statistics




Show ip ospf interface:
This command provides detailed information about the OSPF configuration on each interface of the router. It includes:
Interface name
IP address of the interface
OSPF area to which the interface belongs
Cost of the interface
State of the interface 
Hello and dead interval timers
Authentication type (if configured)

Show ip route ospf:
This command displays the routes in the router's IP routing table that were learned via OSPF. It shows:
Network destinations
Subnet masks
Administrative distance and metric of the OSPF routes
Next-hop addresses
Interfaces through which the routes are reachable



For RIP Configuration on router 23:




VLANs:





Show vlan brief:
The command will typically list all configured VLANs along with their VLAN IDs and some basic information about each VLAN, such as its name and interface membership.

show vtp status:
VTP Version: Indicates the version of VTP being used (either version 1 or version 2).
Configuration Revision: The revision number of the VTP configuration. This number is incremented every time a change is made to the VTP domain.
Maximum VLANs supported locally: The maximum number of VLANs the switch can support.
Number of existing VLANs: The current number of VLANs in the VTP domain.
VTP Operating Mode: Indicates whether the switch is operating as a VTP server, client, or transparent. Servers propagate VLAN information, clients synchronize their VLAN configuration with servers, and transparent switches don't participate in VTP.
VTP Domain Name: The name of the VTP domain to which the switch belongs. All switches within the same VTP domain share VLAN information.
VTP Pruning Mode: Whether VTP pruning is enabled or disabled. VTP pruning prevents unnecessary flooding of traffic in VLANs where there are no active ports.
VTP Traps Generation: Indicates whether VTP traps (notifications) are generated and sent to management stations.
MD5 digest: A cryptographic hash of the VTP configuration. It helps ensure the integrity of the VTP messages exchanged between switches.

DHCP configuration:


Server:

PC 13 (DHCP Request Successful):



LinkedIn Link:
https://www.linkedin.com/feed/update/urn:li:activity:7203341257559957504/
