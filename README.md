# Enterprise Network Design Using VLANs and Router-on-a-Stick

## Project Overview
Designed and configured an enterprise network in Cisco Packet Tracer for three departments: HR, IT, and Finance.

## Objectives
- Segment departments using VLANs.
- Configure access ports and IEEE 802.1Q trunking.
- Implement inter-VLAN routing using Router-on-a-Stick.
- Configure IPv4 addressing and default gateways.
- Verify connectivity and troubleshoot network issues.

## Network Design
- **VLAN 10:** HR
- **VLAN 20:** IT
- **VLAN 30:** Finance
- **Devices:** Cisco 2911 router, Cisco 2960 switch, and six PCs.

## Technologies
Cisco Packet Tracer, Cisco IOS CLI, VLANs, IPv4, trunking, and inter-VLAN routing.

## Verification
Commands used:
- `show vlan brief`
- `show interfaces trunk`
- `show ip interface brief`
- `show ip route`

Connectivity tested using ICMP ping between devices in different VLANs.

## Files
- `Enterprise_VLAN_InterVLAN_Routing.pkt` — Packet Tracer lab file.
- `Network_Topology.png` — Network topology screenshot.
- `screenshots/` — Configuration and connectivity evidence.

## Learning Outcome
Practised VLAN segmentation, trunk configuration, router subinterfaces, IPv4 addressing, and basic network troubleshooting.

*This is a personal hands-on lab project created for learning and demonstrating networking skills.*
