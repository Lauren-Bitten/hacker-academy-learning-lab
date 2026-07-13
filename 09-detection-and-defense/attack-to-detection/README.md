# Attack-to-Detection

## Status

Not Started

## Objective

Connect offensive security techniques to the logs, alerts, network activity, and endpoint behavior a SOC analyst would investigate.

## Topics to Study

- Attacker objectives
- Process relationships
- Command-line activity
- Network connections
- Authentication events
- File and registry changes
- Endpoint telemetry
- SIEM detections
- MITRE ATT&CK mapping
- False positives
- Investigation and response

## Detection Format

For each technique, document:

- What the attacker is trying to accomplish
- What tool or command was used
- What process activity may appear
- What network activity may appear
- Which logs may contain evidence
- What an EDR may detect
- What a SIEM alert may look like
- Which MITRE ATT&CK technique applies
- Recommended investigation steps
- Possible remediation

## Techniques Reviewed

| Technique | MITRE ATT&CK ID | Status | Detection Notes Added |
|---|---|---|---|
| Network Scanning |  | Not Started | No |
| Service Enumeration |  | Not Started | No |
| Reverse Shell |  | Not Started | No |
| Privilege Escalation |  | Not Started | No |
| Web Exploitation |  | Not Started | No |

## Sample Investigation Questions

- Which user performed the activity?
- Which host was involved?
- What process started the activity?
- What child processes were created?
- Which destination IPs and ports were contacted?
- Was the behavior expected?
- Did the activity continue after the initial alert?
- Were credentials or elevated privileges involved?

## Lessons Learned

Add a short summary after reviewing each technique.

## Next Steps

- [ ] Choose the first offensive technique
- [ ] Document the attacker behavior
- [ ] Identify relevant logs
- [ ] Add MITRE ATT&CK mapping
- [ ] Write investigation steps
- [ ] Update the progress tracker
