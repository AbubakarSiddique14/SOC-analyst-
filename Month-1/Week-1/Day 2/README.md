# Day 2 – Human & System Attack Vectors

**Date:** 5 August 2026

## 🎯 Objective

Understand how attackers target both people and computer systems, and learn how a Security Operations Center (SOC) detects and defends against these attacks.

---

# Room 3: Human Attack Vectors

## What is a Human Attack Vector?

A human attack vector is a technique where attackers target people instead of directly attacking systems. Rather than exploiting software vulnerabilities, they exploit human behavior such as trust, curiosity, fear, or lack of security awareness.

Humans are often considered the weakest link in cybersecurity because a single mistake can compromise an entire organization.

---

## Common Human Attack Vectors

### Phishing

Attackers send fake emails or messages that appear legitimate to steal usernames, passwords, or financial information.

**Example:**
An employee receives an email pretending to be from Microsoft asking them to verify their account credentials.

---

### Social Engineering

Attackers manipulate people into revealing confidential information or performing actions that benefit the attacker.

Examples include:

- Pretending to be IT support
- Impersonating company executives
- Phone scams (Vishing)
- SMS scams (Smishing)

---

### Insider Threats

Security incidents caused by employees, contractors, or trusted users.

These may be:

- Intentional
- Accidental
- Negligent

---

## How a SOC Defends Against Human Attacks

A SOC helps reduce human-based attacks by:

- Monitoring suspicious login attempts
- Detecting phishing activity
- Investigating unusual user behavior
- Monitoring email security alerts
- Detecting compromised accounts
- Responding quickly to reported incidents

---

# Room 4: System Attack Vectors

## What is a System Attack Vector?

A system attack vector is a weakness that allows attackers to compromise computers, servers, networks, or applications.

Instead of manipulating people, attackers exploit technical weaknesses.

---

## Common System Attack Vectors

### Software Vulnerabilities

Security flaws in applications or operating systems.

Examples:

- Buffer Overflow
- Remote Code Execution
- SQL Injection

---

### Misconfigurations

Incorrect security settings that expose systems to attackers.

Examples:

- Default passwords
- Open ports
- Public cloud storage
- Weak permissions
- Disabled security controls

---

### Unpatched Systems

Systems missing security updates are vulnerable to known exploits.

Keeping software updated reduces attack opportunities.

---

## How a SOC Protects Systems

A Security Operations Center protects systems by:

- Monitoring security logs
- Detecting malicious behavior
- Investigating alerts
- Identifying Indicators of Compromise (IOCs)
- Coordinating incident response
- Working with vulnerability management teams
- Recommending remediation actions

---

# Human vs System Attack Vectors

| Human Attack Vector | System Attack Vector |
|----------------------|----------------------|
| Targets people | Targets systems |
| Uses manipulation | Uses technical exploits |
| Social Engineering | Software Vulnerabilities |
| Phishing | Misconfiguration |
| Credential Theft | Remote Exploitation |
| Awareness Training reduces risk | Patching and hardening reduce risk |

---

# Key Concepts Learned Today

- Human Attack Vector
- System Attack Vector
- Phishing
- Social Engineering
- Insider Threats
- Software Vulnerabilities
- Misconfigurations
- Security Patching
- Indicators of Compromise (IOCs)
- Security Monitoring

---

# Real-World SOC Scenario

An employee receives a phishing email that appears to come from the company's HR department.

The employee clicks the malicious link and enters their credentials.

The attacker logs into the employee's Microsoft 365 account from a foreign country.

The SOC detects:

- An unusual login location
- Multiple failed login attempts
- A successful login from an unfamiliar IP address

The SOC investigates the alert, resets the user's password, terminates active sessions, blocks the malicious IP address, and documents the incident.

---

# Reflection

Today's lessons showed that attackers do not always rely on advanced hacking techniques. Many attacks begin by exploiting human behavior or simple system weaknesses such as unpatched software and poor configurations.

As a future SOC Analyst, understanding both human and system attack vectors is essential for identifying threats, investigating alerts, and helping protect an organization's assets.

---

# Progress Tracker

- ✅ Day 1 Completed
- ✅ Day 2 Completed
- 📚 TryHackMe Rooms Completed: 4