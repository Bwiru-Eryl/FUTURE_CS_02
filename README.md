# SIEM-Based Incident Monitoring and Analysis

## Project Overview

This project replicates real-world security event monitoring using **Splunk SIEM**. The objective was to analyze structured log data to detect suspicious behaviors, including failed logins, brute-force attempts, malware activity, and user-IP anomalies.

## Tools & Environment

* **SIEM Platform:** Splunk (Free Trial)
* **Log Source:** `SOC_Task2_Sample_Logs.txt` (custom sample logs)
* **Environment:** Splunk Web Interface using SPL (Search Processing Language)

---

## Methodology

### 1. Splunk Setup

* Registered for a Splunk account and accessed the web dashboard.
* Selected Windows logs (Application, Security, System) as sources.
* Uploaded the sample log file and confirmed ingestion with a wildcard SPL query (`*`), returning over **107,000 events**.

### 2. Log Analysis (SPL Queries)

* Queried failed login attempts to detect unusual patterns.
* Correlated failed and successful login events to identify possible credential misuse.
* Highlighted frequent login failures by user/IP to detect brute-force sources.
* Investigated malware detection entries, mapping them to affected users and IP addresses.

### 3. Incident Investigation

* Analyzed brute-force attempts, malware infections, and account compromise indicators.
* Classified incidents by severity and developed tailored responses.

### 4. Recommendations

* **Immediate Actions:** IP blocking, user password resets, isolating compromised hosts.
* **Preventive Measures:** Enable MFA, enforce login throttling, conduct regular audits.
* **Ongoing Strategy:** Continuous monitoring and security awareness training.

### 5. Reporting

* Composed an incident summary email outlining findings, impact, and response recommendations.

---

## Key Takeaways

* Gained practical experience in log ingestion and threat detection using Splunk SPL.
* Identified attack vectors such as brute-force, malware, and credential compromise.
* Learned how to correlate diverse log types to extract meaningful insights.
* Developed skills in incident reporting and communication.

---

## Disclaimer

> This project was conducted in a controlled environment using simulated data. No real systems or sensitive information were used or affected.

---

## Author

**Eryl Bwiru**
Intern – Future Interns Program
**Date:** August 2025


