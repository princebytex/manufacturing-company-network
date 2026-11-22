# IP Addressing Scheme

| Department | VLAN ID | Network Address | Default Gateway |
|---|---:|---|---|
| Production | 10 | 192.168.10.0/24 | 192.168.10.1 |
| Quality Control | 20 | 192.168.20.0/24 | 192.168.20.1 |
| Management | 30 | 192.168.30.0/24 | 192.168.30.1 |
| IT | 40 | 192.168.40.0/24 | 192.168.40.1 |

## Server Configuration

| Parameter | Value |
|---|---|
| IP Address | 192.168.30.100 |
| Subnet Mask | 255.255.255.0 |
| Default Gateway | 192.168.30.1 |
| DNS Server | 192.168.30.100 |
| Domain | www.medicore.local |
