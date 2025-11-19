📘 Windows Event Log Threat Detection
A Complete Blue Team / SOC Analyst Project by Mered Mulugeta
🔍 Project Summary

This end-to-end project simulates how SOC Analysts, Threat Hunters, and Blue Team professionals detect, investigate, and respond to malicious activity using Windows Event Logs.
It includes:

Real & simulated Windows security events

Detection rule creation (Sigma-style YAML rules)

Threat hunting analysis

Incident investigation workflows

Power BI dashboards

CSV datasets for visualization

A realistic attack storyline and full SOC documentation

This project is built for portfolio visibility, to help recruiters quickly understand your capabilities in log analysis, detection engineering, and cyber defense.

🧱 Project Structure
Windows-Event-Log-Threat-Detection/
│
├── Data-Samples/               # Raw & cleaned event logs (XML, CSV, JSON)
├── Detection-Rules/            # Sigma-style rules, YAML detections
├── Investigation-Notes/        # SOC investigation steps, incident timeline
├── Screenshots/                # Dashboards, event logs, detections
└── README.md                   # Project overview (this file)

🎯 Objectives

This project demonstrates job-ready skills that SOC Analysts and Threat Hunters use daily:

Understand and analyze critical Windows Event IDs

Extract and process logs for detection and hunting

Build Sigma-style detection rules

Identify brute force, persistence, lateral movement & PowerShell abuse

Create an incident investigation timeline

Visualize threats using Power BI dashboards

Document findings like a real SOC case

Present Blue Team skills to recruiters

🔥 Threat Scenarios Covered

This project includes beginner → expert level threat scenarios mapped to real-world attack behavior.

1. Brute Force Logon Attacks

Event ID 4625 — Failed Logons

Event ID 4624 — Successful Logons

Event ID 4768/4769 — Kerberos authentication

Indicators of RDP brute force attacks

Correlation with authentication success

2. Suspicious PowerShell Execution

Event ID 4104 — Script Block Logging

Event ID 4688 — New Process Creation

Event ID 800 — PowerShell Operational logs

Encoded commands, download Cradles, recon commands

3. Privilege Escalation

Event ID 4672 — Special Privileges Assigned

Event ID 4728/4732 — User added to privileged group

4. Persistence Techniques

Event ID 4698 — Scheduled Task Created

Event ID 7045 — New Service Installed

5. Defense Evasion

Event ID 1102 — Security Log Cleared

6. Full Attack Storyline

The project includes a complete adversary simulation from:
Brute force → Compromise → PowerShell → Persistence → Log clearing.

🛠️ Tools & Technologies Used

Windows Event Viewer

Sysmon (System Monitor) for enhanced visibility

PowerShell (log parsing)

Sigma Rules & YAML detections

Elastic / Splunk (optional advanced)

MITRE ATT&CK Framework

Power BI dashboards

CSV Datasets for visualization

📊 Power BI Visualizations (Included in Project)

You will create dashboards using CSV datasets, including:

Brute Force Attack Heatmap

Successful vs Failed Logon Timeline

PowerShell Malicious Activity Dashboard

Suspicious Account Modifications

Event Volume by Severity

Attack Kill-Chain Walkthrough

These screenshots will be stored in the /Screenshots/ folder.

🧪 How to Use This Project

Open Data-Samples/
Explore XML/CSV event logs (malicious + normal activity).

Review Detection-Rules/
Look at Sigma-style detection logic for each attack technique.

Explore Investigation-Notes/
See a complete SOC investigation, timeline, and findings.

Check Screenshots/
Contains images of logs, dashboards, and detections.

Import CSV files into Power BI
Build dashboards included in this project.

Use the README to present the project during job interviews.

📝 Skills Demonstrated

This project highlights:

Log analysis

Threat hunting

TTP detection

Sysmon expertise

Incident response

Detection engineering

Correlation of event IDs

Power BI cybersecurity reporting

Documentation & SOC communication

MITRE ATT&CK mapping

These match real SOC job descriptions.

🚀 Future Improvements

Add Atomic Red Team automated tests

Add Elastic SIEM dashboards

Add KQL queries for Microsoft Sentinel

Add a Sysmon configuration file

Expand to include malware artifacts & DFIR triage

👤 Author

Mered Mulugeta
Cybersecurity | SOC Analyst | Blue Team | Threat Detection
GitHub Portfolio • Windows Event Log Threat Detection Project