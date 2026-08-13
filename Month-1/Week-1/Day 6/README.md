# Day 6 – Introduction to Endpoint Detection and Response (EDR)

**Date:** 13 August 2026

# 🛡️ What is EDR?

**Endpoint Detection and Response (EDR)** is a security solution that continuously monitors endpoint devices such as laptops, desktops, and servers to detect, investigate, and respond to suspicious or malicious activities. Unlike traditional antivirus, EDR focuses on identifying attacker behavior and provides analysts with the tools to investigate and contain threats.

Common endpoints include:

* Laptops
* Desktop computers
* Servers
* Virtual machines
* Mobile devices

---

# 🚀 Beyond Traditional Antivirus

Traditional antivirus mainly detects **known malware** using signatures. While it is effective against known threats, it may miss advanced attacks such as fileless malware, ransomware, or attacks using legitimate system tools.

EDR goes beyond antivirus by:

* Continuously monitoring endpoint activity
* Detecting suspicious behavior
* Recording detailed endpoint events
* Supporting incident investigation
* Providing response actions such as isolating compromised devices

This allows organizations to detect threats that bypass traditional security controls.

---

# ⚙️ How EDR Works

A typical EDR workflow includes:

1. **Collect Telemetry** from endpoint devices.
2. **Monitor Activities** such as processes, network connections, and user actions.
3. **Analyze Behavior** using detection rules and behavioral analysis.
4. **Generate Alerts** when suspicious activity is detected.
5. **Investigate the Incident** using collected telemetry.
6. **Respond** by isolating the endpoint, terminating malicious processes, or removing threats.

This continuous monitoring helps SOC analysts quickly identify and contain attacks.

---

# 📊 EDR Telemetry

**Telemetry** is the data collected from endpoint devices that helps analysts investigate security incidents.

Examples of EDR telemetry include:

* Process creation and termination
* Command-line execution
* File creation, deletion, and modification
* Registry changes
* User logins and authentication events
* Network connections
* PowerShell activity
* Parent-child process relationships

This information provides visibility into what happened on an endpoint before, during, and after an attack.

---

# 🚨 Detection & Response Capabilities

An EDR solution provides several important capabilities:

### Threat Detection

* Detects suspicious behavior
* Identifies malware and ransomware
* Recognizes unusual process activity
* Detects credential theft attempts

### Investigation

* Displays detailed process trees
* Correlates related events
* Provides historical endpoint activity
* Supports forensic analysis

### Response

* Isolate compromised endpoints
* Kill malicious processes
* Quarantine malicious files
* Collect investigation data
* Support incident remediation

These capabilities enable SOC analysts to quickly detect, investigate, and contain threats before they spread across the network.

---

# 💡 Why EDR is Important for a SOC Analyst

As a SOC Analyst, EDR is one of the primary tools used during incident investigations. It provides detailed visibility into endpoint activity, helping analysts understand how an attack occurred, determine its impact, and respond effectively.

EDR also works alongside SIEM by supplying detailed endpoint data that can be correlated with logs from other security tools to improve threat detection.

---

# 🧠 Key Takeaway

Today's lesson showed me that **EDR is much more than an antivirus solution**. It continuously monitors endpoint activity, collects detailed telemetry, detects suspicious behavior, and provides powerful investigation and response capabilities. For a SOC Analyst, EDR is an essential tool for identifying, investigating, and containing modern cyber threats.

---

# 📈 SOC Analyst Journey Progress

* ✅ Day 1 – SOC Fundamentals
* ✅ Day 2 – Human & System Attack Vectors
* ✅ Day 3 – Alert Triage & Alert Reporting
* ✅ Day 4 – SOC Workbooks, Lookups & Metrics
* ✅ Day 5 – Introduction to SIEM
* ✅ Day 6 – Introduction to EDR
* ✅ **10 TryHackMe rooms completed**
