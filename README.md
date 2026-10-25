# Enterprise HQ & Branch Network

## Project Overview
This project demonstrates the design, configuration, and testing of an enterprise network connecting a headquarters (HQ) and a branch office using Cisco Packet Tracer.

The network supports multiple departments through VLAN segmentation, inter-VLAN routing, DHCP, and static routing between sites.

## Network Topology
The topology consists of:
- 2 Cisco 2911 Routers
- 4 Cisco 2960 Switches
- 8 PCs
- 1 Server
- A point-to-point connection between HQ and the branch

## Headquarters (HQ)
- VLAN 10: IT — 192.168.10.0/24
- VLAN 20: HR — 192.168.20.0/24
- VLAN 30: Finance — 192.168.30.0/24
- VLAN 40: Servers — 192.168.40.0/24

## Branch Office
- VLAN 50: Sales — 192.168.50.0/24
- VLAN 60: Support — 192.168.60.0/24

## Technologies and Configurations
- VLAN configuration and network segmentation
- 802.1Q trunk links
- Router-on-a-Stick inter-VLAN routing
- DHCP for automatic IP address assignment
- Static routing between HQ and the branch
- IP addressing and subnetting
- Basic network connectivity troubleshooting

## Connectivity Testing
The following tests were successfully performed:
- Branch-to-HQ router connectivity
- Branch Sales PC to HQ IT PC connectivity
- Communication between Sales and Support VLANs

## Project File
Download the Enterprise_HQ_Branch_Network.pkt file and open it using Cisco Packet Tracer to explore the network topology and device configurations.

## Skills Demonstrated
Cisco Networking | VLANs | DHCP | Static Routing | Inter-VLAN Routing | Network Troubleshooting | Cisco Packet Tracer

## Author
Raghad Al Muhaya
