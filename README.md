
# Manufacturing Company Departmental Network

A Cisco Packet Tracer-based network simulation designed for a manufacturing company. The project demonstrates departmental network segmentation, VLAN configuration, inter-VLAN routing, and essential network services.

## Project Overview

The network is designed to connect four departments through a structured and manageable network infrastructure using an Extended Star Topology.

## Objectives

- Design a departmental network using Cisco Packet Tracer.
- Implement VLAN-based network segmentation.
- Configure inter-VLAN communication using Router-on-a-Stick.
- Provide automatic IP allocation using DHCP.
- Configure DNS and HTTP services.
- Test network connectivity between departments.

## Network Architecture

- **Topology:** Extended Star
- **Router:** Cisco 2911
- **Switches:** Cisco 2960
- **End Devices:** 12 PCs
- **Server:** 1 Server
- **Simulation Tool:** Cisco Packet Tracer

## Departmental VLAN Configuration

| Department | VLAN ID | Network |
|---|---:|---|
| Production | 10 | 192.168.10.0/24 |
| Quality Control | 20 | 192.168.20.0/24 |
| Management | 30 | 192.168.30.0/24 |
| IT | 40 | 192.168.40.0/24 |

## Network Services

- DHCP – Automatic IP address assignment.
- DNS – Domain name resolution.
- HTTP – Web server service.
- Inter-VLAN Routing – Communication between VLANs.

**Configured Domain:** `www.medicore.local`

## Project Files

- [Packet Tracer Project](Packet-Tracer/)
- [Lab Report](Report/)
- [Project Screenshots](Screenshots/)
- [Network Documentation](Documentation/)

## Documentation

- [Network Overview](Documentation/Network-Overview.md)
- [IP Addressing Scheme](Documentation/IP-Addressing-Table.md)
- [VLAN Configuration](Documentation/VLAN-Configuration.md)

## Testing and Verification

Network connectivity was verified through ping tests between network devices and departments. Screenshots of the topology, configurations, and connectivity tests are available in the Screenshots directory.

## Academic Information

**Course:** Data Communication  
**Project:** Manufacturing Company Departmental Network  
**Platform:** Cisco Packet Tracer


## Contributors

1. **Prince Mahmud**
2. **Abdul Momin**
3. **Ahsanul Alam**

## Project Supervisor

**Mahamuda Sultana Omi**  
Lecturer  
Department of Computer Science and Engineering (CSE)  
CCN University of Science & Technology


*Academic project developed as part of the Data Communication course.*
