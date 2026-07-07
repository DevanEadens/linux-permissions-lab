# Ubuntu Linux Log Analysis Lab

## Objective
Analyze Ubuntu 24.04 system logs to identify errors, authentication events, and service activity.

## Environment
- Ubuntu 24.04 LTS
- VirtualBox VM

## Tools Used
- journalctl
- grep
- last
- lastb

## Findings

### VM Graphics Errors
Finding:
vmwgfx configuration warnings

Analysis:
Determined to be related to virtual machine graphics configuration.

Severity:
Low

---

### SSSD Sudo Socket Failure

Finding:
sssd-sudo.socket dependency failure

Analysis:
Determined to be an unused enterprise authentication service on a personal Ubuntu system.

Severity:
Low

---

## Skills Demonstrated
- Linux log investigation
- Service troubleshooting
- Authentication log review
- Security event classification

