# IP Address Plan

## Overview

This document tracks the planned network layout and IP addressing structure for the RedRack Technologies SOC Lab environment.

The goal is to simulate a segmented enterprise network supporting infrastructure systems, monitored endpoints, security tooling, automation services, and future containerized workloads.

---

## Planned Network Segments

| VLAN | Network | Purpose |
|---|---|---|
| VLAN 10 | 10.10.10.0/24 | Core Infrastructure |
| VLAN 20 | 10.10.20.0/24 | Workstations / Endpoints |
| VLAN 30 | 10.10.30.0/24 | Security Monitoring |
| VLAN 40 | 10.10.40.0/24 | Management / Administration |
| VLAN 50 | 10.10.50.0/24 | Future Container / Kubernetes |

---

## Current Systems

| Hostname | Operating System | Planned IP | Role |
|---|---|---|---|
| redrack-dc01 | Windows Server 2022 | 10.10.10.10 | Active Directory / DNS / DHCP |
| redrack-win10-01 | Windows 10 Pro | 10.10.20.10 | Enterprise Endpoint |
| redrack-util01 | Ubuntu 24.04 | 10.10.40.10 | Automation / Utility Server |
| redrack-wazuh01 | Ubuntu Server | 10.10.30.10 | SIEM Platform |

---

## Planned Services

- Active Directory
- DNS
- DHCP
- Sysmon
- Wazuh
- Splunk
- Python automation
- Ansible
- Monitoring dashboards
- Threat hunting workflows

---

## Future Enhancements

- VLAN segmentation
- Firewall rules
- Docker networking
- Kubernetes networking
- VPN access
- IDS/IPS integrations
- Monitoring dashboards

---

## Status

In Progress
