# Phase 1 — Project Setup Procedure  
**Windows Event Log Threat Detection Project**  
**Version:** 1.0  
**Author:** Mered Wassie  
**Date:** <Nov-19-2025>

---

## 🎯 Objective
Document the exact steps performed during Project Phase 1 so that the setup is fully reproducible by SOC analysts, cybersecurity students, or hiring managers reviewing the portfolio.

---

## 1.1 Understanding Windows Event Logs
### Summary
Windows Event Logs record all important security and system activities.  
I reviewed:
- Security logs  
- System logs  
- PowerShell logs  
- Sysmon logs  

### Key Event Log Categories
- **Security.evtx** — authentication, logon attempts, account changes  
- **System.evtx** — driver failures, service issues  
- **Application.evtx** — installed applications logging errors  
- **PowerShell.evtx** — script execution (Event ID 4104)  
- **Sysmon Operational Logs** — process creation, network connections, registry changes  

This knowledge is critical for threat detection in later phases.

---

## 1.2 Creating Folder Structure
Created the main project directory:

Windows-Event-Log-Threat-Detection/

yaml
Copy code

Added subfolders for:
- Raw logs  
- Parsed logs  
- Sample logs  
- Detections  
- Sigma rules  
- Investigation notes  
- Screenshots  
- Documentation  

Aligned fully with the project roadmap.

---

## 1.3 Installing Needed Tools
Installed the following tools on Windows:

### ✔ Sysinternals Sysmon  
Used for process-level and network telemetry.

### ✔ Python 3.13  
Verified installation: