
# MITRE ATT&CK – Security Detection Mapping

## Overview

This document maps simulated SOC investigation
scenarios to relevant MITRE ATT&CK techniques.

## 1. PowerShell Execution

**Technique ID:** T1059.001  
**Tactic:** Execution  
**Technique:** PowerShell

### Description
Attackers may abuse PowerShell to execute
commands and scripts on Windows systems.

### Detection Opportunities
- Monitor Sysmon Event ID 1.
- Review process command-line arguments.
- Investigate parent-child process relationships.
- Correlate endpoint activity.

### Related Project Scenario
Suspicious PowerShell Execution.

---

## 2. Brute Force

**Technique ID:** T1110  
**Tactic:** Credential Access  
**Technique:** Brute Force

### Description
Attackers may attempt multiple passwords
to gain unauthorized account access.

### Detection Opportunities
- Monitor Windows Event ID 4625.
- Identify repeated authentication failures.
- Analyze source IP addresses.
- Correlate failed and successful logons.

### Related Project Scenario
Multiple Failed Login Attempts.

---

## 3. Command and Scripting Interpreter

**Technique ID:** T1059  
**Tactic:** Execution  
**Technique:** Command and Scripting Interpreter

### Description
Attackers may use command interpreters
to execute commands and scripts.

### Detection Opportunities
- Monitor process creation events.
- Review command-line activity.
- Identify suspicious parent processes.
- Correlate execution patterns.

### Related Project Scenario
Endpoint Process Monitoring.

---

## Analyst Takeaways

MITRE ATT&CK mapping helps SOC analysts
understand adversary behavior, organize
detection coverage, and support incident
investigation and threat hunting.

## Project Status

Technique mapping based on simulated
investigation scenarios.

