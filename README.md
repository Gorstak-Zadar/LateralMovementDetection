# 🔄 LateralMovementDetection

> **Lateral Movement Detection** - Identifies techniques used to move between systems in a network.

---

## 📋 Overview

LateralMovementDetection monitors for lateral movement techniques including PsExec, WMI remote execution, SMB abuse, and other methods attackers use to spread across networks.

---

## 🎯 What It Detects

- 🔄 **PsExec Usage** - Sysinternals abuse
- 💻 **WMI Remote** - WMI-based execution
- 📂 **SMB Access** - Admin share abuse
- 🌐 **WinRM Sessions** - Remote management abuse
- 🔗 **RDP Connections** - Remote desktop lateral movement

---

## 🚀 Usage

```powershell
# Detect lateral movement
.\LateralMovementDetection.ps1
```

---

## 📜 License & Disclaimer

This software is for **AUTHORIZED NETWORK MONITORING** only.
---

## Comprehensive legal disclaimer

This project is intended for authorized defensive, administrative, research, or educational use only.

- Use only on systems, networks, and environments where you have explicit permission.
- Misuse may violate law, contracts, policy, or acceptable-use terms.
- Running security, hardening, monitoring, or response tooling can impact stability and may disrupt legitimate software.
- Validate all changes in a test environment before production use.
- This project is provided "AS IS", without warranties of any kind, including merchantability, fitness for a particular purpose, and non-infringement.
- Authors and contributors are not liable for direct or indirect damages, data loss, downtime, business interruption, legal exposure, or compliance impact.
- You are solely responsible for lawful operation, configuration choices, and compliance obligations in your jurisdiction.

---

<p align="center">
  <sub>Built with care by <strong>Gorstak</strong></sub>
</p>