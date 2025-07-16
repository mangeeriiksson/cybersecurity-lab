# Proxmox VE Installation and Configuration

This directory documents the installation and configuration of Proxmox Virtual Environment (VE), which serves as the hypervisor platform for my cybersecurity lab.

---

## * Purpose

Proxmox was deployed to:

- Provide a flexible and efficient virtualization platform
- Host virtual machines for security tools, firewalls, and targets
- Enable snapshotting and backups of lab environments
- Support VLAN-based network segmentation

---

## * Installation

Proxmox VE was installed on an HP ProLiant DL380e Gen8 server using iLO remote management.

Key installation steps:

1. Created bootable USB with the Proxmox VE ISO
2. Accessed iLO remote console to mount ISO and start installation
3. Installed Proxmox on dedicated SSD storage
4. Configured management network interface and static IP
5. Applied updates and enabled the no-subscription repository

---

## * Configuration Details

Main configurations:

- **Networking:**
  - Created Linux bridges for VLAN tagging
  - Isolated management, lab, and storage traffic
- **Storage:**
  - Configured local SSD for VM disks
  - Added NFS shares for backups and templates
- **Security:**
  - Enabled HTTPS access to the web interface
  - Configured two-factor authentication for root user
- **Backups:**
  - Scheduled nightly backups of critical VMs

---

## * Monitoring

Proxmox is monitored via:

- Email notifications for failures and updates
- Resource usage dashboards in the web GUI
- ntopng and Wazuh for external network and log monitoring

---

## * Lessons Learned

- Proper VLAN planning simplifies VM network isolation
- iLO remote console is invaluable for headless server deployments
- Regular snapshotting speeds up lab resets

---

## * Screenshots

*(Add screenshots here, e.g., Proxmox dashboard, VM configuration, storage pools.)*
*(Comming soon)*

---

## * References

- [Proxmox VE Documentation](https://pve.proxmox.com/wiki/Main_Page)
- [Proxmox Networking Guide](https://pve.proxmox.com/wiki/Network_Configuration)

---

## * Contact

For questions about this configuration or lab environment:

- **LinkedIn:** 
- **Email:** 

