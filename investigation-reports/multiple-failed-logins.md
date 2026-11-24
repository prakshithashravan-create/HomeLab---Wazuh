
# SOC Investigation – Multiple Failed Login Attempts

## 1. Incident Overview

**Incident Type:** Authentication Failure  
**Log Source:** Windows Security Event Logs  
**Event ID:** 4625  
**Severity:** Medium (illustrative)  
**MITRE ATT&CK:** T1110 – Brute Force

## 2. Alert Description

Multiple failed authentication attempts were observed
against an administrator account on a Windows endpoint.

## 3. Investigation Steps

1. Identify the targeted user account.
2. Review the number and frequency of failed attempts.
3. Analyze source IP addresses.
4. Examine logon types and failure status codes.
5. Correlate failed attempts with successful logons.
6. Identify potentially suspicious authentication patterns.

## 4. Key Findings

- Target Account: administrator
- Event ID: 4625
- Logon Type: 3 (Network)
- Failure Status: 0xC000006D
- SubStatus: 0xC000006A
- Source IP: 192.0.2.25 (documentation example)

## 5. Threat Assessment

Repeated authentication failures may indicate
password guessing or brute-force activity.

However, failed logons can also result from
incorrect credentials or misconfigured services.

## 6. MITRE ATT&CK Mapping

T1110 – Brute Force

## 7. Recommended Response

- Validate the source of authentication attempts.
- Review related successful login events.
- Check for account lockout activity.
- Escalate suspicious activity.
- Apply appropriate account security controls.

## 8. Conclusion

Authentication event monitoring and correlation
help identify potentially suspicious login activity.

**Status:** Simulated investigation documentation.

