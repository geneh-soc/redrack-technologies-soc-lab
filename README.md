# RedRack Technologies SOC Lab

## Overview

The RedRack Technologies SOC Lab is a multi-system enterprise cybersecurity environment designed to simulate real-world infrastructure administration, security monitoring, SIEM operations, automation workflows, threat hunting, and incident response processes.

The lab combines Windows Server infrastructure, Windows endpoints, Linux administration, centralized logging, Python automation, and future containerized workloads to demonstrate practical blue-team engineering skills across enterprise technologies.

This repository documents the complete build process, validation procedures, troubleshooting steps, security detections, operational workflows, and automation projects developed throughout the lab lifecycle.

---

## Current Infrastructure

| VM Name | Purpose | Status |
|---|---|---|
| redrack-dc01 | Active Directory / DNS / DHCP / GPO | In Progress |
| redrack-win10-01 | Windows Endpoint Monitoring | In Progress |
| redrack-util01 | Ubuntu Automation Server | Active |
| redrack-wazuh01 | Wazuh SIEM Platform | Planned |

## Core Technologies

### Infrastructure
- Proxmox VE
- Windows Server 2022
- Windows 10 Pro
- Ubuntu 24.04

### Security Monitoring
- Wazuh
- Splunk
- Sysmon
- PowerShell Logging

### Automation
- Python
- Bash
- Ansible
- APIs

### Monitoring & Operations
- Grafana
- Uptime Kuma
- Git
- SSH

### Networking
- VLANs
- DNS
- DHCP
- Firewall Management
