# 🛡️ Project 2: Splunk + Sysmon Log Monitoring Lab

This lab demonstrates the setup of a centralized log monitoring environment using **Sysmon** and **Splunk**, with a focus on detecting suspicious activity like reverse shells and unauthorized login attempts. It simulates a basic blue team use case in a Windows environment.

---

## 🔧 Tools Used

- 🖥️ **Windows 10 VM** – As a victim machine  
- 📜 **Sysmon** – For advanced Windows event logging  
- 📈 **Splunk** – For centralized log collection and analysis  
- 🐚 **Netcat / Reverse Shell Simulation** – To generate test alerts  
- 🔍 **MITRE ATT&CK Mapping** – For detection alignment (optional)

---

## ⚙️ Lab Setup

### 1. Install Sysmon with Configuration

```bash
Sysmon64.exe -accepteula -i sysmonconfig.xml

sysmonconfig.xml enables detailed logging (process creation, network events, etc.)

You can export current config:

Sysmon64.exe -c > current-config.xml '''

✅ Summary
This lab strengthens your detection engineering and SOC analysis skills by:

Configuring host-level logging (Sysmon)

Ingesting logs into SIEM (Splunk)

Creating basic detection logic

Mapping behaviors to real-world attack techniques