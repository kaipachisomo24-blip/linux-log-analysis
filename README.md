Linux Log Analysis and Security Investigation

Project Overview

This project documents my practical journey learning Linux log analysis and security investigation using Parrot OS.

The objective is to understand how Linux records system activities, investigate service events, recognize unusual log messages, and develop foundational SOC analyst skills.

Environment

- Operating System: Parrot OS
- Platform: Linux
- Primary Tool: journalctl
- Focus: Blue Team / Security Operations

Investigation Objectives

1. Understand Linux logging mechanisms.
2. Explore system and service logs.
3. Investigate system warnings and errors.
4. Identify potentially suspicious events.
5. Document observations and investigation findings.

Tools and Commands

Command| Purpose
"journalctl"| View system journal logs
"journalctl -b"| View logs from the current boot
"journalctl -p warning"| Filter warning-level and higher priority messages
"systemctl"| Inspect system services
"who"| View logged-in users
"last"| Review login history

Investigation Areas

- System events
- Boot logs
- Service failures
- Authentication events
- Kernel messages
- Network-related system events

Findings

This section will contain documented observations, investigation steps, and conclusions as the project progresses.

Learning Outcomes

Through this project, I aim to improve my understanding of:

- Linux system administration
- Log analysis
- Security event investigation
- Troubleshooting
- SOC investigation workflows

Disclaimer

All investigations are conducted on my own system or in authorized learning environments.

This repository is part of my ongoing cybersecurity learning journey.
