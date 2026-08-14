# Day 7 – Splunk Basics
## 🎯 Objective

Today I completed the **Splunk Basics** room in the TryHackMe SOC Level 1 path. The objective was to understand what Splunk is, its main components, how to navigate the Splunk interface, and how data is added for security monitoring and analysis.

---

# 🔍 What is Splunk?

**Splunk** is a Security Information and Event Management (SIEM) platform that collects, indexes, searches, and analyzes machine-generated data from different sources. It enables SOC analysts to monitor security events, investigate incidents, and detect suspicious activities from a centralized platform.

Instead of checking logs on individual devices, analysts can use Splunk to search and investigate all collected logs from one interface.

---

# ⚙️ Splunk Components

Splunk consists of several important components that work together to process and analyze data.

### Forwarder

* Collects logs from endpoints, servers, or network devices.
* Sends the collected data to the Indexer.

### Indexer

* Receives and indexes incoming data.
* Stores logs in a searchable format.
* Processes events for fast searching.

### Search Head

* Provides the web interface for users.
* Allows analysts to search data using SPL (Search Processing Language).
* Creates dashboards, reports, and alerts.

Together, these components enable efficient log collection, storage, and investigation.

---

# 🧭 Splunk Navigation

I learned how to navigate the Splunk web interface and its main sections.

Important areas include:

* Home Dashboard
* Search & Reporting
* Apps
* Dashboards
* Reports
* Alerts
* Settings

The **Search & Reporting** application is the primary workspace for SOC analysts, where they search logs, investigate alerts, and create reports.

---

# 📥 Adding Data

Splunk is only useful when it has data to analyze. The first step in any deployment is collecting logs from different sources.

Common data sources include:

* Windows Event Logs
* Linux System Logs
* Firewall Logs
* Web Server Logs
* Application Logs
* IDS/IPS Logs
* Endpoint Security Logs

Data can be added through:

* Uploading log files
* Monitoring files and directories
* Using Universal Forwarders
* Connecting external log sources

Once the data is ingested, Splunk indexes it so analysts can search and investigate security events efficiently.

---

# 💡 Why Splunk is Important for a SOC Analyst

Splunk is one of the most widely used SIEM platforms in Security Operations Centers.

It helps SOC analysts to:

* Monitor security events
* Search and analyze logs
* Investigate alerts
* Detect suspicious activities
* Create dashboards and reports
* Support incident response

Learning Splunk is a fundamental skill for becoming a job-ready SOC Analyst.

---

# 🧠 Key Takeaway

Today's lesson introduced me to one of the most important tools used in a SOC. I learned how Splunk collects logs from multiple sources, organizes them into searchable data, and provides analysts with powerful tools to investigate and respond to security incidents.

---

# 📈 SOC Analyst Journey Progress

* ✅ Day 1 – SOC Fundamentals
* ✅ Day 2 – Human & System Attack Vectors
* ✅ Day 3 – Alert Triage & Alert Reporting
* ✅ Day 4 – SOC Workbooks, Lookups & Metrics
* ✅ Day 5 – Introduction to SIEM
* ✅ Day 6 – Introduction to EDR
* ✅ Day 7 – Splunk Basics
* ✅ **11 TryHackMe rooms completed**
