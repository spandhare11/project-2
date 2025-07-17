# 🛡️ Project 2: Splunk + Sysmon Log Monitoring Lab

This lab demonstrates the setup of a centralized log monitoring environment using **Sysmon** and **Splunk**, focused on detecting suspicious activity like reverse shells and unauthorized login attempts. It simulates a basic Blue Team use case for threat detection and analysis.

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


Sysmon64.exe -accepteula -i sysmonconfig.xml


## ✅ Summary

This lab strengthens your **detection engineering** and **SOC analysis** skills by:

- 🖥️ Configuring **host-level logging** using Sysmon  
- 📡 Ingesting logs into **SIEM (Splunk)** for centralized analysis  
- 📜 Creating basic **detection logic** using Splunk SPL queries