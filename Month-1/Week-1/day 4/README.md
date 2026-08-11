# Day 4 – SOC Workbooks, Lookups & SOC Metrics

**Date:** 11 August 2026
**TryHackMe Path:** SOC Level 1

## 🎯 Objective

Today I completed two TryHackMe rooms:

* SOC Workbooks and Lookups
* SOC Metrics and Objectives

The main goal was to understand how SOC analysts use workbooks, asset information, and lookups during investigations, and how SOC teams use metrics to measure and improve their performance.

---

# 📚 SOC Workbooks & Lookups

A **SOC workbook** is a structured guide that helps analysts follow consistent steps during an investigation.

Workbooks can contain:

* Investigation steps
* Important questions
* Data sources
* Useful commands
* Investigation procedures
* Response actions
* Escalation instructions

They help analysts avoid missing important information and make investigations more consistent.

---

## 🗂️ Asset Inventory

An **asset inventory** is a list of systems, devices, applications, and other resources that belong to an organization.

Examples include:

* Servers
* Workstations
* Network devices
* Applications
* Databases
* Cloud resources

Understanding the organization's assets is important during an investigation because the **importance of an alert depends partly on which asset is affected**.

For example, an alert involving a critical production server may require a higher priority than the same alert on a test machine.

---

## 🔍 Identifying Assets

During an investigation, analysts may need to identify:

* Which system generated the alert
* Who owns the system
* What type of system it is
* Where it is located
* How important it is to the organization
* Whether it contains sensitive information

This information provides context and helps the analyst determine the potential impact of an incident.

---

## 🔎 SOC Lookups

Lookups provide additional information about indicators discovered during an investigation.

Analysts may perform lookups on:

* IP addresses
* Domains
* URLs
* File hashes
* Usernames
* Hostnames

For example, if a suspicious IP address appears in an alert, an analyst can investigate the IP to gather additional information and determine whether it is associated with malicious activity.

---

# 📊 SOC Metrics & Objectives

SOC metrics are measurements used to understand how effectively a SOC is detecting, investigating, and responding to security incidents.

Metrics help SOC teams identify weaknesses and improve their security operations.

---

## 🎯 Core Metrics

Core metrics provide important information about the overall performance of a SOC.

Examples include:

* Number of alerts
* Number of incidents
* Detection time
* Response time
* False-positive rate
* Number of escalated incidents

These measurements help security teams understand their workload and performance.

---

## 🔎 Triage Metrics

**Triage metrics** focus specifically on how effectively analysts handle security alerts.

Examples include:

* Number of alerts investigated
* Time spent investigating alerts
* Number of alerts escalated
* False-positive rate
* Time taken to triage an alert

These metrics can help identify problems such as excessive alert volume or inefficient investigation processes.

---

## 📈 Improving Metrics

Metrics are not only used to measure performance. They can also help the SOC identify areas that need improvement.

For example:

**High false-positive rate**
→ Improve detection rules.

**High alert volume**
→ Review unnecessary or duplicate alerts.

**Long triage time**
→ Improve workbooks, automation, or analyst training.

**Long response time**
→ Improve escalation and incident response procedures.

The goal is to use metrics to continuously improve the SOC rather than simply use them as performance numbers.

---

# ⏱️ Important SOC Metrics

### Mean Time to Detect (MTTD)

The average time it takes to detect a security incident.

**Lower MTTD = Faster detection**

### Mean Time to Respond (MTTR)

The average time it takes to respond to and resolve a security incident.

**Lower MTTR = Faster response**

### False Positive Rate

The percentage of alerts that are determined to be legitimate activity rather than real threats.

A high false-positive rate can contribute to **alert fatigue**.

---

# 🔗 How Everything Connects

The concepts from today's rooms connect with the previous SOC topics:

**Asset Inventory → Alert → Triage → Lookups → Investigation → Escalation → Reporting → Metrics → Improvement**

A SOC analyst needs to understand the affected asset, investigate the alert using available information and lookups, and document the results.

The SOC then uses metrics to identify weaknesses and improve its detection and response processes.

---

# 🧠 Key Takeaway

Today's main lesson was that a professional SOC needs more than security alerts.

**Workbooks** provide a structured investigation process, **asset inventories** provide important context, **lookups** provide additional information, and **metrics** help the SOC measure and improve its performance.

A strong SOC continuously learns from its investigations and uses those lessons to improve detection, triage, and response.

---

# 📈 SOC Analyst Journey Progress

* ✅ Day 1 – SOC Fundamentals
* ✅ Day 2 – Human & System Attack Vectors
* ✅ Day 3 – Alert Triage & Alert Reporting
* ✅ Day 4 – SOC Workbooks, Lookups & Metrics
* ✅ **8 TryHackMe rooms completed**