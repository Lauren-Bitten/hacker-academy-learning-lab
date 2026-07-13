# Penetration Test Report

## Report Information

- Date:
- Report author:
- Lab or platform:
- Testing period:
- Authorization status:

## Executive Summary

Provide a high-level overview of the assessment, major findings, overall risk, and recommended actions.

## Scope

List the systems, applications, networks, or lab targets included in the assessment.

### In Scope

- Authorized target:
- Authorized services:
- Authorized testing methods:

### Out of Scope

- Production systems
- Third-party systems
- Denial-of-service testing
- Social engineering
- Any target without explicit authorization

## Rules of Engagement

Document:

- Approved testing window
- Authorized tools
- Testing limitations
- Data handling requirements
- Stop conditions
- Reporting requirements

## Methodology

### 1. Planning and Scoping

Describe how the scope and objectives were defined.

### 2. Reconnaissance

Describe authorized information-gathering activities.

### 3. Scanning and Enumeration

Describe host discovery, port scanning, service detection, and enumeration.

### 4. Vulnerability Analysis

Describe how potential vulnerabilities were identified and reviewed.

### 5. Exploitation

Describe authorized exploitation attempts and their results.

### 6. Post-Exploitation

Describe any authorized privilege escalation, access validation, or impact testing.

### 7. Cleanup

Document how files, accounts, sessions, and configuration changes were removed or restored.

## Findings Summary

| ID | Finding | Severity | Status |
|---|---|---|---|
| F-001 |  |  | Open |

## Detailed Findings

### F-001: Finding Title

#### Severity

- [ ] Informational
- [ ] Low
- [ ] Medium
- [ ] High
- [ ] Critical

#### Description

Explain the finding in my own words.

#### Evidence

Add sanitized screenshots, logs, or command output.

#### Reproduction Steps

```bash
# Add authorized commands here
```

#### Impact

Explain the possible security impact.

#### Remediation

Explain how the issue should be corrected or reduced.

#### Validation

Describe how the remediation can be tested safely.

## SOC and Detection Perspective

Document:

- Relevant log sources
- Process activity
- Network connections
- Authentication events
- Endpoint telemetry
- Possible EDR alerts
- Possible SIEM detections
- Recommended investigation steps

## MITRE ATT&CK Mapping

| Tactic | Technique | Technique ID |
|---|---|---|
|  |  |  |

## Recommendations

List prioritized recommendations based on the findings.

1. Address critical and high-severity findings.
2. Review exposed services and permissions.
3. Improve logging and monitoring.
4. Validate remediation through authorized retesting.

## Conclusion

Summarize the overall security posture, key risks, and next steps.

## References

Add public documentation and security references here.
