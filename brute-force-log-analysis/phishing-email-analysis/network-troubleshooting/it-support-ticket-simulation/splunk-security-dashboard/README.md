# Splunk Security Dashboard – Log Monitoring & Threat Detection

## Objective
To simulate the use of a SIEM tool (Splunk) to monitor security logs, identify suspicious activity, and visualise potential threats using dashboard-style analysis.

---

## Tools Used
- Splunk (SIEM Platform)
- Simulated Security Log Data
- Basic Search Processing Language (SPL)

---

## Scenario
A simulated enterprise environment generated authentication and system logs. The goal was to analyse these logs in Splunk and identify potential security threats such as brute-force attacks and unusual login patterns.

---

## Activities Performed

### 1. Log Ingestion
- Imported simulated authentication logs into Splunk
- Structured logs for analysis and filtering

### 2. Log Analysis Using SPL
- Filtered failed login attempts using search queries
- Identified repeated authentication failures from single IP addresses
- Compared successful vs failed login patterns

### 3. Dashboard Creation
- Created visual dashboards showing:
  - Failed login attempts over time
  - Top source IP addresses generating alerts
  - Authentication success vs failure ratio

---

## Key Findings
- Multiple failed login attempts detected from a single IP address (indicative of brute-force behaviour)
- Spike in authentication failures within short time intervals
- Unusual login activity patterns compared to baseline behaviour

---

## Security Insights
- Potential brute-force attack attempts identified
- Need for account lockout policies and MFA enforcement
- Importance of continuous log monitoring in detecting early threats

---

## Skills Demonstrated
- SIEM log analysis (Splunk)
- Security event monitoring
- Threat detection and investigation
- Dashboard creation and data visualisation
- Incident interpretation and reporting
