# Threat-Hunting-Threat-Intelligence-Project-


## Overview
This project demonstrates threat hunting and security monitoring using log data. Suspicious activities such as authentication failures and abnormal system behavior were analyzed, and attacker IPs were identified and validated using threat intelligence platforms.

---

## Objectives
- Detect suspicious activities from logs
- Identify attacker IP addresses
- Analyze alert severity and patterns
- Validate indicators using threat intelligence
- Build security dashboards

---

## Tools Used
- Wazuh (SIEM - concept based)
- Kibana-style dashboards
- VirusTotal (IP reputation)
- AbuseIPDB (threat intelligence)
- Linux log dataset

---

---

## 🔍 Key Analysis Performed

### 1. Top Attacker IPs
- Identified IPs with highest failed login attempts
- Example:
  - 185.220.101.1 (High activity)
  - 73.117.146.84

---

### 2. Alert Severity Analysis
- Categorized alerts into:
  - Low (Login success)
  - Medium (Authentication failure)
  - High (File/system changes)

---

### 3. Security Events Over Time
- Observed spikes in failed login attempts
- Identified attack time windows

---

### 4. Top Triggered Rules
- Authentication failure (Brute force)
- Successful login
- File deletion activity

---

## Threat Intelligence Validation

### 🔹 VirusTotal
- Checked IP reputation and detections

### 🔹 AbuseIPDB
- Verified abuse score and reported activity

---

## 📊 Dashboards

### Main Dashboard
### Top Attacker IPs
### Alerts Timeline
### Severity Distribution
### Triggered Rules
##  Findings

- Multiple failed login attempts indicate brute force activity
- IP 185.220.101.1 showed highest suspicious behavior
- Attack spikes observed in short time intervals
- Threat intelligence confirmed malicious IP activity

---

##  MITRE ATT&CK Mapping

- T1110 – Brute Force
- T1078 – Valid Accounts

---

## Conclusion

This project demonstrates practical SOC analyst skills including threat detection, log analysis, dashboard creation, and threat intelligence validation.

---

## 👨‍💻 Author
SOC Analyst | SIEM | Threat Hunting | Wazuh | Splunk
