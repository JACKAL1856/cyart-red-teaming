Threat Detection and SOC Engineering Labs

This repository contains hands-on SOC engineering and threat detection labs focused on real-world security monitoring, adversary behavior analysis, and defensive controls. The work reflects practical exposure to enterprise SOC workflows, detection engineering concepts, and incident investigation methodologies.

Project Overview

The objective of this repository is to simulate real SOC operations and security engineering tasks commonly performed in enterprise environments. The labs emphasize log analysis, intrusion detection, malware triage, vulnerability assessment, and adversary emulation in controlled lab settings.

Key Areas of Work

Log Analysis and SIEM Monitoring  
Performed centralized log analysis using the ELK stack to identify anomalous activity, monitor HTTP traffic patterns, and analyze response codes through Kibana dashboards.

Malware Analysis and File Reputation  
Conducted malware reputation checks and antivirus-based analysis to evaluate suspicious files, interpret detection confidence, and support SOC-level triage decisions.

Static Malware Analysis  
Performed static analysis of executable files using PEframe to extract metadata, hashes, strings, and indicators without execution.

Vulnerability Assessment and Risk Analysis  
Reviewed vulnerability scan results, analyzed CVSS severity, and documented findings to support risk-based prioritization and remediation planning.

Intrusion Detection and Alert Engineering  
Configured and tested Suricata IDS, created custom detection rules, and analyzed alert logs to understand network-based threat detection.

Adversary Emulation and Detection Validation  
Deployed and configured MITRE Caldera to simulate adversary techniques and support validation of defensive visibility and detection coverage.

MITRE ATT&CK Alignment

The labs align with multiple MITRE ATT&CK tactics, including reconnaissance, initial access, execution, defense evasion, discovery, command and control, and impact. The framework was used to understand attacker behavior and improve detection logic.

Tools and Technologies

ELK Stack  
Suricata IDS  
MITRE Caldera  
PEframe  
Malware Analysis Platforms  
Kali Linux  
Python and Virtual Environments

SOC Relevance

This repository demonstrates practical SOC capabilities such as alert monitoring, threat investigation, malware triage, vulnerability analysis, and detection engineering fundamentals. The work mirrors responsibilities typically handled by SOC Analysts and Security Engineers.

Disclaimer

All activities were conducted in isolated lab environments strictly for educational and defensive security purposes.

