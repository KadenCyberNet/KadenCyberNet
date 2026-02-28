<h1>Hi, I'm Kaden! 👋</h1>

<p>
Networking & Cybersecurity student building real-world skills through hands-on home lab projects using physical Cisco hardware, Packet Tracer, Wireshark, and virtual machines. Holding a CompTIA Security+ certification with a strong focus on network defense and Layer 2 security, currently preparing for the CCNA exam in May.
</p>

---

<h2>👨‍💻 Networking Projects (CCNA Home Lab):</h2>

| Project | Summary |
|--------|---------|
| 🔌 [VLAN Segmentation Lab](https://github.com/KadenCyberNet) | Configured VLANs on a physical Cisco switch to isolate departments (IT, Sales, HR). Practiced access port assignment, VLAN verification, and traffic isolation. |
| 🏠 [Home Lab Setup – Physical Cisco Hardware](https://github.com/KadenCyberNet) | Built a home lab using a real Cisco switch and router. Configured console access via PuTTY, set hostnames, enable secrets, management IPs, and saved configs. |
| 🌐 [Inter-VLAN Routing – Router on a Stick](https://github.com/KadenCyberNet) | Configured a Cisco router with subinterfaces to allow communication between VLANs. Practiced trunk port setup between switch and router. |
| 🌳 [Spanning Tree Protocol Analysis](https://github.com/KadenCyberNet) | Observed STP behavior on a live switch, manipulated root bridge election, and configured PortFast and BPDU Guard on access ports. |

---

<h2>🔐 Cybersecurity Projects:</h2>

> These projects focus on real attack vectors that target Layer 2 networks — the same threats that exist in enterprise environments. Each project was built and tested on physical Cisco hardware.

<br />

**🛡️ Port Security & MAC Address Attack Prevention**

Most attackers start at Layer 2. This project demonstrates how to lock down switch ports so only authorized devices can connect. Configured violation modes (shutdown, restrict, protect), tested MAC flooding behavior, and analyzed the MAC address table to detect unauthorized devices. This is a fundamental defense skill in any enterprise network.

`Skills: Port Security, MAC Flooding, Violation Policies, show mac address-table`

---

**🕵️ Network Device Discovery & Mapping**

Using only built-in tools — no third-party software — mapped out an entire network by analyzing ARP tables, MAC address tables, and ICMP responses. Identified every device by MAC address and matched them to physical switch ports. This mirrors what a security analyst does during a network audit or incident investigation.

`Skills: ARP Analysis, MAC Table Forensics, ipconfig, arp -a, Cisco IOS show commands`

---

**🚫 DHCP Snooping & Dynamic ARP Inspection**

Configured DHCP Snooping to prevent rogue DHCP servers from hijacking IP assignments on the network. Combined with Dynamic ARP Inspection (DAI) to block ARP poisoning attacks. These are two of the most important Layer 2 security controls in modern networks and appear on both the CCNA exam and real enterprise deployments.

`Skills: DHCP Snooping, DAI, ARP Poisoning Prevention, Trusted/Untrusted Ports`

---

**🔒 SSH Hardening & Secure Remote Management**

Removed all Telnet access and replaced it with encrypted SSH management on a physical Cisco switch. Generated RSA keys, set up VTY line restrictions, and tested secure remote login. Telnet sends credentials in plaintext — this project demonstrates why SSH is non-negotiable in a secure environment.

`Skills: SSH Configuration, RSA Key Generation, VTY Line Security, Telnet Removal`

---

**🔥 Windows Firewall Analysis & ICMP Traffic Control**

Investigated one-way ping failures between two PCs on the same network. Diagnosed the issue as asymmetric firewall rules blocking inbound ICMP on one host. Used netsh to configure firewall rules and verified connectivity. This mirrors real-world troubleshooting where firewalls silently block traffic and appear as network faults.

`Skills: Windows Firewall, netsh, ICMP, Inbound Rules, Network Troubleshooting`

---

<h2>🌱 Currently Working On:</h2>

- Studying for **CCNA Certification**
- Expanding home lab with additional Cisco routers
- Building EtherChannel and advanced STP labs
- Practicing **network security hardening** and Layer 2 attack mitigation

---

<h2>🤳 Connect with me:</h2>

[<img align="left" alt="Kaden Baffour | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]

<br />

[linkedin]: https://linkedin.com/in/kaden-baffour

<!--
**KadenCyberNet/KadenCyberNet** is a ✨ _special_ ✨ repository because its `README.md` appears on your GitHub profile.
-->
