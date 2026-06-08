Here are the instructions to set up your repository structure, followed by the complete, production-ready `README.md` code block.

### 📁 Step 1: Directory Setup

Create a folder named `assets` in your repository root directory and save your screenshots using these exact filenames:

* Save your uploaded n8n workflow screenshot as: `assets/n8n-workflow.png`
* Save your Google Sheets dashboard screenshot as: `assets/google-sheet.png`
* Save your high-risk email alert screenshot as: `assets/high-risk-alert.png`
* Save your medium-risk email alert screenshot as: `assets/medium-risk-alert.png`

---

### 📝 Step 2: Copy into `README.md`

```markdown
# 🚀 AI-Powered Financial Fraud Detection using n8n

Automated fraud monitoring workflow built with n8n, Google Sheets, and Gmail to perform real-time transaction risk scoring, fraud classification, and alert generation.

## 📌 Project Overview
Financial institutions process thousands of digital transactions daily. Manual fraud review is slow, error-prone, and difficult to scale. 

This project automates fraud detection using a rule-based risk scoring engine that:
* Analyzes transactions in real time
* Applies fraud detection rules
* Calculates risk scores
* Classifies transactions into risk categories
* Sends automated alerts
* Maintains an audit trail in Google Sheets

## 🎯 Key Features
* **Real-time transaction monitoring**
* **Automated fraud risk scoring** with 12 comprehensive detection rules
* **Dynamic risk classification** (High, Medium, Low & Clear)
* **Instant Gmail alerts** for high and medium-risk activities
* **Google Sheets integration** for a structured, real-time audit trail
* **Low-code implementation** leveraging the speed and scalability of n8n

---

## 🏗️ Technology Stack

| Technology | Purpose |
| :--- | :--- |
| **n8n** | Workflow Automation Engine |
| **Google Sheets** | Transaction Data Storage & Audit Log |
| **JavaScript** | Fraud Detection Logic & Risk Engine Execution |
| **Gmail API** | Automated Alert Notifications |
| **JSON** | Workflow Configuration & Export |

---

## 🔄 Workflow Architecture


```

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

| Rule ID | Description |
| :--- | :--- |
| **R1** | High Value Transaction (> ₹50,000) |
| **R2** | Round Amount Detection |
| **R3** | Micro Probe Transaction |
| **R4** | Velocity Breach |
| **R5** | Mule Account Pattern |
| **R6** | Off-Hours Transaction |
| **R7** | Dormant Account Spike |
| **R8** | First High Value Transaction |
| **R9** | Foreign/Unknown Location |
| **R11** | UPI Abuse Detection |
| **R12** | Cross-Border Split Pattern |

---

## 📊 Risk Classification

| Risk Score | Status | Action |
| :--- | :--- | :--- |
| **0** | CLEAR | Auto Approve |
| **1** | LOW RISK | Log & Monitor |
| **2–3** | MEDIUM RISK | Email Alert |
| **4+** | HIGH RISK | Escalate & Alert |

---

## 📈 Business Impact

| Metric | Manual Process | Automated Process |
| :--- | :--- | :--- |
| **Processing Time** | 3–4 Hours | **16.8 Seconds** |
| **Human Effort** | 1–2 Analysts | **Zero** |
| **Detection Speed** | End of Day | **Real-Time** |
| **Audit Trail** | Limited | **Automated** |
| **Alerts** | Manual | **Instant** |

### 📊 Batch Results Summary
* **55** Transactions Processed
* **14** High Risk Transactions Identified
* **15** Medium Risk Transactions Identified
* **11** Low Risk Transactions Logged
* **15** Clear Transactions Approved
* **29** Automated Email Alerts Generated

---

## 📸 Screenshots

### n8n Workflow Automation Backend
![n8n Workflow Automation Backend](assets/n8n-workflow.png)

### Google Sheets Risk Monitoring Dashboard
![Google Sheets Risk Monitoring Dashboard](assets/google-sheet.png)

### High Risk Alert Email
![High Risk Alert Email](assets/high-risk-alert.png)

### Medium Risk Alert Email
![Medium Risk Alert Email](assets/medium-risk-alert.png)

---

## 📂 Repository Structure

```text
fraud-detection-n8n/
│
├── workflow/
│   └── fraud-monitoring-data.json
│
├── assets/
│   ├── n8n-workflow.png
│   ├── google-sheet.png
│   ├── high-risk-alert.png
│   └── medium-risk-alert.png
│
├── README.md
└── LICENSE

```

---

## 🚀 Future Enhancements

* [ ] Machine Learning-based Predictive Fraud Scoring
* [ ] WhatsApp Business API Alert Integration
* [ ] Interactive Power BI Dashboard for Executives
* [ ] Direct Core Banking System (CBS) Integration
* [ ] Automated RBI/FEMA Compliance Monitoring & Reporting

---

## 👨‍💻 Author

**Rohit Pachouri**
*IPM Student | Finance & Business Analytics*
Chitkara University
🔗 [LinkedIn](https://www.google.com/search?q=https://www.linkedin.com/in/rohitpachori)

---

### ⭐ Project Highlights

This project demonstrates how low-code automation can transform modern fraud monitoring by reducing operational review times from hours to seconds while providing uncompromised visibility, instantaneous alerting capabilities, and a fully scalable audit framework for financial institutions.

```

```
