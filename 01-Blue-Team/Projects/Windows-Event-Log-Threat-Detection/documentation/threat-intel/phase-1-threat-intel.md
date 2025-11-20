# Phase 1 — Threat Intelligence Baseline  
**Windows Event Log Threat Detection Project**

---

## 🎯 Objective
Establish baseline knowledge of common attacker behaviors visible in Windows logs before starting detailed detection.

---

## 🔍 Key Threat Behaviors Mapped (MITRE ATT&CK)

### 1. Brute Force — (T1110)
Evidence:
- Multiple failed logons (Event 4625)
- Followed by a single success (4624)

### 2. PowerShell Abuse — (T1059.001)
Evidence:
- Suspicious command execution
- Encoded commands (-enc)
- Event ID 4104

### 3. Persistence Mechanisms — Scheduled Tasks (T1053.005)
Evidence:
- Event ID 4698 (new task created)

### 4. User Account Creation — Privilege Escalation (T1136)
Evidence:
- Event ID 4720

### 5. Defense Evasion — Clearing Logs (T1070)
Evidence:
- Event ID 1102 (Security log cleared)

---

## 📌 Why These Threats Matter
These behaviors represent the most common attacker steps:
1. **Initial Access** (brute force)  
2. **Execution** (PowerShell)  
3. **Persistence** (scheduled task)  
4. **Privilege Escalation** (new user)  
5. **Defense Evasion** (wipe logs)

Your entire project is built around detecting these behaviors.

---

## 📖 Use of Threat Intel in Later Phases
- Phase 3 detection rules will map logs → MITRE techniques  
- Phase 4 investigation notes will reference these attacker paths  
- Phase 5 dashboards will show visualized threat activity  
