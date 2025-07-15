# Cybersecurity Lab Environment

This project documents the design, deployment, and continuous improvement of my personal cybersecurity lab, built to simulate real-world enterprise environments for hands-on practice in offensive and defensive security.

The lab is designed to serve as a **comprehensive platform** to learn and demonstrate key competencies across multiple areas of cybersecurity, including network segmentation, intrusion detection and prevention, SIEM implementation, traffic monitoring, virtualization, and penetration testing.

---

### 🎯 Objectives and Purpose

The primary objectives of this lab environment are:

✅ To gain practical experience configuring and securing a hypervisor-based infrastructure  
✅ To practice deploying, hardening, and managing security tools commonly used in enterprise networks  
✅ To create realistic scenarios for testing incident detection, alerting, and response workflows  
✅ To conduct vulnerability assessments and penetration testing in a safe, controlled setting  
✅ To develop automation scripts to streamline security operations and maintenance tasks

---

## 🛠️ Lab Infrastructure Overview

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

## ⚙️ Projects and Configurations

### 🔹 1. Proxmox Installation and Configuration
- Installed Proxmox VE on dedicated SSD
- Configured networking and storage pools
- Enabled no-subscription repositories
- Set up email alerts and backup schedules

➡️ *Proxmox Setup Details*

---

### 🔹 2. pfSense Firewall Hardening
- Deployed pfSense VM as the primary firewall
- Configured:
  - VLANs
  - Firewall rules
  - Geo-blocking
  - pfBlockerNG
  - DNS filtering
- Enabled Suricata inline mode for IDS/IPS

➡️ *pfSense Configuration*

---

### 🔹 3. Suricata IDS/IPS
- Installed Suricata for real-time intrusion detection
- Tuned rulesets
- Integrated with pfSense
- Enabled alerting and logging

➡️ *Suricata Configuration*

---

### 🔹 4. Wazuh SIEM
- Deployed Wazuh server and agents
- Collected logs from all lab systems
- Configured dashboards and rules
- Tested alerting workflows

➡️ *Wazuh Setup*

---

### 🔹 5. ntopng Network Monitoring
- Monitored traffic flows and bandwidth
- Visualized protocols and hosts
- Created custom traffic alerts

➡️ *ntopng Monitoring*

---

### 🔹 6. Security Scripts and Automation
- Bash and Python scripts for:
  - Automated backups
  - Log parsing
  - Vulnerability scanning
  - Helper scripts for lab setup and reset

➡️ *Scripts*

---

### 🔹 7. Capture the Flag (CTF) Writeups
- Documented solutions for:
  - HackTheBox
  - TryHackMe
  - VulnHub
- Included screenshots and methodology

➡️ *CTF Writeups*

---

## 💡 Key Skills and Tools Demonstrated

- Virtualization and hypervisor administration
- Network segmentation and firewall configuration
- IDS/IPS deployment and tuning
- SIEM configuration and alerting
- Traffic monitoring and analysis
- Offensive security testing
- Scripting and automation

---

## 📸 Screenshots

*(You can add images here, e.g., Proxmox dashboard, pfSense interfaces, Wazuh alerts, Suricata logs)*

---

## 📫 Contact

If you want to know more about this lab environment or discuss cybersecurity projects:

- **LinkedIn:** 
- **Email:** 
