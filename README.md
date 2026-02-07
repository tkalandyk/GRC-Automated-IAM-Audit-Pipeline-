# 📊 GRC Automated IAM Audit Pipeline  
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

