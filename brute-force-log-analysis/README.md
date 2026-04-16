# Brute Force Attack Detection (Log Analysis)

## Objective
To identify and analyse suspicious login attempts and detect brute-force attack patterns.

---

## Scenario
A system showed repeated failed login attempts within a short period. The objective was to analyse the logs and determine whether this activity indicated a brute-force attack.

---

## Analysis Process
- Reviewed authentication logs for failed login attempts  
- Identified repeated login failures from a single IP address  
- Observed rapid login attempts within short time intervals  
- Compared activity against normal login behaviour  

---

## Findings
- Multiple failed login attempts detected from a single source  
- Pattern consistent with brute-force attack behaviour  
- Over 20 failed login attempts recorded within minutes  

---

## Risk Impact
- Potential unauthorized access to user accounts  
- Increased risk of account compromise  

---

## Recommendations
- Implement account lockout policies after multiple failed attempts  
- Enable multi-factor authentication (MFA)  
- Monitor login activity using SIEM tools  
- Block suspicious IP addresses  

---

## Skills Demonstrated
- Log analysis  
- Threat detection  
- Security monitoring  
- Incident reporting  
