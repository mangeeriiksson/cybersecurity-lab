This directory documents the installation and configuration of Suricata as an Intrusion Detection and Prevention System (IDS/IPS) in my cybersecurity lab environment.

---

## * Purpose

Suricata was deployed to:

- Monitor and inspect traffic between VLAN segments
- Detect malicious activity and policy violations
- Block unwanted traffic inline when appropriate
- Generate logs and alerts for correlation in Wazuh

---

## * Installation

Suricata was installed as a package within pfSense and configured to run in inline IPS mode on selected interfaces.

Installation steps included:

1. Installing Suricata via pfSense package manager
2. Enabling IPS mode for active blocking
3. Selecting interfaces for monitoring (WAN, VLANs)
4. Updating rulesets from Emerging Threats and Proofpoint VRT
5. Configuring automatic rule updates

---

## * configuration Details

Notable configurations:

- **Detection Mode:** Inline IPS with auto-drop
- **Rulesets:** Emerging Threats Open, Snort GPL
- **Performance:** Hyperscan enabled for high-speed pattern matching
- **Logging:** Enabled unified2 output for external SIEM ingestion
- **Thresholds:** Tuned alert frequency and suppression lists to reduce false positives

---

## * Monitoring and Logging

Suricata logs and alerts are:

- Forwarded to Wazuh for correlation and alerting
- Stored locally on pfSense with rotation policies
- Available in the pfSense GUI for real-time analysis

---

## * Lessons Learned

- Inline mode requires careful tuning to avoid false positives disrupting legitimate traffic
- Rule management is critical to maintain performance
- Hyperscan improves performance significantly on modern CPUs

---

## * Screenshots

*(Add screenshots here, e.g., Suricata dashboard, rule configuration, alert logs.)*

---

## * References

- [Suricata Documentation](https://suricata.io/docs/)
- [Suricata on pfSense](https://docs.netgate.com/pfsense/en/latest/packages/suricata.html)

---

## * Contact

For questions about this configuration or lab environment:

- **LinkedIn:** [Your LinkedIn URL]
- **Email:** [Your Email Address]
