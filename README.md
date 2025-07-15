# Cybersecurity Lab Environment.

This repository documents the design, installation, and configuration of my personal cybersecurity lab. The environment is built to simulate real-world scenarios for learning, testing, and practicing offensive and defensive security techniques.

---

##  Lab Infrastructure Overview

**Hypervisor:**
- Proxmox VE installed on HP ProLiant DL380e Gen8 server via iLO 4 remote management

**Virtual Machines:**
- **pfSense:** Firewall and network segmentation
- **Suricata:** Intrusion Detection and Prevention System (IDS/IPS)
- **Wazuh:** SIEM and log management
- **ntopng:** Network monitoring and traffic analysis
- **Kali Linux:** Offensive security and testing
- Additional Linux/Windows targets for vulnerability assessment and exploitation

**Networking:**
- Dedicated management VLAN
- Segmented lab networks with VLAN tagging
- Internal DNS and DHCP via pfSense

---

##  Projects and Configurations

###  1. Proxmox Installation and Configuration
- Installed Proxmox VE on dedicated SSD
- Configured networking and storage pools
- Enabled no-subscription repositories
- Set up email alerts and backup schedules

[Proxmox Setup Details](proxmox-setup/README.md)

---

###  2. pfSense Firewall Hardening
- Deployed pfSense VM as the primary firewall
- Configured:
- VLANs
- Firewall rules
- Geo-blocking
- pfBlockerNG
- DNS filtering
- Enabled Suricata inline mode for IDS/IPS

[pfSense Configuration](pfsense-setup/README.md)

---

###  3. Suricata IDS/IPS
- Installed Suricata for real-time intrusion detection
- Tuned rulesets
- Integrated with pfSense
- Enabled alerting and logging

[Suricata Configuration](suricata-setup/README.md)

---

###  4. Wazuh SIEM
- Deployed Wazuh server and agents
- Collected logs from all lab systems
- Configured dashboards and rules
- Tested alerting workflows

[Wazuh Setup](wazuh-setup/README.md)

---

###  5. ntopng Network Monitoring
- Monitored traffic flows and bandwidth
- Visualized protocols and hosts
- Created custom traffic alerts

 [ntopng Monitoring](ntopng-monitoring/README.md)

---

### 6. Security Scripts and Automation
- Bash and Python scripts for:
- Automated backups
- Log parsing
- Vulnerability scanning
- Helper scripts for lab setup and reset

 [Scripts](scripts/README.md)

---

###  7. Capture the Flag (CTF) Writeups
- Documented solutions for:
- HackTheBox
- TryHackMe
- VulnHub
- Included screenshots and methodology

[CTF Writeups](ctf-writeups/README.md)

---

## Key Skills and Tools Demonstrated

- Virtualization and hypervisor administration
- Network segmentation and firewall configuration
- IDS/IPS deployment and tuning
- SIEM configuration and alerting
- Traffic monitoring and analysis
- Offensive security testing
- Scripting and automation

---
# 
## Screenshots

*(You can add images here, e.g. Proxmox dashboard, pfSense interfaces, Wazuh alerts, Suricata logs.)*

---

## Contact

If you want to know more about my lab environment or discuss cybersecurity projects:

- **LinkedIn:** 
- **Email:** 

---
