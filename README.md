# WannaCry SOC Investigation Lab

## Overview

This project simulates a WannaCry ransomware attack investigation in an isolated virtual lab environment.

The objective was to:

* perform SMB enumeration,
* identify vulnerable services,
* exploit MS17-010 using EternalBlue,
* simulate ransomware behavior,
* collect Indicators of Compromise (IOCs),
* and document defensive mitigation strategies.

---

## Lab Environment

### Attacker Machine

* Kali Linux

### Victim Machine

* Windows 7

### Tools Used

* Nmap
* Metasploit Framework
* Wireshark
* Windows Event Viewer

---

## Attack Workflow

1. Network scanning
2. SMB enumeration
3. Vulnerability identification
4. EternalBlue exploitation
5. Meterpreter session establishment
6. WannaCry ransomware simulation
7. IOC collection
8. MITRE ATT&CK mapping
9. Mitigation planning

---

## Skills Demonstrated

* SOC Investigation
* Threat Hunting
* Malware Analysis
* Incident Response
* Network Traffic Analysis
* MITRE ATT&CK Mapping
* Vulnerability Assessment

---

## MITRE ATT&CK Techniques

| Technique                       | ID    |
| ------------------------------- | ----- |
| Active Scanning                 | T1595 |
| Network Service Discovery       | T1046 |
| Exploitation of Remote Services | T1210 |
| Ingress Tool Transfer           | T1105 |
| Data Encrypted for Impact       | T1486 |

---

## Indicators of Compromise

### Network Indicators

* SMB Port 445
* Reverse shell traffic

### File Indicators

* .WNRY
* .WNCRY
* @WanaDecryptor@

---

## Mitigation Recommendations

* Disable SMBv1
* Patch MS17-010
* Implement endpoint monitoring
* Use network segmentation
* Maintain offline backups

---

## Disclaimer

This project was conducted in a controlled lab environment strictly for educational and defensive cybersecurity purposes.
