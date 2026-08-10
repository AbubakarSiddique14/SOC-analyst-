# Day 3 – Alert Triage & Alert Reporting

**Date:** 10 August 2026
**TryHackMe Path:** SOC Level 1

## 🎯 Objective

Today I completed two TryHackMe rooms:

* Alert Triage
* Alert Reporting

The main goal was to understand how SOC analysts receive security alerts, evaluate their importance, investigate them, and communicate their findings through proper reporting.

---

# 🔎 Alert Triage

**Alert triage** is the process of reviewing and analyzing security alerts to determine their severity, priority, and required action.

A SOC can receive a large number of alerts, so analysts cannot investigate every alert with the same priority. They must quickly identify which alerts could represent real threats.

### Important Alert Properties

Some important information found in an alert includes:

* Alert name and ID
* Date and timestamp
* Severity
* Source and destination IP
* Username
* Hostname
* Detection rule
* Event details
* Affected system

This information provides the initial context for an investigation.

---

## 🚨 Alert Prioritization

Alert prioritization helps analysts decide which alerts should be investigated first.

Important factors include:

* **Severity:** How dangerous is the activity?
* **Asset criticality:** How important is the affected system?
* **User privileges:** Is the affected account an administrator?
* **Evidence of compromise:** Is there evidence that an attacker succeeded?
* **Business impact:** Could the activity affect important business operations?

### False Positive vs True Positive

**False Positive:**
An alert is triggered, but the activity is legitimate.

**True Positive:**
An alert correctly identifies suspicious or malicious activity.

A SOC analyst must investigate the available evidence before deciding whether an alert is a real security incident.

---

# 👥 Roles in Alert Triage

Different SOC roles may handle different stages of an investigation.

### Tier 1 Analyst

* Monitor alerts
* Perform initial triage
* Identify false positives
* Gather basic information
* Prioritize alerts
* Escalate suspicious activity

### Tier 2 Analyst

* Perform deeper investigations
* Correlate multiple events
* Analyze logs and endpoint activity
* Investigate suspicious behavior

### Tier 3 Analyst

* Handle complex investigations
* Perform advanced threat hunting
* Support advanced incident response
* Improve detection capabilities

If an analyst cannot resolve an alert at their level, it should be properly escalated.

---

# 📝 Alert Reporting

**Alert reporting** is the process of documenting an alert investigation and communicating the results to other members of the security team.

A good report should allow another analyst to understand what happened without repeating the entire investigation.

### Basic Report Structure

1. **Incident Title**
2. **Alert Information**
3. **Summary**
4. **Investigation**
5. **Findings**
6. **Impact**
7. **Actions Taken**
8. **Recommendations**

A good SOC report should be:

* Clear
* Accurate
* Concise
* Objective
* Based on evidence

---

# 📢 Escalation & Communication

If an alert requires further investigation, the SOC analyst may escalate it to a higher-level analyst or another security team.

A good escalation should explain:

* What happened
* When it happened
* Which user or system was affected
* What evidence was discovered
* What actions were already taken
* Why the alert requires escalation

Good communication is important because unclear reporting can delay incident response.

---

# 🧠 What I Learned

Today's rooms taught me that a SOC analyst does not simply receive an alert and immediately call it an attack.

The analyst needs to:

**Review → Prioritize → Investigate → Validate → Escalate → Report**

This process helps the SOC focus its resources on genuine threats and respond to incidents efficiently.

---

# 💡 Key Takeaway

**Alert triage helps determine what needs attention, while alert reporting communicates what was discovered and what should happen next.**

Both skills are essential for a SOC Analyst because security alerts are only useful when analysts can correctly understand, investigate, and communicate them.

---

# 📈 SOC Analyst Journey Progress

* ✅ Day 1 – SOC Fundamentals
* ✅ Day 2 – Human & System Attack Vectors
* ✅ Day 3 – Alert Triage & Alert Reporting
* ✅ **6 TryHackMe rooms completed**


