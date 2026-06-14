[Snapshot Configuration]

- Created Windows 7 clean snapshot before ransomware simulation
- Snapshot Name: Fresh Snapshot
- Purpose: restore victim machine after malware execution

- Created Kali Linux attacker snapshot
- Purpose: maintain reusable attacker environment


[Network Verification]

- Windows 7 victim machine received IP: 10.0.2.4
- Kali Linux attacker connected to same NAT Network
- Successful ICMP communication verified between attacker and victim systems

[Reconnaissance]

- Performed host discovery scan using Nmap
- Active hosts identified in isolated NAT Network
- Windows victim machine detected at 10.0.2.4

[Vulnerability Assessment]

- Performed vulnerability enumeration using Nmap NSE scripts
- MS17-010 vulnerability detected on Windows 7 victim machine

[Exploitation Preparation]

- Launched Metasploit Framework for controlled exploitation testing
- Prepared environment for EternalBlue simulation

[Exploit Enumeration]

- Searched Metasploit modules related to MS17-010
- Identified EternalBlue exploitation module and SMB scanner module

[Exploit Module Selection]

- Loaded EternalBlue exploit module inside Metasploit
- Prepared SMB exploitation workflow for MS17-010 vulnerability

[Exploit Configuration Review]

- Reviewed Metasploit exploit parameters
- Identified required fields including RHOSTS, RPORT, and LHOST

[Target Configuration]

- Configured Metasploit RHOSTS parameter with Windows 7 victim IP
- Verified exploit target configuration before execution

[Exploitation Execution]

- Executed EternalBlue exploit against Windows 7 SMB service
- Attempted controlled remote access through MS17-010 vulnerability

[Post-Exploitation Validation]

- Meterpreter session established successfully
- Verified remote access against Windows 7 victim system

[Session Enumeration]

- Verified compromised user context through Meterpreter session
- Identified privilege level and active user environment

[Payload Transfer Preparation]

- Established SYSTEM-level Meterpreter access on Windows 7 victim machine
- Prepared controlled ransomware sample transfer for isolated lab analysis

[Payload Upload]

- Uploaded ransomware simulation sample to Windows 7 victim machine
- Verified payload presence inside target filesystem

[Ransomware Execution]

- Executed ransomware simulation sample through Meterpreter session
- Began controlled observation of victim system behavior within isolated lab

[Incident Investigation]

- Began post-compromise forensic investigation on infected Windows 7 system
- Collected active process information from compromised host

[Network Investigation]

- Collected active network connection data from compromised Windows 7 host
- Investigated suspicious communication channels and SMB-related activity

[Impact Assessment]

- Investigated ransomware-related filesystem artifacts
- Identified encrypted files, modified extensions, and ransom note indicators

[Windows Event Investigation]

- Investigated Windows Event Viewer logs on compromised system
- Reviewed system and application events related to ransomware activity

[Windows Event Investigation]

- Investigated Windows Event Viewer logs on compromised system
- Reviewed system and application events related to ransomware activity

[Network Traffic Analysis]

- Investigated SMB-related network traffic using Wireshark
- Observed communication between attacker and compromised victim system

[Packet Analysis]

- Captured SMB negotiation traffic between attacker and victim systems
- Observed TCP handshake and SMB protocol communication associated with enumeration activity
- Preserved packet capture evidence in PCAP format

