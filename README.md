# Cybersecurity-Detection-Rules
Cyber Detection Rules

---

## 🧠 Detection Philosophy

- **Behavior over indicators** – avoid static IOCs where possible  
- **Threat-informed** – aligned with adversary TTPs  
- **Context-aware** – leverage enrichment and correlation  
- **Defender-centric** – written for SOC, DFIR, and Threat Intel teams  

Where applicable, detections include:
- MITRE ATT&CK mappings
- Tuning recommendations
- Optional enhancement logic
- Known evasion considerations

---

## 🧪 Rule Quality Standards

Each detection rule should clearly specify:

- **Purpose** – what behavior is being detected  
- **Data sources required** – DNS logs, EDR, proxy, auth logs, etc.  
- **Detection logic** – query or rule logic  
- **Expected false positives** – and how to reduce them  
- **Severity & confidence** – recommended triage priority  

---

## ⚙️ Supported Platforms (Non-Exhaustive)

- YARA / YARA-L / YARA-L 2.0  
- Splunk SPL  
- Elastic (KQL)  
- Microsoft Sentinel (KQL)  
- Network telemetry (DNS, proxy, NetFlow)

---

## 🚨 Disclaimer

These detection rules are provided **as-is** for research and defensive purposes.

- They may require tuning for your environment  
- Not all detections are production-ready by default  
- No guarantee is provided regarding completeness or accuracy  

Always validate detections in a test environment before deployment.

---

## 🤝 Contributions

Contributions are welcome and encouraged.

When submitting new rules:
- Follow the existing structure
- Document assumptions and limitations
- Avoid environment-specific hardcoding
- Include ATT&CK mappings where relevant

---

## 📄 License

Specify your chosen license here (e.g., MIT, Apache 2.0, GPL).
Ensure compatibility with your organization’s legal and compliance requirements.

---

## 🎯 Intended Audience

- SOC Analysts  
- Detection Engineers  
- Threat Hunters  
- DFIR Practitioners  
- Security Researchers  

---

**Detection is not about blocking everything — it’s about understandin**
