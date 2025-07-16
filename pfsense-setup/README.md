This directory documents the installation, configuration, and hardening of pfSense, which serves as the main firewall and network segmentation component in my cybersecurity lab environment.

---

## * Purpose

The primary purpose of deploying pfSense in the lab was to:

- Segment and isolate virtual networks using VLANs
- Implement strong firewall policies and NAT rules
- Provide DNS and DHCP services internally
- Integrate inline intrusion detection/prevention with Suricata
- Enable advanced filtering and blocking using pfBlockerNG

---

## * Installation

pfSense was installed as a virtual machine on the Proxmox hypervisor.

Key installation steps included:

1. Creating a new VM with adequate CPU and memory allocation
2. Mounting the pfSense ISO image
3. Configuring virtual network interfaces (WAN, LAN, optional VLAN interfaces)
4. Running the pfSense installer and initial configuration wizard

---

## * Hardening and Configuration

Some of the hardening measures and configurations implemented:

- Enabling HTTPS for the web interface
- Changing default admin credentials and restricting GUI access
- Configuring multiple VLAN interfaces for lab segmentation
- Creating firewall rule sets to control inter-VLAN traffic
- Setting up GeoIP blocking and DNS filtering via pfBlockerNG
- Integrating Suricata IDS/IPS in inline mode on selected interfaces
- Enabling logging for all firewall rules

---

## * Monitoring

pfSense is configured to export logs to:

- Wazuh SIEM for event correlation
- ntopng for traffic flow analysis

Daily backups of the configuration are automated and stored securely.

---

## * Lessons Learned

- VLAN configuration requires careful planning to avoid conflicts with Proxmox bridges
- Suricata inline mode can impact performance if not properly tuned
- pfBlockerNG is highly effective for filtering malicious domains and IPs

---

## * Screenshots

*(Add screenshots here, e.g., VLAN interface configuration, pfBlockerNG dashboard, firewall rules.)*
*(Comming soon)*

---

## * References

- [pfSense Documentation](https://docs.netgate.com/pfsense/en/latest/)
- [pfBlockerNG Guide](https://docs.netgate.com/pfsense/en/latest/packages/pfblocker.html)
- [Suricata on pfSense](https://docs.netgate.com/pfsense/en/latest/packages/suricata.html)

---

## * Contact

For questions about this configuration or the lab environment:

- **LinkedIn:**
- **Email:** 
