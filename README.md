# 📊 AWS-GRC Automated IAM Audit Pipeline  
### Continuous Cloud Compliance Evidence for Modern GRC Teams

> **Positioning:** Enterprise-Style GRC Automation Proof-of-Concept  
> **Focus:** SOC 2 + NIST Control Evidence | Cloud-Native GRC | Compliance as Code  
> **Built For:** GRC Engineers, Security Leadership, Recruiters, Hiring Managers  

---

## 📌 Project Overview

Traditional GRC audits rely heavily on manual screenshots, spreadsheets, and last-minute evidence gathering. That model does not scale in modern cloud environments where infrastructure and identities change constantly.

The **GRC Automated IAM Audit Pipeline** demonstrates how GRC can shift from reactive, point-in-time auditing to **continuous, automated compliance evidence collection** using native AWS services.

This project automatically collects IAM user data, generates timestamped audit reports, stores immutable evidence in cloud storage, and sends confirmation notifications — all on a scheduled basis without manual intervention.

---

## 🎯 Who This Project Is For

### 👨‍💻 GRC Engineers
- Reduce manual audit preparation time  
- Implement continuous compliance monitoring  
- Build repeatable evidence pipelines  

### 🏢 Security & Compliance Leadership
- Increase audit readiness year-round  
- Reduce compliance labor costs  
- Improve risk visibility and reporting confidence  

### 💼 Recruiters & Hiring Managers
Demonstrates real-world capability in:
- Cloud GRC automation  
- Serverless security architecture  
- Compliance evidence engineering  
- Modern audit strategy design  

---

## 🎥 Click the Picture to Watch Demo Video ⬇️
[![GRC Automated IAM Audit Pipeline Demo](https://github.com/user-attachments/assets/85891451-debc-4fd9-9c17-4e2ba48cf085)](https://youtu.be/Nv-MAXMSAHM)



## 🚨 The Problem With Traditional GRC Audits

### Old Model
- Annual or quarterly audit prep scramble  
- Manual screenshots and spreadsheet tracking  
- Evidence gaps due to human error  
- High audit consulting costs  
- No continuous visibility into access risk  

### Modern Cloud Reality
Cloud environments change:
- Hourly  
- Daily  
- At infrastructure scale  

Manual GRC processes cannot keep up.

---

## ✅ The Modern GRC Approach (This Project)

This pipeline shifts GRC to:

- **Continuous Compliance**
- **Automated Evidence Collection**
- **Immutable Audit Trails**
- **Proactive Risk Monitoring**

---

## 🏗 Architecture Overview

### AWS Native Serverless GRC Evidence Pipeline

**EventBridge (Scheduler)**  
⬇  
**AWS Lambda (Python Evidence Collector)**  
⬇  
**IAM (Data Source)**  
⬇  
**S3 (Evidence Storage — Date-Organized)**  
⬇  
**SNS (Audit Confirmation Notification)**  

---

## ⚙️ How It Works

### 1️⃣ Scheduled Compliance Monitoring
EventBridge automatically triggers the pipeline (example: every Sunday at midnight).

### 2️⃣ Automated Evidence Collection
Lambda runs a Python script that:
- Pulls all IAM users  
- Captures username, ARN, creation timestamp  
- Generates structured audit report  

### 3️⃣ Immutable Evidence Storage
Reports are stored in S3 using:

evidence/YYYY-MM-DD/iam_users_report_HHMMSS.txt


Creates historical, timestamped audit proof.

### 4️⃣ Audit Confirmation Notifications
SNS sends confirmation including:
- Evidence location  
- User count  
- Success or failure status  

---

## 📊 Compliance Framework Alignment

### SOC 2 Alignment
Supports:
- CC6 — Logical Access Controls  
- CC7 — System Monitoring  
- Evidence of identity governance activities  

### NIST 800-53 Alignment
Supports evidence collection for:
- AC-2 — Account Management  
- AC-6 — Least Privilege Validation Support  
- AU-2 / AU-6 — Audit Event Logging and Review  

---

## 💰 Business Value

### Cost Reduction
- Reduces audit prep labor hours  
- Minimizes external audit consulting dependency  

### Risk Reduction
- Detects access growth trends early  
- Provides historical forensic evidence  

### Operational Efficiency
- Removes manual evidence gathering  
- Creates repeatable audit workflows  

### Executive Confidence
- Proves controls operate continuously — not just during audits  

---

## 🚀 Why This Is Better Than Traditional GRC

| Traditional GRC | Automated Cloud GRC |
|---|---|
| Manual screenshots | Automated evidence generation |
| Point-in-time audits | Continuous compliance validation |
| Spreadsheet tracking | Immutable cloud evidence storage |
| Human error risk | Programmatic consistency |
| High audit prep stress | Always audit-ready |

---

## 🔮 Future of GRC Direction

This project models the shift toward:

- Compliance as Code  
- Evidence Engineering  
- Continuous Controls Monitoring (CCM)  
- Cloud-Native Audit Automation  
- AI-Augmented GRC Operations  

---

## 🧠 Skills Demonstrated

- Cloud GRC Automation  
- AWS Serverless Security Architecture  
- Compliance Evidence Pipeline Design  
- SOC 2 / NIST Control Mapping  
- Python Security Automation  
- IAM Governance Monitoring  
- Audit Readiness Engineering  
- Security Notification & Alerting Design  

---

## 🛠 Tech Stack

- AWS Lambda (Python 3)  
- AWS EventBridge (Scheduling Automation)  
- AWS IAM (Identity Data Source)  
- AWS S3 (Evidence Storage)  
- AWS SNS (Compliance Notifications)  
- Boto3 (AWS SDK for Python)  

---

## 📈 Real-World Enterprise Use Cases

- Continuous IAM audit evidence generation  
- Access review support for quarterly audits  
- M&A compliance validation  
- Cloud access growth monitoring  
- Forensic evidence preservation  

---

## 🧭 Enterprise POC Value

This project is designed as a **realistic enterprise proof-of-concept** demonstrating how modern GRC teams can:

- Transition from manual to automated audit models  
- Support cloud-first business environments  
- Reduce compliance overhead while improving control assurance  

---

## 👤 Author

**Tywin Kalandyk**  
GRC Automation | Cloud Security | Compliance Engineering  




