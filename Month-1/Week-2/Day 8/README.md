# Day 8 – Introduction to SOAR (Security Orchestration, Automation, and Response)
## 🎯 Objective

Today I completed the **Introduction to SOAR** room in the TryHackMe SOC Level 1 path. The objective was to understand what SOAR is, the challenges faced by traditional SOCs, how SOAR improves security operations, and how playbooks automate incident response workflows.

---

# 🛡️ What is SOAR?

**SOAR (Security Orchestration, Automation, and Response)** is a security platform that integrates multiple security tools, automates repetitive tasks, and helps SOC teams respond to incidents more efficiently. It works alongside tools like SIEM, EDR, firewalls, and threat intelligence platforms to streamline security operations.

SOAR is built around three key capabilities:

* **Orchestration:** Connects different security tools into one platform.
* **Automation:** Executes repetitive tasks automatically.
* **Response:** Performs or assists with incident response actions.

---

# ⚠️ Traditional SOC & Challenges

Traditional SOC teams often face several operational challenges, including:

* High alert volume
* Alert fatigue
* Manual and repetitive investigations
* Multiple disconnected security tools
* Slow incident response
* Limited analyst resources

These challenges can delay investigations and reduce the overall efficiency of the SOC.

---

# 🚀 Overcoming SOC Challenges with SOAR

SOAR helps overcome these challenges by automating repetitive workflows and integrating different security solutions into a single platform.

Some benefits of SOAR include:

* Faster alert triage
* Automated investigation steps
* Reduced manual workload
* Consistent incident response
* Faster containment and remediation
* Improved collaboration between security teams

By automating routine tasks, SOC analysts can focus on making critical security decisions instead of spending time on repetitive processes.

---

# 📖 Building SOAR Playbooks

A **SOAR playbook** is a predefined workflow that automates the investigation and response process for a specific type of security incident.

Playbooks ensure that every incident is handled using a consistent and repeatable process.

### Phishing Playbook

A phishing playbook may include the following steps:

1. Receive a phishing alert.
2. Create an investigation ticket.
3. Check URLs and attachments.
4. Query threat intelligence sources.
5. Determine if the email is malicious.
6. Quarantine the email.
7. Block the sender or domain.
8. Notify affected users.
9. Escalate the incident if required.

This automation reduces investigation time while still allowing analysts to review important decisions.

---

### CVE Patching Playbook

A CVE playbook helps automate vulnerability management by:

* Monitoring newly published CVEs
* Identifying vulnerable assets
* Assessing the severity of vulnerabilities
* Creating patching tickets
* Testing patches before deployment
* Verifying successful remediation
* Developing a mitigation plan if patching is not immediately possible

This helps organizations respond more quickly to newly disclosed vulnerabilities.

---

# 💡 Why SOAR is Important for a SOC Analyst

SOAR does **not replace SOC analysts**. Instead, it automates repetitive tasks so analysts can focus on investigation, decision-making, and incident response.

Using SOAR, analysts can:

* Investigate alerts faster
* Reduce manual effort
* Improve response consistency
* Minimize response time
* Handle a larger number of incidents efficiently

---

# 🧠 Key Takeaway

Today's lesson taught me that **SOAR enhances SOC operations by combining orchestration, automation, and response into a single platform**. Through automated playbooks, repetitive tasks such as phishing investigations and CVE management can be completed more efficiently, allowing SOC analysts to focus on higher-value security investigations and decision-making.

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
* ✅ **12 TryHackMe rooms completed**
