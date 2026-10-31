# Multi-Area OSPF Dynamic Routing Implementation 

##  Project Overview
This project demonstrates the design and deployment of a Multi-Area OSPF (Open Shortest Path First) routing topology using Cisco Packet Tracer. The objective is to establish seamless and efficient communication across multiple network segments while optimizing routing updates.

##  Key Configurations
*   **Multi-Area Architecture:** Divided the network into distinct OSPF areas (`Area 0` backbone, `Area 1`, and `Area 2`) to minimize routing table size and reduce processing overhead on routers.
*   **Inter-Router Connectivity:** Configured inter-router interfaces to enable dynamic route sharing and end-to-end ICMP communication.
*   **Local Area Networks:** Connected multiple end-user PCs via Cisco 2960-24TT switches across different subnets (e.g., `192.168.2.0/24`, `192.168.3.0/24`, `192.168.4.0/24`).

## 💻 Technologies Used
*   **Simulator:** Cisco Packet Tracer
*   **Protocols:** OSPFv2, IPv4, ICMP
*   **Devices:** Cisco Routers, Cisco 2960 Switches, End-user PCs
