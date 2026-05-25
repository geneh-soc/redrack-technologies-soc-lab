# redrack-win10-01

## Purpose

Windows 10 enterprise endpoint used for endpoint monitoring, telemetry collection, detection validation, and SOC operations testing within the RedRack Technologies SOC Lab environment.

This system simulates a managed enterprise workstation connected to the Active Directory domain.

---

## Operating System

- Windows 10 Pro

---

## Current Status

In Progress

---

## Planned Services and Tooling

- Active Directory domain join
- Sysmon
- Splunk Universal Forwarder
- PowerShell logging
- Endpoint telemetry collection
- Security event forwarding
- Browser testing tools

---

## Planned Validation

### Domain Join
- Active Directory authentication
- Domain connectivity testing
- DNS validation

### Sysmon
- Event generation
- Process creation monitoring
- PowerShell monitoring
- Network connection logging

### Splunk Forwarder
- Forwarding validation
- Log ingestion testing
- SIEM connectivity

### PowerShell Logging
- Module logging
- Script block logging
- Transcript logging

---

## Validation Commands

```powershell
hostname
whoami
ipconfig /all
gpresult /r
Get-WinEvent
Get-Service
```

---

## Planned Screenshots

- Successful domain join
- Sysmon service running
- PowerShell logging configuration
- Splunk Forwarder service
- Windows Event Viewer logs
- Endpoint telemetry validation

---

## Detection Testing

Planned detection scenarios include:

- Failed login attempts
- Suspicious PowerShell execution
- Process creation events
- Network connection events
- Administrative activity monitoring

---

## Lessons Learned

This section will document:
- domain join troubleshooting,
- DNS issues,
- logging validation,
- Sysmon configuration tuning,
- and endpoint monitoring challenges encountered during deployment.
