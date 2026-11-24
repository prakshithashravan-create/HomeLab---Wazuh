
# SOC Incident Response Report
## Suspicious PowerShell Execution

### 1. Incident Overview

| Attribute | Details |
|---|---|
| Incident ID | SOC-IR-001 |
| Incident Type | Suspicious Process Execution |
| Affected Asset | WIN-ENDPOINT-01 |
| Log Source | Windows Sysmon |
| Event ID | 1 |
| Severity | Medium (illustrative) |
| Status | Simulated Investigation |

### 2. Incident Identification

A PowerShell process execution event was
identified during endpoint monitoring.

The execution included an unusual execution
policy bypass argument, requiring further
investigation.

### 3. Initial Triage

The following attributes were reviewed:

- Executable path
- Command-line arguments
- Parent process
- Executing user
- Process ID
- Event timestamp

### 4. Investigation Activities

1. Reviewed the PowerShell execution event.
2. Examined parent-child process relationships.
3. Validated the executing user account.
4. Assessed command-line arguments.
5. Identified additional telemetry required
   for further investigation.

### 5. Risk Assessment

Potential risk includes unauthorized command
execution and possible abuse of administrative
scripting capabilities.

The observed command-line argument alone
does not establish malicious activity.

### 6. MITRE ATT&CK Mapping

Technique: T1059.001  
Name: PowerShell  
Tactic: Execution

### 7. Recommended Containment

- Validate execution with the system owner.
- Isolate the endpoint if compromise is confirmed.
- Preserve relevant endpoint evidence.
- Escalate confirmed malicious activity.

### 8. Remediation

- Remove unauthorized scripts or persistence
  mechanisms if identified.
- Review endpoint security controls.
- Reset credentials if compromise warrants it.
- Apply required security updates.

### 9. Closure Criteria

- Activity validated and classified.
- Required remediation completed.
- Relevant evidence documented.
- Incident owner confirms closure.

### 10. Lessons Learned

- Strengthen endpoint process monitoring.
- Improve detection coverage.
- Correlate process execution with
  authentication and network events.

### Disclaimer

This is a simulated incident response case study.
No live security incident was investigated.

