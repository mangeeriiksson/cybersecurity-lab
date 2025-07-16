# * Cybersecurity Lab & CTF Portfolio

Welcome to my cybersecurity portfolio repository. This project documents the design, configuration, and continuous development of my personal cybersecurity lab environment, as well as writeups and tooling from Capture the Flag (CTF) challenges.  

The lab and projects are built to simulate real-world scenarios for practicing offensive and defensive security skills.

---

## * Objectives and Purpose

The primary goals of this environment and portfolio are:

* Gain hands-on experience configuring and securing enterprise-grade infrastructure  
* Deploy, harden, and integrate industry-standard security tools  
* Practice vulnerability assessment, exploitation, and incident response workflows  
* Automate security operations through scripting and orchestration  
* Document learnings and methodologies to share knowledge and demonstrate capability

---

## * Lab Infrastructure Overview

**Hypervisor:**  
- Proxmox VE installed on an HP ProLiant DL380e Gen8 server via iLO 4 remote management

**Virtual Machines:**  
- **pfSense:** Firewall and network segmentation
- **Suricata:** Intrusion Detection and Prevention System (IDS/IPS)
- **Wazuh:** SIEM and log management
- **ntopng:** Network traffic monitoring and analysis
- **Kali Linux:** Offensive security testing
- Additional Linux/Windows targets for vulnerability assessment

**Networking:**  
- Dedicated management VLAN
- Segmented lab networks with VLAN tagging
- Internal DNS and DHCP via pfSense

**Storage:**  
- Local SSD for Proxmox and VM storage
- NFS shares for backups and snapshots

---

## * Projects and Configurations

Below are the main components and configurations in this lab environment:

### * Proxmox Installation and Configuration
- Bare-metal installation via iLO remote ISO
- Storage and network configuration
- Email alerts and backups

➡ *Proxmox Setup Details*

---

### * pfSense Firewall Hardening
- VLAN segmentation and firewall rule sets
- Geo-blocking and DNS filtering with pfBlockerNG
- Suricata inline IDS/IPS integration

➡ *pfSense Configuration*

---

### * Suricata IDS/IPS
- Inline deployment with pfSense
- Custom rule tuning
- Logging and alerting

➡ *Suricata Configuration*

---

### * Wazuh SIEM
- Centralized log collection from all lab systems
- Custom dashboards and detection rules
- Test scenarios for alert workflows

➡ *Wazuh Setup*

---

### * ntopng Network Monitoring
- Flow analysis and per-host monitoring
- Custom traffic alerts and reports

➡ *ntopng Monitoring*

---

###  Security Scripts and Automation
- Bash and Python scripts for:
  - Automated backups
  - Log parsing and enrichment
  - Vulnerability scanning

➡ *Scripts*

---

## * CTF and Vulnerability Research Repositories

In addition to the lab environment, I maintain separate repositories documenting CTF challenges, writeups, and tooling:

- [VulnForge CTF](https://github.com/mangeeriiksson/VulnForge-CTF) – Vulnerability research and exploit development from VulnForge scenarios.
- [Ancicent](https://github.com/mangeeriiksson/ancicent) – Custom Python tools used in CTF exercises.
- [Mythic Journey CTF](https://github.com/mangeeriiksson/Mythic.journey.ctf) – Writeups and solutions for Mythic Journey CTF.
- [WRAPP3.0](https://github.com/mangeeriiksson/WRAPP3.0) – Web exploitation challenges and scripts.
- [Toolbox CTF](https://github.com/mangeeriiksson/toolbox.CTF) – Python utilities for automating CTF workflows.

---

## Key Skills and Tools Demonstrated

- Hypervisor and virtualization administration (Proxmox)
- Network segmentation and firewall configuration (pfSense)
- IDS/IPS deployment and tuning (Suricata)
- SIEM implementation and alerting (Wazuh)
- Traffic monitoring and analysis (ntopng)
- Offensive security techniques (Kali Linux)
- Scripting and automation (Bash, Python)
- Vulnerability research and exploit development

---

## * Screenshots and Documentation

*(Add screenshots of Proxmox, pfSense, Suricata, Wazuh dashboards here)*

---

## * Contact

If you want to learn more about my lab environment, CTF research, or discuss collaboration opportunities:

- **LinkedIn:** 
- **Email:** 

---
