# NetworkPlus-Labs
This repository contains hands-on projects aligned with the CompTIA Network+ (N10-009) exam objectives. All labs are built and tested within a Proxmox virtual environment.

## Domains Covered
- [x] Networking Fundamentals
- [x] Network Implementations
- [x] Network Operations
- [x] Network Security
- [x] Network Troubleshooting

## Lab List
| Domain | Lab | Description |
|-----|-----|-------------|
| 1 | [OSI Model Wireshark](./osi-model-wireshark) | Capturing and labeling traffic by OSI layer |
| 1 | [IP Addressing and Subnetting](./osi-model-wireshark) | Assign static IPs and perform subnetting exercises |
| 1 | [Ports and Protocols Analysis](./osi-model-wireshark) | Use nmap and Wireshark to explore TCP/UDP traffic |
| 1 | [DNS, DHCP, and NAT Configuration](./osi-model-wireshark) | Configure services in pfSense and test them |



| [pfSense VPN Setup](./pfSense-vpn-wireguard) | Remote access to lab over WireGuard |
| [DNS, DHCP, NAT](./dns-dhcp-nat) | Simulate core LAN services with pfSense/Ubuntu |
| [VLAN Routing + Firewalls](./vlan-routing-firewall) | Segmentation and ACLs via pfSense |
| [Network Monitoring](./network-monitoring-ids) | IDS with Suricata and Security Onion |

## Tools Used
- Proxmox VE
- pfSense
- Ubuntu Server/Desktop
- Wireshark
- WireGuard
- Kali Linux
