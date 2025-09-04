# DHCP & DNS Server Configuration

This project demonstrates DHCP and DNS configuration in a small office LAN using Cisco Packet Tracer with a Windows Server.

## Topology
- **LAN Network**: 192.168.1.0/24
- **Router Gateway**: 192.168.1.1
- **Windows Server**: 192.168.1.10 (DHCP + DNS)
- **DHCP Scope**: 192.168.1.100 – 192.168.1.200
- **DNS Domain**: mycompany.local

### Features Implemented
- DHCP Server assigns IPs dynamically to clients
- DNS Server resolves hostnames within domain
- Router provides gateway to internet
- PCs automatically receive IP + DNS from DHCP

## How to Test
1. Set PCs to **DHCP mode**
2. Check assigned IPs using `ipconfig /all`
3. Ping server.mycompany.local or pc1.mycompany.local
