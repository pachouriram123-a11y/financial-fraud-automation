I fixed the screenshot section so GitHub will actually display images. Copy this full README and replace your current one.

# 🚨 AI-Powered Fraud Monitoring & Alert Automation using n8n

<p align="center">
Automated Financial Fraud Detection • Risk Scoring • Workflow Automation • Email Alerts
</p>

---

# 📌 Project Overview

This project automates financial fraud monitoring using **n8n**, **Google Sheets**, **JavaScript**, and **Gmail**.

The workflow reads transaction records, applies fraud detection rules, calculates a risk score, classifies transaction risk level, updates the monitoring sheet automatically, and triggers email notifications for suspicious activity.

This project demonstrates a real-world fraud monitoring process commonly used in financial operations and risk management.

---

# 🎯 Objectives

* Automate fraud monitoring
* Detect suspicious transactions
* Generate real-time alerts
* Reduce manual review effort
* Improve operational efficiency

---

# 🏗 Solution Architecture

```text
Google Sheets
      ↓
Read Transactions
      ↓
n8n Workflow
      ↓
Fraud Rule Engine
      ↓
Risk Scoring
      ↓
Update Sheet
      ↓
Email Notifications
```

---

# ⚙ Workflow Process

### Step 1 — Extract Transaction Data

Read transaction records from Google Sheets.

### Step 2 — Execute Fraud Rules

Apply rule-based fraud detection.

### Step 3 — Calculate Risk Score

Generate fraud score.

### Step 4 — Update Dataset

Store:

* Rules Triggered
* Risk Score
* Fraud Status

### Step 5 — Send Alerts

Trigger automated notifications.

---

# 🧠 Fraud Detection Rules

| Rule | Description            |
| ---- | ---------------------- |
| R1   | High Value Transaction |
| R2   | Round Amount Detection |
| R3   | Micro Probe            |
| R4   | Impossible Travel      |
| R5   | Mule Account Pattern   |
| R6   | Off Hours Activity     |
| R7   | Dormant Account Spike  |
| R8   | First High Value       |
| R9   | Foreign Location       |
| R11  | UPI Abuse              |
| R12  | Cross Border Activity  |

---

# 📊 Risk Classification

| Risk Score | Status      |
| ---------- | ----------- |
| 0          | CLEAR       |
| 1          | LOW RISK    |
| 2–3        | MEDIUM RISK |
| 4+         | HIGH RISK   |

---

# 📸 Project Screenshots

## Fraud Monitoring Dataset

<img src="./screenshot/assetsgoogle-sheet.png.png" width="1000"/>

Shows:

* Transaction data
* Fraud status
* Risk score
* Triggered rules

---

## 🔴 High Risk Alert

<img src="./screenshot/assetshigh-risk-alert.png.png" width="1000"/>

Automated alert for high-risk transactions.

---

## 🟠 Medium Risk Alert

<img src="./screenshot/assetsmedium-risk-alert.png.png" width="1000"/>

Automated review notification.

---

## 🔄 n8n Workflow

<img src="./screenshot/n8n project.png" width="1000"/>

Workflow orchestration and fraud evaluation process.

---

# 🛠 Tech Stack

| Technology     | Purpose             |
| -------------- | ------------------- |
| n8n            | Workflow Automation |
| Google Sheets  | Data Storage        |
| JavaScript     | Fraud Rules         |
| Gmail          | Notifications       |
| Risk Analytics | Monitoring          |

---

# 📂 Repository Structure

```text
n8n/
│
├── README.md
│
├── screenshot/
│   ├── assetsgoogle-sheet.png.png
│   ├── assetshigh-risk-alert.png.png
│   ├── assetsmedium-risk-alert.png.png
│   └── n8n project.png
│
├── workflow/
│   └── Fraud monitoring data.json
```

---

# 🚀 Run Project

```bash
git clone <repository-url>
```

Open n8n → Import Workflow → Configure Credentials → Execute Workflow

---

# 📈 Future Improvements

* Machine Learning Detection
* Real-Time Monitoring
* Dashboard Integration
* API Connectivity
* Cloud Deployment

---

# 👨‍💻 Developed By

## Ram Pachori

MBA (Applied Finance)
Chitkara University

Fraud Analytics • Automation • Risk Monitoring

LinkedIn: *(Add Profile)*
GitHub: *(Add GitHub URL)*

---

### ⭐ If you found this project useful, consider giving it a star.

Then:

```bash
git add .
git commit -m "update readme screenshots"
git push
```

Refresh GitHub and screenshots should appear.
