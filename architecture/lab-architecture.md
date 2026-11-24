
# SOC Lab Architecture

## 1. Overview

This document describes a simulated SOC architecture using Wazuh SIEM and Windows Sysmon for endpoint security monitoring and threat detection.

## 2. Architecture Components

| Component | Purpose |
|---|---|
| Windows Endpoint | Source of security events |
| Windows Sysmon | Endpoint activity monitoring |
| Wazuh Agent | Log collection and forwarding |
| Wazuh Manager | Security event analysis |
| Wazuh Dashboard | Alert monitoring and investigation |

## 3. Event Monitoring Workflow

1. Sysmon captures endpoint activities.
2. Windows events are collected by the Wazuh Agent.
3. The agent forwards relevant telemetry to Wazuh.
4. Wazuh analyzes events using configured rules.
5. Security alerts are reviewed through the dashboard.
6. SOC analysts investigate and document findings.

## 4. Monitoring Use Cases

- Suspicious PowerShell execution
- Multiple failed authentication attempts
- Process creation monitoring
- Suspicious network connections
- Endpoint security event analysis

## 5. Security Investigation

Alerts are assessed based on severity, event context, process information, user activity, and associated indicators.

## 6. Project Status



<img width="599" height="73" alt="image" src="https://github.com/user-attachments/assets/f85b9204-ee17-455d-a9f9-0e6f0a1e37fb" />

