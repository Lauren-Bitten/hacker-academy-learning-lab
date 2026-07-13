# Project Structure

This repository is organized by learning topic, hands-on labs, reports, templates, and defensive security notes.

## Main Files

- `README.md` — Project overview
- `ETHICS-AND-SCOPE.md` — Authorization and ethical testing rules
- `LEARNING-PATH.md` — Planned order of study
- `PROGRESS-TRACKER.md` — Module completion tracker
- `.gitignore` — Files and folders excluded from GitHub

## Learning Modules

```text
01-foundations/
02-osint/
03-networking-and-enumeration/
04-web-security/
05-exploitation/
06-digital-forensics/
07-ai-security/
08-special-topics/
09-detection-and-defense/

```

Each module folder contains a `README.md` for:

- Objectives
- Topics studied
- Original notes
- Tools and commands practiced
- Authorized exercises
- SOC connections
- Lessons learned

## Labs

```text
labs/
├── lab-template.md
└── completed-labs/
```

Each completed lab should have its own folder.

Example:

```text
labs/
└── completed-labs/
    └── lab-01-nmap-host-discovery/
        ├── README.md
        └── screenshots/
```

## Reports

```text
reports/
├── vulnerability-report-template.md
└── penetration-test-report-template.md
```

These templates are used to practice professional security documentation.

## Templates

```text
templates/
└── lesson-notes-template.md
```

Templates provide a consistent format for lessons and exercises.

## Screenshots

```text
screenshots/
└── README.md
```

Screenshots must be sanitized before being uploaded.

## File Naming Rules

Use lowercase names with hyphens.

Good examples:

```text
nmap-host-discovery
linux-file-permissions
burp-request-analysis
privilege-escalation-basics
```

Avoid:

```text
New Folder
final-stuff
test123
random-notes
```

## Documentation Workflow

1. Complete a lesson or authorized lab.
2. Write notes in my own words.
3. Add commands and sanitized evidence.
4. Document problems and troubleshooting.
5. Add SOC and detection observations.
6. Review for sensitive information.
7. Commit the changes.
8. Update the progress tracker.
