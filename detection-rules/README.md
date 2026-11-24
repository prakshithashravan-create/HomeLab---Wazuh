
# Wazuh Custom Detection Rules

## Rule 1 – PowerShell Process Execution

### Objective
Identify PowerShell process execution using
Windows Sysmon telemetry.

### Detection Source
- Windows Sysmon
- Event ID 1 – Process Creation

### Rule Configuration
- Rule ID: 100100
- Severity: 7
- Detection Category: Process Monitoring

### MITRE ATT&CK
T1059.001 – PowerShell

### Detection Logic
The sample rule identifies process creation
events associated with powershell.exe.

### Investigation Considerations
- Review command-line arguments.
- Identify parent process.
- Validate executing user.
- Correlate related endpoint events.
- Check for suspicious follow-on activity.

### False Positive Considerations
Legitimate administrative scripts and
automation tools may trigger this detection.

### Status
Illustrative custom detection rule.
Live deployment and validation pending.

