# Windows Patching Overview

This section documents how Windows patching is handled across environments.

---

## Scope

This process applies to:

- On-premises VMware VMs
- Azure IaaS VMs
- Multiple Active Directory domains

---

## Current Patching Approach

Patching is performed using **Ivanti Security Controls** in an agentless configuration.

Key characteristics:
- Monthly patch cycles
- Pre-production testing window
- Change record required for production
- Reboots managed via maintenance windows

---

## High-Level Flow

1. Scan target systems
2. Review missing patches
3. Stage patches
4. Deploy during maintenance window
5. Validate and close change

---

## Exceptions

- Domain Controllers follow a separate schedule
- Legacy OS versions may require manual intervention