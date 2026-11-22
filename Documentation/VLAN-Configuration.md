# VLAN Configuration

The network is divided into four VLANs to separate the departments and organize network traffic.

| VLAN ID | VLAN Name | Department |
|---|---|---|
| 10 | PRODUCTION | Production |
| 20 | QUALITY_CONTROL | Quality Control |
| 30 | MANAGEMENT | Management |
| 40 | IT | IT |

## Inter-VLAN Routing

Router-on-a-Stick configuration is used to enable communication between different VLANs through the Cisco 2911 router.

## Trunk Configuration

Trunk links connect the core switch with departmental switches and carry traffic from the required VLANs.

## Purpose

- Departmental network segmentation.
- Improved network organization.
- Controlled inter-department communication.
- Efficient network management.
