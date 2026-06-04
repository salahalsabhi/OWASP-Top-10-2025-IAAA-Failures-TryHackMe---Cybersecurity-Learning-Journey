# OWASP-Top-10-2025-IAAA-Failures-TryHackMe---Cybersecurity-Learning-Journey
I completed OWASP Top 10 2025: IAAA Failures room on TryHackMe! Learn about A01, A07, and A09 in how they related to failures in the applied IAAA model.

# OWASP Top 10 2025: IAAA Failures — TryHackMe Write-Up

## Overview

I successfully completed the **OWASP Top 10 2025: IAAA Failures** room on TryHackMe. This room explores how weaknesses in the **Identification, Authentication, Authorization, and Accountability (IAAA)** model contribute to some of the most critical web application security risks identified in the OWASP Top 10.

Through practical examples and hands-on exercises, the room demonstrates how failures in implementing identity and access controls can lead to unauthorized access, privilege escalation, sensitive data exposure, and insufficient auditability.

---

## Learning Objectives

* Understand the components of the IAAA security model.
* Learn how IAAA failures map to OWASP Top 10 2025 risks.
* Identify weaknesses in authentication and authorization mechanisms.
* Explore the security impact of poor logging and monitoring practices.
* Understand how attackers exploit identity and access control failures.
* Develop a defensive mindset for securing modern web applications.

---

# The IAAA Model

The IAAA model is a foundational security framework used to manage user identities, access rights, and accountability within systems.

## Identification

**Question:** Who are you?

Identification is the process of claiming an identity within a system.

Examples:

* Username
* Email address
* Employee ID
* Customer account number

A user must first identify themselves before authentication can occur.

---

## Authentication

**Question:** Can you prove who you are?

Authentication verifies the claimed identity using one or more authentication factors.

Examples:

* Passwords
* Multi-Factor Authentication (MFA)
* Security Tokens
* Biometrics

Weak authentication controls can lead to account compromise and unauthorized access.

---

## Authorization

**Question:** What are you allowed to do?

Authorization determines which resources and actions an authenticated user can access.

Examples:

* Standard User
* Moderator
* Administrator
* Super Administrator

Improper authorization controls often result in privilege escalation or unauthorized access to sensitive data.

---

## Accountability

**Question:** Can your actions be traced?

Accountability ensures actions performed within a system are logged and attributable to a specific user or process.

Examples:

* Audit Logs
* Event Logs
* Security Monitoring
* Access Records

Without proper accountability mechanisms, detecting malicious activity becomes significantly more difficult.

---

# OWASP Top 10 2025 Categories Covered

## A01: Broken Access Control

### Related IAAA Component:

Authorization

Broken Access Control occurs when users can perform actions or access resources beyond their intended permissions.

Examples:

* IDOR (Insecure Direct Object Reference)
* Privilege Escalation
* Accessing Admin Pages as a Standard User
* Unauthorized Data Access

Impact:

* Data Exposure
* Account Takeover
* Administrative Access
* Compliance Violations

---

## A07: Identification and Authentication Failures

### Related IAAA Components:

Identification + Authentication

This category focuses on weaknesses in identity verification and authentication processes.

Examples:

* Weak Password Policies
* Credential Stuffing
* Lack of MFA
* Session Management Issues
* Predictable Session Tokens

Impact:

* Account Compromise
* Unauthorized Access
* Credential Theft
* Identity Impersonation

---

## A09: Security Logging and Monitoring Failures

### Related IAAA Component:

Accountability

Organizations rely on logging and monitoring to detect, investigate, and respond to security incidents.

Examples:

* Missing Audit Logs
* Insufficient Monitoring
* Failure to Alert on Suspicious Activity
* Incomplete Security Event Records

Impact:

* Delayed Incident Response
* Undetected Attacks
* Limited Forensic Evidence
* Reduced Visibility into Threat Activity

---

# Practical Skills Gained

During this room, I developed practical knowledge in:

* Access Control Analysis
* Authentication Security
* Session Management Concepts
* Identity Management Fundamentals
* Security Monitoring Principles
* Audit Logging Requirements
* Threat Detection Concepts
* Web Application Security
* Risk Assessment
* Defensive Security Practices

---

# Security Lessons Learned

### Strong Authentication Matters

Organizations should implement:

* Multi-Factor Authentication (MFA)
* Secure Password Policies
* Account Lockout Mechanisms
* Session Expiration Controls

---

### Authorization Must Be Enforced Server-Side

Client-side controls should never be trusted.

Every request should be validated against:

* User Roles
* Permissions
* Ownership Rules
* Business Logic

---

### Logging Is a Security Control

Effective logging enables:

* Threat Detection
* Incident Response
* Forensic Investigations
* Regulatory Compliance

Without visibility, security teams cannot effectively defend their environments.

---

# Key Takeaways

* Authentication verifies identity.
* Authorization determines permissions.
* Accountability provides traceability.
* Failures in any IAAA component can create significant security risks.
* OWASP Top 10 categories often originate from weaknesses in identity and access management.
* Security logging is critical for detecting and responding to attacks.

---

# Conclusion

The **OWASP Top 10 2025: IAAA Failures** room provided valuable insight into how modern web applications can become vulnerable when identification, authentication, authorization, and accountability controls are improperly implemented.

By studying the relationship between the IAAA model and OWASP Top 10 categories A01, A07, and A09, I gained a stronger understanding of identity-centric security risks and the defensive measures required to protect web applications against real-world threats.

---

**Platform:** TryHackMe
**Room:** OWASP Top 10 2025: IAAA Failures
**Category:** Web Security / OWASP Top 10 / Blue Team Fundamentals
**Difficulty:** Beginner
---
My LinkedIn :[
My X :[https://x.com/charisma1385/status/2062555165178138991]
---
#TryHackMe #OWASP #OWASPTop10 #CyberSecurity #WebSecurity #Authentication #Authorization #AccessControl #IdentityManagement #SecurityMonitoring #BlueTeam #SOCAnalyst #ThreatDetection #SecurityAwareness #DefensiveSecurity #AppSec #InformationSecurity
