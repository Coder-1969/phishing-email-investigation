# 📌 Indicators of Compromise (IOCs)

This file contains the indicators identified during the phishing email investigation.

---

## 🔍 Summary of Indicators

| Indicator | Type | Description |
|----------|------|------------|
| 209.85.167.226 | IP Address | Originating IP address extracted from the email header |
| etekno.xyz | Domain | Suspicious domain identified within the email, not related to Netflix |
| JGO47...@googlecloud.com | Email Address | Suspicious sender email used to impersonate a legitimate service |
| hxxps://t[.]co/yuxfZm8KPg?amp=1 | URL | Shortened URL used to hide the final malicious destination |

---

## ⚠️ Notes

- The domain **etekno.xyz** is not associated with Netflix and is likely malicious  
- The use of a shortened URL is a common phishing technique to obscure the destination  
- The originating IP address may be part of a larger phishing infrastructure  
- The sender email domain does not match the impersonated brand  

---

## 🚨 Threat Classification

- **Attack Type:** Phishing (Brand Impersonation)  
- **MITRE ATT&CK:** T1566 — Phishing  

---

## 🛡️ Recommended Actions

- Block the domain **etekno.xyz**  
- Block the malicious URL at network/firewall level  
- Monitor for similar indicators across the network  
- Alert users about phishing attempts  

---
