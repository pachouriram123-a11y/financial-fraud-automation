# 🚀 AI-Powered Financial Fraud Detection using n8n

Automated fraud monitoring workflow built with **n8n**, **Google Sheets**, and **Gmail** to perform real-time transaction risk scoring, fraud classification, and alert generation.

## 📌 Project Overview

Financial institutions process thousands of digital transactions daily. Manual fraud review is slow, error-prone, and difficult to scale.

This project automates fraud detection using a rule-based risk scoring engine that:

* Analyzes transactions in real time
* Applies fraud detection rules
* Calculates risk scores
* Classifies transactions into risk categories
* Sends automated alerts
* Maintains an audit trail in Google Sheets

---

## 🎯 Key Features

✅ Real-time transaction monitoring

✅ Automated fraud risk scoring

✅ 12 fraud detection rules

✅ High, Medium, Low & Clear risk classification

✅ Automated Gmail alerts

✅ Google Sheets integration

✅ Structured audit trail

✅ Low-code implementation using n8n

---

## 🏗️ Technology Stack

| Technology    | Purpose                  |
| ------------- | ------------------------ |
| n8n           | Workflow Automation      |
| Google Sheets | Transaction Data Storage |
| JavaScript    | Fraud Detection Logic    |
| Gmail API     | Alert Notifications      |
| JSON          | Workflow Configuration   |

---

## 🔄 Workflow Architecture

```text
Google Sheets
       │
       ▼
Read Transactions
       │
       ▼
JavaScript Risk Engine
       │
       ▼
Fraud Rule Evaluation
       │
       ▼
Risk Score Calculation
       │
       ▼
Risk Classification
       │
 ┌─────┼─────┐
 ▼     ▼     ▼
High  Medium Low/Clear
Risk   Risk
 ▼      ▼
Email  Email
Alert  Alert
```

---

## 🛡️ Fraud Detection Rules

| Rule ID | Description                        |
| ------- | ---------------------------------- |
| R1      | High Value Transaction (> ₹50,000) |
| R2      | Round Amount Detection             |
| R3      | Micro Probe Transaction            |
| R4      | Velocity Breach                    |
| R5      | Mule Account Pattern               |
| R6      | Off-Hours Transaction              |
| R7      | Dormant Account Spike              |
| R8      | First High Value Transaction       |
| R9      | Foreign/Unknown Location           |
| R11     | UPI Abuse Detection                |
| R12     | Cross-Border Split Pattern         |

---

## 📊 Risk Classification

| Risk Score | Status      | Action           |
| ---------- | ----------- | ---------------- |
| 0          | CLEAR       | Auto Approve     |
| 1          | LOW RISK    | Log & Monitor    |
| 2–3        | MEDIUM RISK | Email Alert      |
| 4+         | HIGH RISK   | Escalate & Alert |

---

## 📈 Business Impact

| Metric          | Manual Process | Automated Process |
| --------------- | -------------- | ----------------- |
| Processing Time | 3–4 Hours      | 16.8 Seconds      |
| Human Effort    | 1–2 Analysts   | Zero              |
| Detection Speed | End of Day     | Real-Time         |
| Audit Trail     | Limited        | Automated         |
| Alerts          | Manual         | Instant           |

### Results

* 55 Transactions Processed
* 14 High Risk Transactions
* 15 Medium Risk Transactions
* 11 Low Risk Transactions
* 15 Clear Transactions
* 29 Automated Email Alerts Generated

---

## 📸 Screenshots

### Google Sheets Risk Monitoring Dashboard

![Google Sheet Dashboard](assets/google-sheet.png)

---

### High Risk Alert Email

![High Risk Alert](assets/high-risk-alert.png)

---

### Medium Risk Alert Email

![Medium Risk Alert](assets/medium-risk-alert.png)

---

## 📂 Repository Structure

```text
fraud-detection-n8n/
│
├── workflow/
│   └── fraud-monitoring-data.json
│
├── assets/
│   ├── google-sheet.png
│   ├── high-risk-alert.png
│   └── medium-risk-alert.png
│
├── README.md
└── LICENSE
```

---

## 🚀 Future Enhancements

* Machine Learning-based Fraud Detection
* Predictive Fraud Scoring
* WhatsApp Alert Integration
* Power BI Dashboard
* Core Banking System Integration
* RBI/FEMA Compliance Monitoring

---

## 👨‍💻 Author

**Rohit Pachouri**
IPM Student | Finance & Business Analytics
Chitkara University

🔗 LinkedIn: [www.linkedin.com/in/rohitpachori](http://www.linkedin.com/in/rohitpachori)

---

## ⭐ Project Highlights

This project demonstrates how low-code automation can transform fraud monitoring by reducing review time from hours to seconds while providing real-time visibility, automated alerts, and a scalable audit framework for financial institutions.
