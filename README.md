# 🛡️ SOC Investigation Report — Phishing Attack Leading to PowerShell Recon & DNS Exfiltration

## 📌 Overview

This repository contains a detailed **SOC Level 1 incident investigation report** based on a simulated enterprise environment.
The case demonstrates a full attack lifecycle — from **phishing initial access** to **post-compromise reconnaissance, data staging, and suspected DNS exfiltration**.

The report showcases practical SOC analyst skills including:

* Log analysis and correlation
* Alert triage and validation
* Threat behavior mapping
* Incident impact assessment
* Documentation and escalation decisions

---

## 🎯 Objectives

* Demonstrate real-world SOC investigation workflow
* Practice evidence-based incident analysis
* Map observed activity to attacker tactics and techniques
* Produce professional incident documentation

---

## 🧪 Scenario Summary

An executive workstation was compromised after receiving a phishing email containing a malicious ZIP attachment.
Subsequent activity revealed:

* PowerShell-based reconnaissance (PowerView)
* Unauthorized network share access
* Data staging using native tools (Robocopy)
* Encoded DNS queries consistent with tunneling

The investigation follows the attack progression from **initial access → discovery → collection → exfiltration**.

---

## 🧰 Skills Demonstrated

* SIEM & log analysis
* Endpoint telemetry investigation
* Windows forensic artifacts interpretation
* Living-off-the-land technique identification
* Incident severity classification
* Security reporting & communication

---

## 📂 Contents

* 📄 **SOC L1 Incident Report (PDF)** — Full investigation document
* 📝 Supporting screenshots and evidence

---

## 🗺️ Attack Techniques Observed

* Phishing (Initial Access)
* PowerShell Execution
* Account & Network Discovery
* Network Share Access
* Data Staging
* DNS Tunneling / Exfiltration

---

## 📊 Key Takeaways

* Phishing remains a high-success initial access vector
* Native Windows tools can be abused to evade detection
* Correlating multi-source telemetry is critical for timeline reconstruction
* Behavioral indicators are essential when reputation data is limited

---

## ⚠️ Disclaimer

This project is based on a **TryHackMe training lab** and is intended for **educational and portfolio purposes only**.
All indicators and artifacts exist in a controlled environment.

---

## 👤 Author

**Justin Benedict P. Mendoza**
Aspiring SOC Analyst | Cybersecurity Enthusiast

---

⭐ If you found this useful or interesting, feel free to star the repo!
