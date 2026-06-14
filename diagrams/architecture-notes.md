# Lab Architecture Overview

## Components

### Kali Linux
Role:
- Attacker machine
- Nmap scanning
- EternalBlue exploitation
- Meterpreter session handling
- Wireshark packet analysis

IP Address:
- 10.0.2.3

---

### Windows 7 Victim
Role:
- Vulnerable SMB target
- MS17-010 exploitation victim
- Ransomware execution environment
- Forensic evidence source

IP Address:
- 10.0.2.4

---

## Attack Flow

1. Host discovery performed through Nmap
2. SMB service identified on Windows 7 target
3. MS17-010 vulnerability confirmed
4. EternalBlue exploit executed
5. Meterpreter session established
6. SYSTEM-level access obtained
7. WannaCry sample uploaded
8. Ransomware executed
9. Files encrypted with ransomware extensions
10. SOC investigation initiated
11. Packet analysis and IOC collection performed

---

## Defensive Components

- Windows Event Viewer
- Wireshark packet analysis
- IOC collection
- MITRE ATT&CK mapping
- Sigma detection rules
- Root cause analysis
- Mitigation planning