# The Hacker's Handbook

## Status

In Progress

## Objective

Learn the core concepts, terminology, tools, and phases used in ethical hacking while connecting each phase to defensive security and SOC analysis.

## Study Plan

This module is based on the Hacker's Handbook PDF.

I will complete it in sections instead of trying to finish all 79 pages at once.

### Reading Sections

## Reading Sections

- [x] Introduction and handbook overview — pages 1–2
- [x] How to use the handbook — pages 3–5
- [x] Lab setup and authorization — page 6
- [x] Reconnaissance — pages 7–10
- [ ] Scanning
- [ ] Vulnerability assessment
- [ ] Exploitation
- [ ] Post-exploitation
- [ ] Privilege escalation
- [ ] Lateral movement
- [ ] Reporting and documentation
- [ ] Final review

## Topics to Study

- Ethical hacking fundamentals
- Rules of engagement
- Lab setup and isolation
- Reconnaissance
- Scanning and enumeration
- Vulnerability assessment
- Exploitation
- Post-exploitation
- Privilege escalation
- Lateral movement
- Reporting and remediation

## Introduction Notes

- Penetration testing follows a methodical workflow where each phase builds on the previous phase.
- Commands alone are not enough; I also need to understand the purpose of each command and how to interpret its results.
- The handbook should be used in multiple ways: first for an overview, then for focused study, hands-on practice, and later as a reference.
- A safe lab should use virtual machines, intentionally vulnerable targets, an isolated network, and VM snapshots.
- Testing must only be performed against systems I own or have explicit permission to test.
- Reconnaissance is the information-gathering phase that helps identify the target’s attack surface before active scanning begins.
- Reconnaissance findings should be documented instead of relying on memory.
- Multiple tools should be used because one tool may miss subdomains, records, or other useful information.

## Tools Mentioned

## Tools Mentioned

### Lab Environment

- VirtualBox
- Kali Linux
- Metasploitable 2
- DVWA
- OWASP Juice Shop

### Reconnaissance Tools

- WHOIS
- Dig
- theHarvester
- Amass
- Google search operators
- Web browser developer tools
- Page source
- robots.txt
  
## Commands Introduced

These commands were introduced in the handbook but have not all been practiced yet.

```bash
whois example.com
dig +short example.com any
theHarvester -d example.com -b all
amass enum -d example.com
```
  
## Notes

Add original notes here while reading each section.

## Commands Practiced

```bash
# Add commands practiced during authorized labs
```

## Hands-On Practice

Document authorized exercises completed while working through the handbook.

## SOC Connection

Explain how the techniques covered in the handbook may appear in:

- Endpoint logs
- Network traffic
- Authentication logs
- EDR alerts
- SIEM detections

## Lessons Learned

Add a short summary after completing each section.

## Next Steps

## Next Steps

## Next Steps

- [ ] Add original reconnaissance notes
- [ ] Record the tools and commands introduced
- [ ] Complete one authorized reconnaissance exercise
- [ ] Add SOC and detection observations
- [ ] Begin the scanning section
