# SOC Lab Portfolio

This repository contains a complete SOC L2 lab environment and three fully documented incident response cases.  
The project simulates realistic attacker activity across Windows and Linux systems, with SIEM visibility, log analysis, and incident documentation.

**Link:**  
[https://lmudir.github.io/](https://lmudir.github.io/)

---

## Cases

- **0. Lab Setup**  
  Virtual machines, network layout, Wazuh SIEM, DFIR‑IRIS, Sysmon, auditd, and service configuration.

- **1. Case 1 – Web Server Intrusion Attempt (Linux / Grav CMS)**  
  Reconnaissance, directory enumeration, weak credential attempts, SIEM alerts, and IR documentation.

- **2. Case 2 – Windows Host Compromise Attempt**  
  Network scanning, SMB enumeration, brute force attempts, WinRM probing, LSASS access detection.

- **3. Case 3 – Multi‑Stage Intrusion Simulation**  
  Phishing → LNK execution → mshta → C2 beacon → data exfiltration.  
  Full timeline reconstruction and MITRE ATT&CK mapping.

---

## Skills Demonstrated

- Log analysis (Windows Event Logs, Sysmon, Nginx access/error logs)
- SIEM investigation and alert correlation (Wazuh)
- Threat detection and pattern recognition
- Incident documentation and timeline reconstruction (DFIR‑IRIS)
- MITRE ATT&CK technique identification and mapping
- Basic threat hunting queries and filtering
- Analysis of attacker behavior and TTPs

---

## Tools & Technologies

- Wazuh SIEM  
- DFIR‑IRIS  
- Kali Linux  
- Windows 10  
- Ubuntu Server (Grav CMS + Nginx)  
- Sysmon  
- auditd  
- MITRE ATT&CK Framework  

---

## Repository Structure

- /images/ — Screenshots used in the cases  
- case_1.html — Case 1 documentation  
- case_2.html — Case 2 documentation  
- case_3.html — Case 3 documentation  
- soc_lab_setup.html — Lab environment setup  
- index.html — Main portfolio page

---

This project was created to demonstrate practical SOC L2 investigation skills through hands‑on attack simulations and incident response workflows.
