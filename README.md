```

## 🚀 Future Roadmap
* **Machine Learning Integration:** Moving from rule-based to predictive scoring using regression models.
* **Notification Expansion:** Integrating WhatsApp Business API and Slack for instant SOC alerts.
* **Regulatory Compliance:** Automating RBI/FEMA reporting formats for direct regulatory submission.

## 👨‍💻 Author
**Rohit Pachouri**
IPM Student | Finance & BusinessTo create a professional GitHub presence, I have refined your README into a clean, technical documentation format. Per your request, the screenshots have been referenced in the code structure but are not rendered as images in the display.
```markdown
# Financial Fraud Detection & Risk Scoring Automation

An enterprise-grade automation workflow built with **n8n**, **Google Sheets**, and **Gmail API** designed to perform real-time transaction risk scoring and fraud classification for financial institutions.

## 📌 Executive Summary
In high-volume digital banking environments, manual fraud review is often a bottleneck that increases operational risk. This project implements a **Rule-Based Risk Engine** that automates the transition from "End-of-Day" batch processing to "Real-Time" proactive monitoring.

### Key Objectives
* **Scalability:** Handle thousands of transactions without increasing analyst headcount.
* **Accuracy:** Utilize a 12-point heuristic scoring model to identify suspicious patterns.
* **Auditability:** Generate a continuous, immutable log within Google Sheets for compliance.

## 🏗️ Technical Architecture
The system follows a modular pipeline to ensure data integrity and low latency:

1.  **Ingestion:** Real-time triggers pull transaction data from Google Sheets.
2.  **Processing:** A custom JavaScript engine evaluates the data against predefined fraud heuristics.
3.  **Classification:** Logic gates categorize transactions based on cumulative risk scores.
4.  **Action:** Instant multi-channel alerts (Gmail) are triggered for high-risk anomalies, while low-risk events are logged silently.

## 🛡️ Detection Model (Heuristic Rules)
The engine evaluates each transaction against a weighted scoring system, including:

| Rule ID | Logic Description |
| :--- | :--- |
| **R1 & R8** | High Value & First-Time High Value Transactions (> ₹50,000) |
| **R2 & R3** | Round Amount Detection and Micro-Probe (Testing) Patterns |
| **R4 & R5** | Velocity Breaches and Known "Mule Account" Transaction Behaviors |
| **R6 & R7** | Temporal Anomalies: Off-Hours Trading and Dormant Account Spikes |
| **R9 - R12** | Geographic & Structural Risks: Unknown Locations and Cross-Border Splits |

## 📊 Performance Benchmarks
| Metric | Manual Review | n8n Automated Workflow |
| :--- | :--- | :--- |
| **Latency** | 3–4 Hours | **16.8 Seconds** |
| **Intervention** | 100% Manual | **Zero (Exception-based only)** |
| **Monitoring** | Reactive | **Real-Time / Proactive** |

## 📂 Repository Structure
```text
fraud-detection-n8n/
├── workflow/
│   └── fraud-monitoring-data.json      # n8n Workflow Export
├── assets/                             # Documentation Assets
│   ├── n8n project.png                 # Workflow Schematic
│   ├── google-sheet.png                # Monitoring Dashboard
│   ├── high-risk-alert.png             # Alert Template (High)
│   └── medium-risk-alert.png           # Alert Template (Medium)
├── README.md                           # Project Documentation
└── LICENSE

```

## 🚀 Future Roadmap

* **Machine Learning Integration:** Moving from rule-based to predictive scoring using regression models.
* **Notification Expansion:** Integrating WhatsApp Business API and Slack for instant SOC alerts.
* **Regulatory Compliance:** Automating RBI/FEMA reporting formats for direct regulatory submission.

## 👨‍💻 Author

**Rohit Pachouri**
IPM Student | Finance & Business Analytics
Chitkara University
[LinkedIn Profile](https://www.google.com/search?q=https://www.linkedin.com/in/rohitpachori)

```


```
