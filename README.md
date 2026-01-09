# Wazuh Homelab SIEM

A hands on security homelab built with **Wazuh** to monitor and analyze logs from multiple **Windows Endpoints** using a **linux** Wazuh server.

This project demonstrates practical **SIEM**, **endpoint monitoring**, and **blue-team security** concepts in a self hosted lab environment.

---

## Goals of the project

- Deploy a wazuh all in one SIEM on Linux.
- Monitor and collect logs from multiple windows machines.
- Analyze windoes event logs and security alerts.
- Gain hands on experience with SOC/ blue-team tooling.
- Build a portfolio ready security homelab.

## Lab architecture



## Technologies used

- Wazuh SIEM
- Kali Linux
- Windows
- VM
- Sysmon 

## Installation Overview 

1. Prepare Linux VM
2. Install Wazuh (All in one) 
3. Access Wazuh Dashboard
4. Install Wazuh agent on Windows Endpoints
5. Configure Windows Event Log collection
6. Validate logs and alerts

> Full step by step tutorial available in the '/docs' folder

## Repository structure
|-- README.md <br>
|-- docs/ <br>
|---|-- installation.md <br>
|---|-- linux-setup.md <br>
|---|-- windows-agent-setup.md <br>
|---|-- sysmon-setup.md <br>
|---|-- troubleshooting.md <br>
|-- configs/ <br>
|---|-- ossec.conf <br>
|---|-- sysmon-config.xml <br>
|-- screenshots/ <br>
|---|-- dashboard-overview.png <br>
|---|-- agent-status.png <br>
|---|-- alerts.png <br>
|-- attacks/ <br>
|---|-- brute-force-test.md
|---|-- powershell-test.md 

## Testing

This lab can be tested by
- Failed login attempts
- Unauthorized user creation
- PowerShell execution
- Sysmon process monitoring

Detected events are visible in the **Wazuh Dashboard** 

## Screenshots

Screenshots of the dashboard, agent status, and alerts are available in the '/screenshots' directory.

## Learning Outcomes
- Understanding SIEM architecture
- Log Collection and Normalization
- Windows security event analysis 
- Endpoint detection concepts
- Practical blue-team experience

## References 

- https://documentation.wazuh.com/
- https://github.com/wazuh/wazuh

## Disclaimer !!! 
 
 **This project is for educational and lab purpose only. Do not deploy this configuration directly into production environments.**

 ## Author 

 **Sithija Fernando**
