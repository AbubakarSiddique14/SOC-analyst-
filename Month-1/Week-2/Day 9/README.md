# Day 9 – Elastic Stack: The Basics

Today I completed the **Elastic Stack: The Basics** room in the TryHackMe SOC Level 1 path. The objective was to understand the Elastic Stack, its components, how to explore logs using Kibana, perform searches with KQL, and create visualizations and dashboards for security monitoring.

---

# 🛡️ Introduction to Elastic Stack

The **Elastic Stack (ELK Stack)** is a powerful platform used to collect, store, search, analyze, and visualize large amounts of data. Many Security Operations Centers (SOCs) use the Elastic Stack as a SIEM solution to investigate security events and monitor their environments. It helps analysts quickly search logs, identify suspicious activities, and gain valuable insights through dashboards and visualizations.

The core components of the Elastic Stack are:

* **Elasticsearch** – Stores and indexes data for fast searching.
* **Kibana** – Provides a web interface to search, analyze, and visualize data.
* **Logstash** – Collects, processes, and transforms log data.
* **Beats / Elastic Agent** – Collects logs and sends them to Elasticsearch.

---

# 🔍 Discover Tab

The **Discover** tab is one of the most important features in Kibana. It allows analysts to explore raw log data, search events, apply filters, and investigate suspicious activities.

Using Discover, a SOC analyst can:

* Search logs in real time
* Filter events by different fields
* View detailed log information
* Investigate security incidents
* Save searches for future investigations

The Discover tab is usually the starting point of an investigation.

---

# 💻 KQL (Kibana Query Language)

**KQL (Kibana Query Language)** is used to search and filter data stored in Elasticsearch.

It allows analysts to quickly find relevant events without searching through every log manually.

Some common KQL searches include:

* Search by username
* Search by IP address
* Search by event type
* Filter by severity
* Search within a specific time range

Learning KQL is an essential skill because SOC analysts use it daily to investigate alerts and security incidents.

---

# 📊 Creating Visualizations

Visualizations transform raw log data into easy-to-understand charts and graphs.

Examples include:

* Bar Charts
* Pie Charts
* Line Charts
* Tables
* Metric Panels

Visualizations help analysts identify trends, detect anomalies, and better understand security events without manually reviewing thousands of log entries.

---

# 📈 Creating Dashboards

A **dashboard** combines multiple visualizations into a single screen, giving SOC analysts an overview of the organization's security posture.

Dashboards can display:

* Authentication events
* Failed login attempts
* Network activity
* Top source IP addresses
* Security alerts
* System performance

Dashboards make it easier to monitor security events and quickly identify unusual behavior.

---

# 💡 Why Elastic Stack is Important for a SOC Analyst

Elastic Stack is widely used for security monitoring because it enables analysts to:

* Collect and store logs
* Search large amounts of data quickly
* Investigate security incidents
* Create visual reports
* Monitor threats through dashboards
* Improve incident detection and response

Mastering Elastic Stack helps SOC analysts investigate threats more efficiently and make informed security decisions.

---

# 🧠 Key Takeaway

Today's lesson introduced me to another powerful platform used in Security Operations Centers. I learned how the Elastic Stack stores and analyzes logs, how the Discover tab is used for investigations, how KQL helps search security data, and how visualizations and dashboards transform raw logs into meaningful insights for security monitoring.

---

# 📈 SOC Analyst Journey Progress

* ✅ Day 1 – SOC Fundamentals
* ✅ Day 2 – Human & System Attack Vectors
* ✅ Day 3 – Alert Triage & Alert Reporting
* ✅ Day 4 – SOC Workbooks, Lookups & Metrics
* ✅ Day 5 – Introduction to SIEM
* ✅ Day 6 – Introduction to EDR
* ✅ Day 7 – Splunk Basics
* ✅ Day 8 – Introduction to SOAR
* ✅ Day 9 – Elastic Stack: The Basics
* ✅ **13 TryHackMe rooms completed**

