# SOAR EDR Playbook - Automated Incident Response

---

## 📌 Overview

This project demonstrates an automated **SOAR-based EDR incident response playbook** using LimaCharlie and Tines.  
The workflow detects malicious activity, notifies analysts, and optionally isolates infected machines automatically.

The objective is to simulate a **real-world SOC automated response workflow**.

---

## 🎯 Objectives

- Detect endpoint threats using EDR
- Automate alert handling using SOAR
- Notify analysts via Slack and Email
- Provide decision-based response workflow
- Isolate compromised endpoints automatically
- Reduce incident response time

---

## 🛠️ Tools & Technologies

- LimaCharlie (EDR)
- Tines (SOAR Platform)
- Slack (Alerting)
- Email Notification
- Windows Endpoint (Target Machine)

---

## 🏗️ Architecture Diagram
 
<img src="https://github.com/Prashant42125/SOAR-EDR/blob/main/Project_diagram.png" width="900px"/>

---

## ⚙️ Workflow

1. Endpoint gets infected
2. LimaCharlie detects malicious activity
3. Detection alert sent to Tines
4. Tines processes alert and extracts details
5. Alert sent to analyst via Slack / Email
6. User decision prompt: isolate machine?
7. If YES → LimaCharlie isolates endpoint
8. Isolation status sent back to Slack
9. If NO → Analyst notified for manual investigation

---

## 🚨 Detection Details Collected

- Time of detection
- Computer name
- Source IP
- Process information
- Command line
- File path
- Sensor ID
- Detection link

---

## 🔍 Response Actions

### Automatic Actions
- Alert generation
- Notification to Slack
- Email notification
- Isolation decision workflow

### Manual Decision
- Analyst chooses to isolate host
- Host containment executed via LimaCharlie

---

## 📊 Output

- Isolation confirmation message
- Non-isolation alert message
- Incident response logging
- Automated SOC workflow execution

---

## 🧠 Skills Demonstrated

- SOAR Automation
- EDR Integration
- Incident Response Automation
- SOC Workflow Design
- Threat Containment
- Alert Enrichment
- Blue Team Operations

---

## 🎓 Learning Outcomes

- SOAR playbook development
- EDR response automation
- Endpoint isolation techniques
- SOC alert workflow design
- Security automation concepts

---

## 👤 Author

**Prashant**  
CEHv13 | SOC Analyst | Blue Team | SOAR Automation Enthusiast
