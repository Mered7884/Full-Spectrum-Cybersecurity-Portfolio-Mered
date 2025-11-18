📘 Windows Event Log Threat Detection

A Blue Team project by Mered Mulugeta

🔍 Project Summary

This project focuses on detecting malicious activity using Windows Event Logs, building detection rules, and documenting investigation workflows based on real-world threat behaviors.

🧱 Project Structure
Windows-Event-Log-Threat-Detection/
│
├── Data-Samples/            # Raw Event Log samples (XML, JSON, EVTX)
├── Detection-Rules/         # Sigma rules, custom rules, YAML detections
├── Investigation-Notes/     # Step-by-step investigations
├── Screenshots/             # Analysis screenshots
└── README.md                # Project overview

🎯 Objectives

Understand and analyze Windows Event IDs used in threat detection.

Build Sigma-style detection rules.

Simulate and document real-world threat scenarios.

Develop Blue Team investigation and triage documentation.

🛑 Threat Scenarios Covered

Examples (you will add them as we build):

Suspicious PowerShell Execution

Event ID 4104 — PowerShell Script Block Logging

Event ID 4688 — New Process Creation

Brute Force Logon Attempts

Event ID 4625 — Failed Logons

Event ID 4768 — Kerberos Authentication Requests

Privilege Escalation Attempts

Event ID 4672 — Special Privileges Assigned

Persistence Techniques

Event ID 7045 — New Service Installed

🛠️ Tools and Technologies

Windows Event Viewer

Sysmon

Sigma Rules

PowerShell

ELK / Splunk (optional for advanced visualization)

🧪 How to Use This Project

Open the Data-Samples/ folder → review event logs.

Open the Detection-Rules/ folder → view detection logic.

Open the Investigation-Notes/ folder → follow analysis steps.

Use the repository to demonstrate Blue Team skills.

📝 Future Improvements

Add automated detection testing (e.g., Invoke-AtomicRedTeam).

Add visual dashboards.

Add MITRE ATT&CK mappings.

👤 Author

Mered Mulugeta
Cybersecurity | SOC Analyst | Blue Teaming | Threat Detection

✅ NEXT STEP