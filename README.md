# Re-run after environment reset
readme_content = """
# 🛡️ SOC Analyst Portfolio

Hands-on cybersecurity projects focused on threat detection, log analysis, and incident response.

> This portfolio is shared exclusively with recruiters and hiring managers. It is not indexed by search engines.

---

## 📂 Contents

- [Phishing Analysis](./phishing-analysis)
- [Log Analysis](./log-analysis)
- [Detection Rules](./detection-rules)
- [Network Analysis](./network-analysis)
- [Threat Intelligence](./threat-intel)

---

## 👤 About Me

Aspiring SOC Analyst with practical skills in SIEM platforms, packet analysis, and detection engineering. Currently preparing for:
- CompTIA Network+ (Target: April 2025)
- CompTIA CySA+ (Target: August 2025)

**Core Skills:**
- Log analysis (Windows, Sysmon, Linux)
- Network traffic inspection (Wireshark)
- Splunk detection rule creation
- Incident triage and investigation
- Threat intelligence research and enrichment

---

## 🔗 Links

- [LinkedIn] (https://www.linkedin.com/in/-33b21b3b/)

"""

readme_path = "/mnt/data/README.md"
with open(readme_path, "w") as f:
    f.write(readme_content.strip())

readme_path
