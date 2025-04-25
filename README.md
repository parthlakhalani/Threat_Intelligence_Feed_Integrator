# 🔐 ThreatIntel Hub: Threat Intelligence Feed Integrator

## 📌 Project Description

**ThreatIntel Hub** is an open-source project designed to **aggregate, normalize, tag, and visualize cyber threat intelligence (CTI)** from multiple public sources like VirusTotal, AbuseIPDB, MISP, and AlienVault OTX into a central dashboard. This tool is designed for easy integration into SOC workflows, providing enhanced visibility into emerging threats and Indicators of Compromise (IOCs).

The goal is to simplify and automate the process of collecting threat data, organizing it intelligently, and helping security analysts make faster, smarter decisions.

---

## 🚀 Key Features

- 📥 **Multi-Source Threat Feed Ingestion** (VirusTotal, AbuseIPDB, MISP, OTX)
- 🧠 **IOC Normalization and Auto-Tagging** (e.g., Malware, Phishing, C2 Servers)
- 📊 **Interactive Dashboard** with IOC visualizations and search capabilities
- 🗂️ **MongoDB Backend** to store and query threat indicators
- 🔄 **Scheduled Automation** to fetch and update feeds regularly
- 📤 **SIEM-Friendly Export Options** (JSON or STIX format)

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask / FastAPI
- **Frontend:** HTML, JavaScript, Chart.js / Plotly
- **Database:** MongoDB
- **Automation:** APScheduler / Celery
- **Threat Feeds:** VirusTotal API, AbuseIPDB, MISP, AlienVault OTX
- **Optional:** Docker, STIX/TAXII support

---

## 📁 Project Structure (Coming Soon)
