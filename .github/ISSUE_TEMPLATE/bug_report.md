---
name: Bug report
about: Create a report to help us improve the script
title: '[BUG] '
labels: bug
assignees: ''

---

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior (e.g. command run, interactive selections made).

**Environment Info:**
 - Proxmox VE Version: (e.g. 9.2.3)
 - Container ID / Hostname: (e.g. 109 / frigate)
 - Storage Pool Type: (e.g. local, local-lvm, nfs)
 - Hardware Passthrough configured: (Intel iGPU / Nvidia / AMD / Coral USB / Coral PCIe)
 - Version of the script: (commit hash, or date downloaded)

**Script Log Output**
If applicable, paste any errors, warnings, or logs from the installer or updater:
```text
(Paste logs here)
```

**Container logs**
If the container booted but Frigate is failing, paste logs from `/dev/shm/logs/frigate/current` or `/dev/shm/logs/go2rtc/current`:
```text
(Paste logs here)
```

**Additional context**
Add any other context about the problem here.
