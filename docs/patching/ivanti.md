# Ivanti Security Controls

This page documents how Ivanti Security Controls is used for Windows patching.

---

## Deployment Model

- Agentless scanning
- Distribution servers per datacenter
- Multiple consoles aligned to AD domains

---

## Patch Cycle

| Phase | Description |
|------|------------|
| Scan | Identify missing patches |
| Review | Validate patch applicability |
| Deploy | Patch during approved window |
| Verify | Confirm installation success |

---

## Common Issues

### Machines showing as offline
- Verify WinRM access
- Confirm firewall rules
- Check DNS resolution

### Patch failures
- Review patch logs on target host
- Verify disk space
- Confirm OS support status

---

## Logging

Patch activity logs are stored: