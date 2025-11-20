# Detection Rule Explanations (Phase 3)

## Brute Force (4625)
Multiple failed logons in a short time indicate a password-guessing attack.

## Successful Compromise (4624)
After brute force, attackers log in with Event ID 4624 and begin lateral movement.

## PowerShell Exploitation (4104)
Attackers commonly use encoded or remote PowerShell commands for post-exploitation.

## Malware Process Creation (Sysmon 1)
Malware frequently spawns from unexpected parents such as:
- winword.exe
- excel.exe
- wscript.exe
- mshta.exe

## Suspicious Network Connections (Sysmon 3)
Malware often contacts:
- IPs in foreign countries  
- Non-standard ports  
- Random subdomains  

## Registry Persistence (Sysmon 13 / Event 4698)
Attackers store persistence in:
- Run keys  
- Scheduled Tasks  
- Services  

## Exfiltration
Large outbound data transfers, especially to unknown IPs, indicate data theft.
