Explanations by Detection
1. Windows Brute Force / Failed Login (4625)

Why it matters: Detects attackers attempting multiple password guesses. Early detection prevents account compromise and lateral movement.

Interview note: Explain difference between brute force, password spraying, and how timeframe & count thresholds help reduce false positives.

2. RDP Brute Force (4625 via RDP)

Why it matters: External attackers often use RDP to gain remote access. Detecting failed attempts stops unauthorized access to critical systems.

Interview note: Mention monitoring source IPs, geolocation, and correlation with VPN usage.

3. PowerShell Abuse (4104)

Why it matters: PowerShell is widely abused in fileless malware and post-exploitation. Detecting encoded scripts or suspicious modules can block attacks before they escalate.

Interview note: Explain event IDs 4103 vs 4104, why monitoring script block logging helps SOC.

4. Malware Process Creation (4688)

Why it matters: Detects suspicious processes created outside normal workflows. Early detection of malware processes can prevent lateral movement.

Interview note: Highlight command-line analysis and process parent-child relationships.

5. Registry Persistence

Why it matters: Attackers modify registry keys to maintain persistence across reboots. Detecting these changes stops persistent malware.

Interview note: Show examples of Run keys, Services keys, and explain detection of unusual authors.

6. Data Exfiltration / Suspicious Network (5156)

Why it matters: Identifies data leaving the network to external or suspicious destinations. Critical for preventing intellectual property theft.

Interview note: Explain packet size thresholds, known C2 IPs, and correlation with unusual host activity.

7. Suspicious Network Connections

Why it matters: Detects abnormal outbound connections, lateral movement attempts, or C2 traffic.

Interview note: Mention MITRE T1071 and how SOC correlates network traffic with endpoint logs.

8. New User Creation (4720)

Why it matters: Unauthorized creation of accounts indicates attacker persistence or privilege escalation.

Interview note: Highlight monitoring of unusual creation times and unexpected admin accounts.

9. Event Log Clearing (1102)

Why it matters: Attackers clear logs to hide activity; this is a high indicator of compromise.

Interview note: Emphasize correlation with other alerts to detect stealthy intrusions.