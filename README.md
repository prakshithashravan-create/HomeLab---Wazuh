
# Home SOC Lab – Wazuh SIEM & Windows Sysmon

## Project Overview

A cybersecurity learning portfolio focused on Security Operations, Endpoint Monitoring, Threat Detection, and Incident Investigation using Wazuh SIEM and Windows Sysmon.

The project documents simulated SOC scenarios, Windows security event analysis, detection rule examples, MITRE ATT&CK mapping, and incident response workflows.

**Project Type:** Simulated SOC Lab Portfolio  
**Deployment Status:** Documentation and sample scenarios prepared; live lab deployment pending.

## Objectives

- Understand SIEM monitoring and alert investigation.
- Analyze Windows endpoint telemetry using Sysmon.
- Explore security detection rule development.
- Investigate suspicious authentication and process activity.
- Map security events to MITRE ATT&CK.
- Document incident response and remediation workflows.

## Tools & Technologies

| Technology | Purpose |
|---|---|
| Wazuh SIEM | Security monitoring concepts |
| Windows Sysmon | Endpoint telemetry |
| MITRE ATT&CK | Threat technique mapping |
| Windows Event Logs | Security event analysis |
| XML | Detection rule examples |
| Python | Security automation concepts |

## Project Architecture

Windows Endpoint → Sysmon → Wazuh Agent → Wazuh Manager → Wazuh Dashboard → Alert Investigation

## Project Modules

| Module | Documentation |
|---|---|
| SOC Architecture | [View Architecture](architecture/lab-architecture.md) |
| Sysmon Event Analysis | [View Analysis](sample-logs/sysmon-event-analysis.md) |
| Authentication Monitoring | [View Investigation](investigation-reports/multiple-failed-logins.md) |
| Detection Engineering | [View Detection Rules](detection-rules/README.md) |
| PowerShell Investigation | [View Case Study](investigation-reports/suspicious-powershell.md) |
| MITRE ATT&CK | [View Mapping](mitre-mapping/attack-techniques.md) |
| Incident Response | [View Report](incident-response/powershell-incident-report.md) |
| Vulnerability Management | [View Assessment](vulnerability-management/vulnerability-assessment.md) |
| Security Skills | [View Learning Outcomes](security-skills/learning-outcomes.md) |

## Key Cybersecurity Domains

- Security Operations
- Endpoint Security Monitoring
- Threat Detection & Investigation
- Incident Management
- Vulnerability Management
- Security Risk Assessment
- Governance & Compliance

## Project Limitations

- No live Wazuh environment has been deployed.
- Sample logs are illustrative.
- Detection rules have not been validated.
- Screenshots, where included, are illustrative.

## Disclaimer

This repository is intended for educational and portfolio purposes. All scenarios and sample events are illustrative and do not represent validated live security detections.
