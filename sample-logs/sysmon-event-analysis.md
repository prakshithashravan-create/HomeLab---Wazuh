
# Windows Sysmon – Event ID 1 Analysis

## Event Overview
Sysmon Event ID 1 records process creation activity on Windows endpoints.

## Event Details

| Field | Description |
|---|---|
| Event ID | 1 |
| Event Type | Process Creation |
| Process | powershell.exe |
| Parent Process | explorer.exe |
| User | analyst |
| Integrity Level | High |

## Investigation Approach

1. Identify the executable and process path.
2. Review the command-line arguments.
3. Identify the parent process.
4. Validate the executing user.
5. Correlate the event with other endpoint activity.

## Security Considerations

PowerShell is a legitimate administrative tool but can also be abused by attackers.

An execution policy bypass argument warrants investigation, but does not independently prove malicious activity.

## MITRE ATT&CK Mapping

T1059.001 – PowerShell

## Analyst Assessment

Illustrative event requiring contextual investigation and correlation with additional telemetry.

## Recommended Actions

- Validate whether execution was authorized.
- Review related process activity.
- Check for suspicious child processes.
- Escalate if malicious indicators are identified.

