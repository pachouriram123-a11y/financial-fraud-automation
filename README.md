# 🚨 AI-Powered Fraud Monitoring & Alert Automation using n8n

<p align="center">
Automated Financial Fraud Detection • Risk Scoring • Email Alerting
</p>

---

## 📌 Project Overview

This project automates the detection and monitoring of suspicious financial transactions using **n8n**, **Google Sheets**, and **Gmail Alerts**.

The workflow reads transaction data, evaluates fraud conditions using predefined business rules, calculates a risk score, classifies transaction risk level, updates the monitoring sheet, and automatically sends alerts for suspicious activity.

This project simulates a modern fraud monitoring pipeline used in financial operations and risk management.

---

# 🎯 Objectives

- Automate fraud monitoring
- Reduce manual transaction review
- Detect high-risk transactions instantly
- Trigger automated email alerts
- Improve operational efficiency
- Demonstrate AI + Workflow Automation concepts

---

# 🏗 Solution Architecture

```text
Google Sheets
      ↓
Transaction Read
      ↓
n8n Workflow
      ↓
JavaScript Rule Engine
      ↓
Risk Scoring
      ↓
Status Classification
      ↓
Update Dataset
      ↓
Email Alert System
```

---

# ⚙ Workflow Process

### Step 1 — Read Transaction Dataset
Import transaction records from Google Sheets.

### Step 2 — Execute Fraud Logic
Evaluate transactions using fraud rules.

### Step 3 — Generate Risk Score
Assign risk based on triggered indicators.

### Step 4 — Update Dataset
Store:
- Triggered Rules
- Risk Score
- Fraud Status

### Step 5 — Send Alerts
Generate automated notifications.

---

# 🧠 Fraud Detection Rules

| Rule | Detection Logic |
|------|----------------|
| R1 | High Value Transaction |
| R2 | Round Amount Detection |
| R3 | Micro Pattern |
| R4 | Impossible Travel |
| R5 | Mule Account Pattern |
| R6 | Off Hours Activity |
| R7 | Dormant Account Spike |
| R8 | First High Value |
| R9 | Foreign Location |
| R11 | UPI Abuse |
| R12 | Cross Border Activity |

---

# 📊 Risk Classification

| Risk Score | Status |
|-----------|--------|
| 0 | Clear |
| 1 | Low Risk |
| 2–3 | Medium Risk |
| 4+ | High Risk |

---

# 📸 Project Screenshots

## 1. Fraud Monitoring Dataset

Create folder:

```text
assets/
```

Save your Google Sheet screenshot as:

```text
assets/fraud-monitoring-sheet.png
```

Add:

```md
![Fraud Monitoring Dataset](assets/fraud-monitoring-sheet.png)
```

---

## 2. High Risk Email Alert

Save:

```text
assets/high-risk-alert.png
```

Add:

```md
![High Risk Alert](assets/high-risk-alert.png)
```

---

## 3. Medium Risk Email Alert

Save:

```text
assets/medium-risk-alert.png
```

Add:

```md
![Medium Risk Alert](assets/medium-risk-alert.png)
```

---

## 4. n8n Workflow Automation

Save:

```text
assets/n8n-workflow.png
```

Add:

```md
![Workflow Architecture](assets/n8n-workflow.png)
```

---

# 🛠 Tech Stack

| Technology | Purpose |
|-----------|---------|
| n8n | Workflow Automation |
| Google Sheets | Data Storage |
| JavaScript | Fraud Logic |
| Gmail | Notifications |
| Risk Analytics | Monitoring |

---

# 📂 Repository Structure

```text
fraud-monitoring-automation/
│
├── README.md
├── workflow/
│     └── workflow.json
│
├── assets/
│     ├── fraud-monitoring-sheet.png
│     ├── high-risk-alert.png
│     ├── medium-risk-alert.png
│     └── n8n-workflow.png
│
└── docs/
```

---

# 🚀 Run Locally

### Clone Repository

```bash
git clone <repository-url>
```

### Import Workflow

```bash
Open n8n
→ Import Workflow
→ Configure Credentials
→ Execute Workflow
```

---

# 📈 Future Improvements

- Machine Learning Risk Scoring
- Real-Time Fraud Detection
- Dashboard Integration
- API Connectivity
- WhatsApp Alerts
- Cloud Deployment

---

# 👨‍💻 Developed By

## Ram Pachori

MBA (Applied Finance)  
Chitkara University  

AI • Workflow Automation • Fraud Analytics • Risk Monitoring

LinkedIn: *(Add your profile)*  
GitHub: *(Add your GitHub link)*

---

## ⭐ If you found this project useful, give it a star.
