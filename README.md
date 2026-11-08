# 🛡️ SIEM Detection Engineering & SOC Dashboards

Custom Splunk (SPL) detection queries, scheduled alert configurations, and security monitoring dashboards mapped to the MITRE ATT&CK framework.

## 📂 Lab Directory

| Lab Folder | MITRE ATT&CK ID | Focus Area | Telemetry Source |
| :--- | :--- | :--- | :--- |
| **[01 - Rogue Account Creation Alert](./01-Rogue-Account-Creation-Alert)** | `T1136.001` (Persistence) | Scheduled alert configuration & triage workflow | `WinEventLog:Security` (`EventCode=4720`) |
| **[02 - Windows Activity & Firewall Dashboard](./02-Windows-Activity-Firewall-Dashboard)** | `T1562.004` (Defense Evasion) | Multi-panel authentication & firewall monitoring | `WinEventLog:Security` (`EventCode=4624`, `4625`, `4946`) |
