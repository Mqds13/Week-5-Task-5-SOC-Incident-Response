# Cyber Security Internship - Week 5 Task 5

## SOC Incident Detection & Response Plan

This repository contains my Week 5, Task 5 work completed as part of the Cyber Security Internship Program.

### Student Information

* **Student Name:** Muqaddis Sanobar
* **Program/Course:** Cyber Security Internship (CYBERSEC-101L)
* **Internship Week:** Week 5
* **Task Number:** Task 5
* **Task Title:** SOC Incident Detection & Response Plan
* **Scenario:** NGO Donor Database
* **Focus Area:** SIEM / Incident Response

## Task Overview

This task focuses on the defensive side of cybersecurity, particularly Security Operations Center (SOC) activities, SIEM alert analysis, incident detection, alert triage, incident classification, and incident response planning.

A simulated NGO Donor Database scenario was used to analyze SIEM-style security alerts and determine whether the activity represented a genuine security incident.

The task was completed as a simulated academic exercise. No real NGO system, production SIEM, or live infrastructure was accessed.

## Scenario

The simulated environment consists of an NGO Donor Database hosted on a Linux-based application server.

The SIEM environment was modelled around tools such as Wazuh and Splunk. Authentication logs, web application logs, and host activity were considered for detecting suspicious activity.

The simulated alerts showed multiple failed login attempts from an external IP address, followed by a successful administrator login and unusual activity.

## Key Activities

The following activities were covered in this task:

* Reviewed simulated SIEM alerts.
* Analyzed repeated failed authentication attempts.
* Identified a suspicious successful login following multiple failures.
* Analyzed unusual database export activity.
* Identified the creation of a new administrative account.
* Performed alert triage.
* Distinguished a false positive from a confirmed security incident.
* Assessed the severity and priority of the incident.
* Identified Indicators of Compromise (IOCs).
* Created a simulated incident timeline.
* Developed an incident response plan.
* Applied the NIST SP 800-61 incident response lifecycle.
* Recommended preventive security controls.

## Tools and Technologies

The task referenced the following tools, technologies, and frameworks:

* **Wazuh** - SIEM/XDR reference platform
* **Splunk** - SIEM and log-search reference platform
* **Linux SSH/Auth Logs** - Authentication event source
* **Windows Event Logs** - Reference for authentication events
* **NIST SP 800-61** - Incident Response framework
* **Cyber Kill Chain** - Attack-stage analysis framework

## Lab Manual Experiments

This task was directly related to the following experiments from the CYBERSEC-101L Cyber Security Lab Manual:

### Experiment 14

**Defensive Security Fundamentals - Blue Team & SOC Basics**

Covered SOC fundamentals, the SOC analyst role, Cyber Kill Chain concepts, and basic log review.

### Experiment 15

**SIEM Basics - Splunk & Wazuh**

Covered SIEM concepts, log searching, alert detection, and correlation rules.

### Experiment 16

**Incident Response Process**

Covered the incident response lifecycle, containment strategies, incident analysis, and incident report structure.

## Incident Response Lifecycle

The incident response plan followed these six phases:

1. **Preparation**
2. **Identification**
3. **Containment**
4. **Eradication**
5. **Recovery**
6. **Lessons Learned**

## Incident Findings

The simulated alert sequence indicated a confirmed security incident involving:

* Multiple failed login attempts against an administrator account.
* A successful login from the same external source.
* Suspicious database export activity.
* Creation of a new administrative account.

The simulated incident was classified as **HIGH / P2 priority** because donor Personally Identifiable Information (PII) could potentially be exposed and system integrity could be affected.

## Recommended Security Controls

The task recommended several preventive controls, including:

* Multi-Factor Authentication (MFA) for administrative accounts.
* Account lockout and rate limiting.
* SIEM correlation rules for failed logins followed by successful login.
* Alerts for unusual bulk data export activity.
* Monitoring of new administrative account creation.
* Approved IP allow-listing where feasible.
* Enhanced monitoring after incident recovery.

## Important Note

All alerts, timestamps, IP addresses, logs, and incident details used in this task are simulated and academic.

No real NGO Donor Database was compromised, and no live security incident was investigated.

## Repository Contents

This repository contains the documentation/report for Week 5, Task 5 of the Cyber Security Internship Program.

### Report

**Week5_Task5_MuqadisSanobar.docx**

The report contains the complete simulated SOC incident detection and response analysis, including alert triage, incident identification, IOCs, incident timeline, response methodology, security recommendations, limitations, and learning outcomes.

## Learning Outcomes

After completing this task, I gained an understanding of:

* SOC monitoring and analyst responsibilities.
* SIEM-based security alert analysis.
* Alert triage and incident identification.
* Brute-force attack indicators.
* Indicators of Compromise (IOCs).
* Incident severity classification.
* The NIST SP 800-61 incident response lifecycle.
* Containment, eradication, and recovery procedures.
* Preventive security controls and security recommendations.

**Cyber Security Internship Program**
**CYBERSEC-101L | Week 5 | Task 5**
