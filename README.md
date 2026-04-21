# SOC & Pentesting Portfolio

This repository contains a complete SOC L2 investigation lab along with an extensive collection of hands‑on
penetration testing exercises and tooling notes.
The project demonstrates both defensive and offensive security skills through attack simulations,
log analysis, SIEM investigation, exploitation workflows, and privilege escalation techniques.

Live Portfolio:
https://lmudir.github.io/

---

## SOC Investigation Cases

These cases simulate realistic attacker activity across Windows and Linux systems, with full SIEM visibility,
timeline reconstruction, and incident documentation.

### 0. Lab Setup
Virtual machines, network layout, Wazuh SIEM, DFIR‑IRIS, Sysmon, auditd, and service configuration.

### 1. Case 1 – Web Server Intrusion Attempt (Linux / Grav CMS)
Reconnaissance, directory enumeration, weak credential attempts, SIEM alerts, and IR documentation.

### 2. Case 2 – Windows Host Compromise Attempt
Network scanning, SMB enumeration, brute force attempts, WinRM probing, LSASS access detection.

### 3. Case 3 – Multi‑Stage Intrusion Simulation
Phishing → LNK execution → mshta → C2 beacon → data exfiltration.
Full timeline reconstruction and MITRE ATT&CK mapping.

---

## Hands‑On Pentesting Labs

This portfolio also includes more than 40 practical exploitation writeups, covering:

### HackTheBox Machines
Real‑world Linux and Windows challenges involving web exploitation, misconfigurations, privilege escalation,
and service abuse.

### Vulnhub Machines
Locally hosted vulnerable VMs focused on enumeration fundamentals, web vulnerabilities, and Linux privilege
escalation.

### OffSec Proving Grounds
Short, targeted exploitation exercises aligned with OSCP‑style workflows.

Each writeup follows a structured methodology:
- Reconnaissance
- Service enumeration
- Vulnerability analysis
- Exploitation
- Privilege escalation
- Key takeaways

---

## Active Directory Attack Lab

A dedicated lab demonstrating 20+ AD attack techniques, including:

- Kerberoasting / AS‑REP Roasting
- Pass‑the‑Hash / Pass‑the‑Ticket
- DCSync / DCShadow
- Delegation abuse (Unconstrained, Constrained, RBCD)
- ACL abuse, AdminSDHolder persistence
- LSASS dumping and credential extraction

Each attack includes:
- Preconditions
- Step‑by‑step execution
- Screenshots

---

## More Tools

A growing collection of notes and practical usage examples for security tools used in cybersecurity.

---

## Skills Demonstrated

### Defensive / SOC
- Log analysis (Windows Event Logs, Sysmon, Nginx access/error logs)
- SIEM investigation and alert correlation (Wazuh)
- Threat detection and pattern recognition
- Incident documentation and timeline reconstruction (DFIR‑IRIS)
- MITRE ATT&CK technique identification and mapping
- Threat hunting queries and filtering
- Analysis of attacker behavior and TTPs

### Offensive / Pentesting
- Enumeration (web, network, service)
- Web exploitation (SQLi, LFI/RFI, file upload, CMS vulnerabilities)
- Linux & Windows privilege escalation
- Password cracking and credential harvesting
- Reverse shells, tunneling, and port forwarding
- Simple exploit development and PoC adaptation

---

## Tools & Technologies

Wazuh SIEM
DFIR‑IRIS (Case Management)
Velociraptor (Endpoint Forensics & Response)
Sysmon
MITRE ATT&CK Framework
NetExec
Impacket Toolkit
BloodHound
Responder / LLMNR poisoning
Kali Linux Tooling
Metasploit Framework
Burp Suite & ZAP
ffuf / gobuster
nmap (NSE scripts)
Hydra / Hashcat
John the Ripper
SecLists (wordlists & payloads)
SSH / Socat / Chisel tunneling
And more

---

## Repository Structure

- /images/                     # Screenshots used
- /htb/                        # HackTheBox machine writeups
- /vulnhub/                    # Vulnhub machine writeups
- /offsec_proving_grounds/     # OffSec Proving Grounds writeups
- /more_tools/                 # Cybersecurity tools
- index.html                   # Main portfolio page
- soc_lab_setup.html           # Lab environment setup
- case_1.html                  # Case 1 documentation
- case_2.html                  # Case 2 documentation
- case_3.html                  # Case 3 documentation
- ad_attacks_lab.html          # Active Directory attack lab
- htb.html                     # HTB index page
- vulnhub.html                 # Vulnhub index page
- offsec_proving_grounds.html  # OPG index page
- more_tools.html              # Tools index page
