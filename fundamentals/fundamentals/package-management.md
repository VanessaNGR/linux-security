# Package Management in Linux (APT)

## What is APT
APT (Advanced Package Tool) is the package management system used in Debian-based Linux distributions.
It allows installing, updating, and removing software securely from trusted repositories.

---

## sudo apt update

### What it does
Updates the local list of available packages and versions from configured repositories.
It does NOT install or upgrade any software.

### Why sudo is required
Updating package information modifies system-level directories, which require administrative privileges.

### Security relevance
- Ensures the system is aware of the latest security patches
- Prevents installation of outdated or vulnerable software
- A critical step in system hardening

---

## Difference between update and upgrade

| Command | Description |
|------|------------|
| apt update | Updates package list |
| apt upgrade | Installs available updates |
| apt full-upgrade | Upgrades packages and handles dependencies |

---

## Blue Team Perspective
- Keeping package lists updated is essential for patch management
- Unpatched systems are a common attack vector

## Pentesting Perspective
- Outdated packages may indicate exploitable vulnerabilities
- Systems that skip updates are high-risk targets
