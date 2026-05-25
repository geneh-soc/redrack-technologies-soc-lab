# redrack-dc01

## Purpose

Windows Server 2022 domain controller providing core enterprise infrastructure services for the RedRack Technologies SOC Lab environment.

Primary functions include:

- Active Directory Domain Services (AD DS)
- DNS
- DHCP
- Group Policy
- Authentication services
- Centralized domain management

---

## Operating System

- Windows Server 2022

---

## Current Status

In Progress

---

## Planned Services

- Active Directory
- DNS
- DHCP
- Group Policy Objects (GPO)
- PowerShell logging
- Wazuh Agent
- Security event forwarding

---

## Planned Validation

### Active Directory
- Domain controller promotion
- User and group creation
- OU structure
- Authentication validation

### DNS
- Forward lookup zones
- Reverse lookup zones
- Name resolution testing

### DHCP
- Scope creation
- IP assignment validation
- Reservation testing

### Group Policy
- PowerShell logging
- Security settings
- Audit policies

---

## Validation Commands

```powershell
Get-Service
ipconfig /all
nslookup redracktech.local
Get-ADUser
dcdiag
```

---

## Planned Screenshots

- Active Directory Users and Computers
- DNS Manager
- DHCP Manager
- Group Policy Management
- Successful domain joins
- Validation command outputs

---

## Lessons Learned

This section will document:
- configuration issues,
- DNS troubleshooting,
- domain join problems,
- service validation,
- and operational fixes encountered during deployment.
