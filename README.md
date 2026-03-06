# SOC-Alert-Triage-Log

Summary of the alerts I have resolved on the letsdefend platform  
My profile: https://app.letsdefend.io/user/lburgosjr8  

## Alert ID #257
**Date:** 2026-02-19  
**Alert Title:** Phishing email  
**Severity:** Medium  
**Source:** 103.80.134.63 (External), free@coffeeshoop.com  
**Target:** Felix@letsdefend.io  

**Hypothesis:** External attacker attempting to install malware through phishing.  

**Evidence:**  
- Process executed in the endpoint  
- Attachment with a 61/75 virustotal score  

**Classification:** True Positive  
**Action Taken:** Deleted email from the user's inbox and contain the endpoint  

---

## Alert #86  
**Date:**2026-02-18  
**Alert Title:** Phishing URL  
**Severity:** High  
**Source IP:** 172.16.17.49 (Internal)  
**Target:** 91.189.114.8/mogagrocol.ru  

**Hypothesis:** The user opened the phishing url and compromised his endpoint  

**Evidence:**  
- Malicious IP 91.189.114.8  
- Malicious URL hxxp://mogagrocol.ru/wp-content/plugins/akismet/fv/index.php?email=ellie@letsdefend.,io  

**Classification:** True Positive  
**Action Taken:** Deleted email from the user's inbox and contain the endpoint  

---

## Alert #235  
**Date:** 2024-03-07  
**Alert Title:** SQL Injection  
**Severity:** High  
**Source IP:** 118.194.247.28  
**Target:** 172.16.20.12/WebServer1000  

**Hypothesis:** The attacker wants to get the passwd file from the server via SQL Injection  

**Evidence:**
- Malicious IP from china 118.94.247.28  
- Various SQL Injection attempts  

**Classification:** True Positive  
**Action Taken:** Contain the endpoint and escalate to L2  
