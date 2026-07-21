# Hello, I'm Michael G. (Work in progress)

<a href="https://linkedin.com">
  <img src="https://img.shields.io/badge/-LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

I am a recent graduate with a strong interest in technology and a passion for solving complex problems. My journey has led me to cybersecurity, and I am currently focused on transitioning into a **Security Operations Center (SOC)** role as a **Tier 1 Analyst**.

---

## Objective

To leverage my hands-on SIEM experience, log analysis skills, and problem-solving abilities to contribute as a SOC Analyst while continuing to grow in the cybersecurity field.

---

## Skills

| Skill | Associated Project |
|-------|--------------------|
| SIEM Deployment and File Integrity Monitoring | [Wazuh SIEM Deployment & FIM Lab](#) |
| Log Forwarding, SIEM Administration, and Network Troubleshooting | [Splunk Universal Forwarder & BOTS v3 Lab](#) |
| SOC Investigation with Historical Attack Datasets | [Splunk Universal Forwarder & BOTS v3 Lab](#) |
| SPL Search Development and Security Dashboarding | [AI-Assisted SOC Monitoring Lab (Splunk + Claude MCP)](#) |
| AI-Assisted Log Investigation (MCP Integration) | [AI-Assisted SOC Monitoring Lab (Splunk + Claude MCP)](#) |

---

## Tools

**SIEM**  
![Splunk](https://img.shields.io/badge/-Splunk-000000?style=for-the-badge&logo=Splunk&logoColor=white)
![Wazuh](https://img.shields.io/badge/-Wazuh-1A7CB8?style=for-the-badge&logo=Wazuh&logoColor=white)

**Virtualization & OS**  
![VirtualBox](https://img.shields.io/badge/-VirtualBox-183A61?style=for-the-badge&logo=VirtualBox&logoColor=white)
![Ubuntu](https://img.shields.io/badge/-Ubuntu-E95420?style=for-the-badge&logo=Ubuntu&logoColor=white)
![Windows](https://img.shields.io/badge/-Windows-0078D6?style=for-the-badge&logo=Windows&logoColor=white)

**AI / Automation**  
![Claude](https://img.shields.io/badge/-Claude-D97757?style=for-the-badge&logo=Claude&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)

**Vulnerability Assessment**  
![Nessus](https://img.shields.io/badge/-Nessus-00C176?style=for-the-badge&logo=Nessus&logoColor=white)

---

## Certifications

![Security+](https://img.shields.io/badge/-Security%2B-FF0000?style=for-the-badge&logo=CompTIA&logoColor=white)

---

## Projects

### 1. Wazuh SIEM Deployment & File Integrity Monitoring
- Deployed a Wazuh SIEM (manager, indexer, dashboard) on Ubuntu and enrolled a Windows 11 endpoint as a monitored agent in an isolated VirtualBox lab network  
- Configured real-time File Integrity Monitoring (FIM) on a target directory and validated alerting on file create/modify/delete events  
- Troubleshot a failed install by switching to the all-in-one install flow, and rotated default admin credentials using Wazuh's password tooling  

**[View Project Folder](#)**

---

### 2. Splunk Universal Forwarder & BOTS v3 SOC Investigation Lab
- Configured a Windows VM with Splunk Universal Forwarder to send logs to a separate Splunk Enterprise receiver over TCP 9997  
- Diagnosed Windows Firewall and forwarder-configuration issues, including a stale forward-server entry and ping-vs-port-connectivity troubleshooting  
- Installed and investigated the BOTS v3 (Boss of the SOC) dataset, building discovery searches across sourcetypes, hosts, and suspicious activity (failed logons, PowerShell execution, downloads)  

**[View Project Folder](#)**

---

### 3. [Splunk SIEM & Claude MCP Lab](https://github.com/mgcybersec/AI-Assisted-SIEM-Monitoring-Lab-Splunk-Enterprise-Windows-Logs-and-Claude)
- Built Windows security-monitoring dashboards in Splunk Enterprise using live Windows Event Logs, with SPL searches for failed/successful logons, privileged activity, and account changes  
- Installed the Splunk MCP Server and integrated it with Claude Desktop for natural-language SPL search execution and log investigation  
- Diagnosed and resolved a Windows command-spawn/path-quoting bug, a TLS certificate issue, and an authorization-header bug (HTTP 405) blocking the MCP connection  

**[View Project Folder](#) | [Screenshots](#)**

---

### 4. SOC Automation Lab (Planned)
- Will include Shuffle SOAR, TheHive, etc.
