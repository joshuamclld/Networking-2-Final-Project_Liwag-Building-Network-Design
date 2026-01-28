# Liwag Building Network Design (Cisco Packet Tracer)

## Project Overview
This project implements a hierarchical network design for the Liwag Building using Cisco Packet Tracer.

### Design Model
- Core Router: Cisco 2911
- Distribution/Core Switch
- Access Switches per floor
- VLAN-based segmentation
- Router-on-a-Stick Inter-VLAN Routing
- Centralized DHCP on Router

## VLAN Assignment
| VLAN | Purpose |
|-----|--------|
| 10 | Admin |
| 20 | Faculty / CSS |
| 30 | 2nd Floor Lab |
| 40 | 3rd Floor Lab |
| 50 | 4th Floor Lab |
| 99 | Management |

## Wireless Access Points
- WAPs connected via **access ports**
- Each WAP assigned to its respective VLAN
- Wireless clients receive IP addresses via DHCP

## Proof of Functionality
- DHCP IP assignment verified on PCs and smartphones
- Inter-VLAN communication successful
- Trunk links properly configured

## Files Included
- `.pkt` file
- CLI configurations
- Screenshot proofs of DHCP and VLANs

## Author
Joshua M. Macalalad  
Networking 2 – Final Project
