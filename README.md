## Project Highlights

- 4 VLANs implemented at both sites
- Inter-VLAN routing configured
- DHCP configured on routers
- OSPF Area 1 implemented in WAN
- GRE tunnel established between sites
- EIGRP running through GRE tunnel
- IPSec Site-to-Site VPN configured
- NAT configured for Internet access
- EtherChannel configured between switches
- Wireless network deployed in VLAN 40






# Enterprise Multi-Site Network Lab

## Overview

This project simulates a multi-site enterprise network using Cisco Packet Tracer.

The topology consists of:

* Head Office
* Branch Office
* WAN Infrastructure
* Wireless Network
* Server Network
* Internet Connectivity

## Technologies Implemented

### VLANs

Created four VLANs at both Head Office and Branch Office:

* VLAN 10
* VLAN 20
* VLAN 30
* VLAN 40

VLAN 40 is used for wireless devices in BranchOffice.

### Inter-VLAN Routing

Configured inter-VLAN routing to allow communication between devices located in different VLANs.

### DHCP

Configured DHCP on routers to automatically assign IP addresses for devices in each VLAN.

### EtherChannel

Configured EtherChannel between switches to provide redundancy and increased bandwidth.

### OSPF

Configured OSPF Area 1 across WAN routers to enable dynamic routing throughout the WAN infrastructure.

### GRE Tunnel

Configured GRE tunnel between Head Office and Branch Office to provide logical connectivity between sites.

### EIGRP

Configured EIGRP across the GRE tunnel to enable routing between Head Office and Branch Office networks.

### Site-to-Site VPN

Configured site-to-site VPN through the GRE tunnel to provide secure communication between both locations.

### NAT

Configured NAT on edge routers to allow internal VLAN users to access external networks and Internet resources.

### Wireless Networking

Configured wireless devices within VLAN 40 at the Branch Office.

## Skills Demonstrated

* VLAN Configuration
* Inter-VLAN Routing
* DHCP Services
* OSPF Routing
* EIGRP Routing
* GRE Tunneling
* Site-to-Site VPN
* NAT Configuration
* EtherChannel
* Wireless Networking
* Enterprise Network Design
* Routing and Switching Troubleshooting




Verification
Network Topology




VLAN Configuration

Verified VLAN creation and assignments.




EtherChannel Verification

Verified EtherChannel status and bundled interfaces.




OSPF Verification

Verified OSPF neighbor adjacency across the WAN.




Routing Verification

Verified routing table entries and route propagation.




NAT Verification

Verified NAT translations for internal devices accessing external networks.




IPSec VPN Verification

Verified IPSec security associations between Head Office and Branch Office.




Connectivity Testing

Successful end-to-end communication between sites.

Ping Test

