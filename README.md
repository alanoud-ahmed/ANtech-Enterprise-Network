# AN Tech – Enterprise Network Design

Design, implementation, testing, and evaluation of a secure, scalable, and highly available enterprise network connecting a headquarters in Manama with branches in Dubai and Kuwait. Built in Cisco Packet Tracer.

## Overview
- **Sites:** Manama (HQ), Dubai, Kuwait
- **Routing:** OSPF (single area)
- **Switching:** VLAN segmentation, Rapid-PVST+/PVST+, LACP EtherChannel
- **Redundancy:** HSRP, triangular WAN with automatic failover
- **WAN:** PPP with CHAP authentication
- **Internet edge:** NAT/PAT, static port forwarding, DMZ
- **Security:** ACLs, SSH v2, port security, WPA2, guest isolation
- **Services:** DHCP, DNS, Web, Email

## Repository contents
| File | Description |
|------|-------------|
| `AN_Tech_network_design.pdf` | Full 43-page design and evaluation report |
| `AN_Tech_network.pkt` | Cisco Packet Tracer project file |

## Topology
![Topology](topology.png)

## How to open the project
1. Install Cisco Packet Tracer.
2. Open `AN_Tech_network.pkt`.

## Author
Alanoud Ahmed
