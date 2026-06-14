# Incident Timeline Reconstruction

| Time/Phase | Activity |
|---|---|
| Reconnaissance | Performed host discovery using Nmap |
| Enumeration | Identified SMB service on port 445 |
| Vulnerability Assessment | Confirmed MS17-010 vulnerability |
| Exploitation | Executed EternalBlue exploit through Metasploit |
| Initial Access | Meterpreter session established |
| Privilege Level | SYSTEM-level access confirmed |
| Payload Delivery | Uploaded ransomware simulation sample |
| Ransomware Execution | Executed WannaCry sample on victim machine |
| Impact | Files encrypted with .WNCRY / .WNRY extensions |
| Investigation | Collected process, network, and filesystem evidence |
| Detection Engineering | Created Sigma detection rules |
| Mitigation Planning | Documented hardening and remediation recommendations |