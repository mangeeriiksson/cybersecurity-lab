# ntopng Network Monitoring

This directory documents the installation, configuration, and usage of ntopng for real-time network monitoring in my lab environment.

---

## * Purpose

ntopng was deployed to visualize and analyze traffic flowing through the pfSense firewall and other network segments in the lab.

The main objectives were:
- Monitor traffic flows between VLANs
- Identify top talkers, protocols, and hosts
- Create alerts on unusual patterns or thresholds
- Improve visibility for incident detection

---

## * Installation

ntopng was installed on a dedicated virtual machine running Debian Linux.

Key steps included:
- Adding the ntopng repository and installing packages
- Configuring data retention and interfaces
- Setting up authentication and HTTPS access

---

## * configuration

Some notable configuration options:
- Flow collection from mirrored pfSense interfaces
- DNS enrichment enabled
- Traffic thresholds configured for alerting
- Integration with Elastic Stack for logs (optional)

---

## * Screenshots

*(Add screenshots here later, e.g., traffic dashboards, host views.)*
*(Comming soon)*
---

## * Lessons Learned

- Flow data is extremely valuable for understanding network behavior.
- DNS enrichment makes investigation much easier.
- Resource usage can be significant on busy networks; tuning is important.

---

## * References

- [ntopng Documentation](https://www.ntop.org/guides/ntopng/)
- [pfSense Port Mirroring](https://docs.netgate.com/pfsense/en/latest/)

---

## * Contact

For questions about this configuration or lab environment:

- **LinkedIn:** 
- **Email:** 
