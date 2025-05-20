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
|--------|-----|-------------|
| 1 | [OSI Model Wireshark](./domain-1-networking-fundamentals/01-osi-model-wireshark) | Capturing and labeling traffic by OSI layer |
| 1 | [IP Addressing and Subnetting](./domain-1-networking-fundamentals/02-ip-subnetting) | Assign static IPs and perform subnetting exercises |
| 1 | [Ports and Protocols Analysis](./domain-1-networking-fundamentals/03-ports-and-protocols) | Use nmap and Wireshark to explore TCP/UDP traffic |
| 1 | [DNS, DHCP, and NAT Configuration](./domain-1-networking-fundamentals/04-dns-dhcp-nat) | Configure services in pfSense and test them |
| 2 | [VLAN Creation and Routing](./domain-2-network-implementations/01-vlans-and-trunking) | Create isolated networks and allow inter-VLAN routing |
| 2 | [WAN Technologies Overview](./domain-2-network-implementations/02-wan-technologies) | Document broadband types and simulate multi-WAN |
| 2 | [Remote Access VPN (WireGuard)](./domain-2-network-implementations/03-vpn-setup-wireguard) | Secure remote access to lab from external networks |
| 3 | [Network Monitoring Tools](./domain-3-network-operations/01-monitoring-tools) | Deploy Netdata/Nagios and monitor performance |
| 3 | [Syslog and SNMP](./domain-3-network-operations/02-syslog-and-snmp) | Forward logs and configure SNMP polling |
| 3 | [Configuration Backups and Management](./domain-3-network-operations/03-config-backups) | Backup pfSense and use Proxmox snapshots |
| 4 | [IDS/IPS with Suricata](./domain-4-network-security/01-ids-suricata) | Deploy Suricata and generate test alerts |
| 4 | [Harden VPN Access with 2FA](./domain-4-network-security/02-vpn-hardening-2fa) | Secure WireGuard with 2FA using pfSense TOTP |
| 4 | [Kali Attacks: ARP Spoofing + MITM](./domain-4-network-security/03-kali-mitm-attacks) | Perform and analyze MITM attacks |
| 5 | [Network Tools and Commands](./domain-5-network-troubleshooting/01-tools-and-commands) | Practice `ping`, `traceroute`, and other CLI tools |
| 5 | [Simulate and Troubleshoot Failures](./domain-5-network-troubleshooting/02-simulated-failures) | Break and fix DHCP, DNS, or routes |

## Tools Used

**Core Infrastructure**
- Proxmox VE
- pfSense
- Ubuntu Server/Desktop
- Kali Linux

**Traffic Analysis**
- Wireshark
- nmap

**Remote Access & VPN**
- WireGuard
- (Optional) OpenVPN

**Monitoring & Detection**
- Suricata
- Security Onion (Zeek, Kibana, Wazuh)
- Netdata
- SNMP Tools (`snmpwalk`, `snmpget`)

**Utility & Documentation**
- draw.io (network diagrams)
- bash/Ansible (automation and backups)

**Advanced (Optional)**
- Splunk or ELK Stack
- Bettercap or Ettercap

