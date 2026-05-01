# 🔐 Cybersecurity Home Lab: Active Directory, Firewall Segmentation, Attack Simulation, & SIEM Logging

This project focuses on building a cybersecurity home lab that simulates a real-world enterprise environment. It demonstrates how network segmentation, identity systems, and security monitoring work together to detect malicious activity. The lab is designed to provide hands-on experience with SOC operations, including log analysis and attack detection using a SIEM.

---

## 👨🏼💻 Performed Tasks

- **Network Architecture Design**
  - User Zone: `10.0.0.0/24`
  - Server Zone: `172.16.10.0/24`

- **Active Directory Setup**
  - Deployed Windows Server 2022 domain environment
  - Created and managed domain users and privilege groups
  - Simulated endpoint activity (local user creation)

- **SIEM Configuration**
  - Configured Wazuh SIEM for centralized log collection
  - Installed and configured Wazuh agents 
  - Configured Syslog forwarding (Palo Alto → Wazuh)

- **Network Security**
  - Deployed pfSense as gateway
  - Implemented Palo Alto firewall for network segmentation

- **Attack Simulation & Reconnaissance**
  - Permormed malicious cmd and powershell on windows 10 and AD server respectively 
  - Performed attack simulation using Kali Linux (internal compromised machine)
  - Conducted network reconnaissance using:
    - Nmap
    - Gobuster

- **Log Analysis & Detection**
  - Observed and analyzed logs for:
    - SSH brute force attempts
    - FTP authentication events
    - Web server errors
    - AD privilege escalation

---

## 🎓 Skills Gained

- Understanding how logs flow from endpoints, servers, and firewalls into a SIEM
- Detecting real attack behavior using event logs and correlation
- Working with Active Directory and identity-based attacks
- Applying network segmentation and firewall rules
- Analyzing attacks and suspicious activity in logs

---

## 📝 Summary

This project provided practical experience in building and monitoring a SOC environment and understanding how different security components interact in real-world scenarios.
