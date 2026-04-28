# soc Analysis Projects
This repository contains multiple cybersecurity analysis projects created during my training.
1. SOC Analysis – Bongo Dataset

Analysis of suspicious HTTP activity.

Key Findings
Automated scans (phpMyAdmin, WordPress, config files)
One unsuccessful command injection attempt
No confirmed compromise
Severity

Low

2. Splunk Log Analysis (Firewall, VPN, IDS)

Analysis of network logs to identify suspicious activity and correlate events.

Key Findings
External IPs performed port scanning and gained VPN access
Internal reconnaissance and lateral movement detected
C2 beaconing from internal host (10.0.0.60)
Suspicious activity on service account (svc_backup)
