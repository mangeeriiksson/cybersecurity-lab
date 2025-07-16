This directory documents the installation and configuration of Wazuh as a Security Information and Event Management (SIEM) solution in my cybersecurity lab environment.

---

## * Purpose

Wazuh was deployed to:

- Collect logs and security events from all lab systems
- Correlate data from Suricata, pfSense, and hosts
- Generate alerts on suspicious activity
- Provide dashboards for monitoring and incident response

---

## * Installation

Wazuh was installed on a dedicated Ubuntu virtual machine in the lab.

Steps included:

1. Installing the Wazuh server and API
2. Installing the Wazuh indexer (OpenSearch)
3. Deploying the Wazuh dashboard
4. Configuring SSL certificates for secure communication
5. Creating agents for monitored hosts

---

## * Configuration Details

Key configurations:

- **Log Collection:**
  - pfSense firewall logs
  - Suricata alerts
  - System logs from Linux and Windows VMs
- **Rules and Decoders:**
  - Enabled default Wazuh ruleset
  - Added custom decoders for pfSense events
- **Alerts:**
  - Configured email notifications for critical events
  - Tuned rules to reduce false positives
- **Dashboards:**
  - Created visualizations for firewall events, IDS alerts, and host security events

---

## * Monitoring and Reporting

The Wazuh dashboard provides:

- Real-time overview of security events
- Alert categorization by severity
- Historical analysis of incidents
- Drill-down into raw logs

---

## * Lessons Learned

- Resource allocation is critical for performance in all-in-one Wazuh deployments
- pfSense logs require proper syslog configuration for compatibility
- Rule tuning significantly reduces noise and improves alert quality

---

## * Screenshots

*(Add screenshots here, e.g., Wazuh dashboards, ruleset configuration, alert views.)*

---

## * References

- [Wazuh Documentation](https://documentation.wazuh.com/)
- [Wazuh Install Guide](https://documentation.wazuh.com/current/installation-guide/index.html)

---

## * Contact

For questions about this configuration or lab environment:

- **LinkedIn:** 
- **Email:** 
