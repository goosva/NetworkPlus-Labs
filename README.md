
# NetworkPlus-Labs

This project is a self-guided lab series aligned with the **CompTIA Network+ (N10-009)** exam, designed to build practical skills in networking and cybersecurity using a virtual lab environment powered by **Proxmox VE**.

---

## Domains Covered

- [x] Networking Fundamentals
- [x] Network Implementations
- [x] Network Operations
- [x] Network Security
- [x] Network Troubleshooting

---

## Lab List

| Domain | Area | Lab | Description |
|--------|------|-----|-------------|
| 1 | Networking Fundamentals | [OSI Model Wireshark](./domain-1-networking-fundamentals/01-osi-model-wireshark) | Capturing and labeling traffic by OSI layer |
| 1 | Networking Fundamentals | [IP Addressing and Subnetting](./domain-1-networking-fundamentals/02-ip-subnetting) | Assign static IPs and perform subnetting exercises |
| 1 | Networking Fundamentals | [Ports and Protocols Analysis](./domain-1-networking-fundamentals/03-ports-and-protocols) | Use nmap and Wireshark to explore TCP/UDP traffic |
| 1 | Networking Fundamentals | [DNS, DHCP, and NAT Configuration](./domain-1-networking-fundamentals/04-dns-dhcp-nat) | Configure services in pfSense and test them |
| 2 | Network Implementations | [VLAN Creation and Routing](./domain-2-network-implementations/01-vlans-and-trunking) | Create isolated networks and allow inter-VLAN routing |
| 2 | Network Implementations | [WAN Technologies Overview](./domain-2-network-implementations/02-wan-technologies) | Document broadband types and simulate multi-WAN |
| 2 | Network Implementations | [Remote Access VPN (WireGuard)](./domain-2-network-implementations/03-vpn-setup-wireguard) | Secure remote access to lab from external networks |
| 3 | Network Operations | [Network Monitoring Tools](./domain-3-network-operations/01-monitoring-tools) | Deploy Netdata/Nagios and monitor performance |
| 3 | Network Operations | [Syslog and SNMP](./domain-3-network-operations/02-syslog-and-snmp) | Forward logs and configure SNMP polling |
| 3 | Network Operations | [Configuration Backups and Management](./domain-3-network-operations/03-config-backups) | Backup pfSense and use Proxmox snapshots |
| 4 | Network Security | [IDS/IPS with Suricata](./domain-4-network-security/01-ids-suricata) | Deploy Suricata and generate test alerts |
| 4 | Network Security | [Harden VPN Access with 2FA](./domain-4-network-security/02-vpn-hardening-2fa) | Secure WireGuard with 2FA using pfSense TOTP |
| 4 | Network Security | [Kali Attacks: ARP Spoofing + MITM](./domain-4-network-security/03-kali-mitm-attacks) | Perform and analyze MITM attacks |
| 5 | Network Troubleshooting | [Network Tools and Commands](./domain-5-network-troubleshooting/01-tools-and-commands) | Practice `ping`, `traceroute`, and other CLI tools |
| 5 | Network Troubleshooting | [Simulate and Troubleshoot Failures](./domain-5-network-troubleshooting/02-simulated-failures) | Break and fix DHCP, DNS, or routes |

---

## Tools Used

### Core Infrastructure
- [Proxmox VE](https://www.proxmox.com/proxmox-ve)
- [pfSense](https://www.netgate.com/)
- Ubuntu Server/Desktop
- [Kali Linux](https://www.kali.org/)

### Traffic Analysis
- [Wireshark](https://www.wireshark.org/)
- [nmap](https://nmap.org/)

### Remote Access & VPN
- [WireGuard](https://www.wireguard.com/)
- *(Optional)* [OpenVPN](https://openvpn.net/)

### Monitoring & Detection
- [Suricata](https://suricata.io/)
- [Security Onion](https://securityonion.net/) (includes Zeek, Kibana, Wazuh)
- [Netdata](https://www.netdata.cloud/)
- SNMP Tools: `snmpwalk`, `snmpget`

### Utility & Documentation
- [draw.io](https://drawio.app/) (network diagrams)
- bash / [Ansible](https://www.ansible.com/) (automation & backups)

### Advanced (Optional)
- [Splunk](https://www.splunk.com/) or ELK Stack
- [Bettercap](https://www.bettercap.org/), [Ettercap](https://www.ettercap-project.org/)

---

## Getting Started

1. Install **Proxmox VE** on a dedicated system or nested VM.
2. Create:
   - `vmbr0`: NAT-connected bridge for internet access
   - `vmbr1`: Isolated lab network
3. Upload ISO images for Ubuntu, pfSense, Kali, etc.
4. Use the lab folders above to follow along.

Feel free to fork this repo and expand the labs, add automation, or track your progress in the README files!
