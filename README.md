# Modern Hotel Network Design

## Overview
This project presents a network design for a modern hotel with three floors, each containing multiple departments. The network is structured to ensure efficient communication, security, and scalability.

## Network Design
- **Three Floors:**
  - **First Floor:** Reception, Store, Logistics
  - **Second Floor:** Finance, HR, Sales
  - **Third Floor:** IT, Admin
- **Three routers** are used to connect each floor.
- **One switch per floor** for wired connections.
- **WiFi networks on each floor** to connect laptops and mobile devices.
- **Each department operates in a separate VLAN** to segment network traffic.

## Key Features
- **OSPF (Open Shortest Path First) Routing Protocol** is implemented to advertise routes between routers efficiently.
- **DHCP Server on each router** to assign IP addresses dynamically to devices within their respective VLANs.
- **Inter-VLAN Communication** is configured to allow all departments to communicate securely.
- **SSH (Secure Shell) is enabled on all routers** for secure remote login and management.

## Technologies Used
- Cisco Packet Tracer for network simulation
- VLANs for network segmentation
- DHCP for dynamic IP allocation
- OSPF for routing
- SSH for secure remote access

## Setup Instructions
1. Open the network design file in Cisco Packet Tracer.
2. Ensure all routers have their DHCP services enabled and correctly configured.
3. Verify VLAN configurations on switches for each department.
4. Test inter-floor and inter-department communication using ping and traceroute.
5. Connect to routers via SSH to ensure secure remote access.

