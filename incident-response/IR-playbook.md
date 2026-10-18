# Incident Response Playbook
## Purpose
This document outlines the steps for detecting, analyzing, and responding to cybersecurity incidents in a SOC environment.

## Steps
1. Identify suspicious activity in SIEM.
   -Review alerts for anomalies in user behavior or network traffic.
3. Validate alerts using threat intelligence.
   -Cross-check indicators against known malicious IP's or domains.
5. Contain affected systems.
   -Isolate endpoints or servers to prevent lateral movement
7. Eradicate malware or unauthorized access.
   -Remove malicious files and reset compromised credentials.
9. Recover and document lessons learned.
    -Restore systems, verify integrity, and update playbooks.
 



   ## Tools Used
-Splunk -SIEM alerting and log analysis
-Wireshark-packet capture and network investigation
-Virus Total-malware and URL reputation checking

## Roles and Responsibilities
-** SOC Analyst: ** Detects, validates, and escalates alerts
- ** Incident Manager: ** Coordinates containment, eradication, and recovery.
- ** Threat Hunter: ** Investigates root causes, patterns, and advanced threats.
- ** System Administrator: ** Restores systems, patches vulnerabilities, and verifies integrity.
- 
- ## References
- NIST SP 800-61r2-Computer Security Incident Handling Guide
- MITRE ATT&CK Framework- Tactics, techniques, and procedures
- CIS Controls v8-Security best practices and hardening guidelines
