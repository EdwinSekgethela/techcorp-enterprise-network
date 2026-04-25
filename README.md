# TechCorp Enterprise Network — Cisco Packet Tracer

## Project Overview
A fully functional two-site enterprise network built from scratch in Cisco 
Packet Tracer as part of CCNA exam preparation. Built and troubleshot across 
4 sessions covering all core CCNA routing and switching topics.

## Technologies Implemented
- VLANs (10/20/30/40) and 802.1Q trunking across 6 switches
- Router-on-a-stick inter-VLAN routing (R1 subinterfaces)
- DHCP server configuration across 4 subnets
- Extended ACLs for department security policy enforcement
- NAT/PAT for internet access via simulated ISP
- OSPF dynamic routing between HQ and branch office
- Port security with sticky MAC on all access switches
- SSH remote management on all routers and switches
- WPA2 wireless access points at HQ and branch
- ASA 5506-X firewall at HQ network edge

## Network Topology
- HQ: R1 (2911) + SW1 (3650) + SW2/3/4 (2960) + HQ-FW (ASA 5506-X)
- Branch: R2 (2911) + SW5/6 (2960)
- WAN: OSPF over point-to-point link (10.0.0.0/30)
- Internet: Simulated ISP with NAT/PAT on R1

## Documentation
All configs, troubleshooting reports and cheat sheets are in /docs

## Author
Edwin Sekgethela | CCNA Candidate | 
linkedin.com/in/[EdwinSekgethela]
