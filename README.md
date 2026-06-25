# 🏦 Zephyr Bank H1 2026 | Transaction Health Dashboard

A 4-page interactive Power BI dashboard analyzing 1,500+ digital transactions for a fictional UK neobank — uncovering fraud exposure, revenue leakage, operational failures, and customer risk across January–May 2026 | Onyx Data #dataDNA Challenge June 2026

---

## 📌 Short Description / Purpose

The Zephyr Bank Transaction Health Dashboard is a comprehensive analytical Power BI report designed to monitor and investigate the digital transaction pipeline of a UK-based fintech neobank. Built as part of the **Onyx Data #dataDNA Challenge — June 2026**, this dashboard delivers actionable insights across four critical business dimensions: operational efficiency, fraud & risk exposure, customer segment behaviour, and revenue integrity.

The tool is intended for use by **Risk teams, Finance teams, Product managers, and Compliance officers** who need a consolidated, data-driven view of transaction health to prioritize investigations, recover lost revenue, and reduce fraud exposure.

---

## 🛠️ Tech Stack

The dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** – Main data visualization platform used for report creation
- 📂 **Power Query** – Data transformation and cleaning layer for reshaping and preparing raw transaction data
- 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures, KPIs, conditional formatting logic and dynamic visuals
- 📝 **Data Modeling** – Relationships established among dimension tables (customers, transaction types, merchant categories) and fact table (transactions) to enable cross-filtering and aggregation
- 📁 **File Format** – `.png` for dashboard previews

---

## 📂 Data Source

**Source:** Onyx Data #dataDNA Challenge — June 2026

The dataset covers **~1,500 individual digital transactions** spanning **January 2026 to May 2026** across three interlinked dimensions:

| Table | Description |
|---|---|
| **dim_customers** | Customer demographics, KYC status, region, segment, tenure |
| **dim_transaction_type** | Channel, fee metadata, domestic/international flag |
| **dim_merchant_category** | Merchant sector and risk classification |
| **fact_transactions** | Individual transactions with amount, status, fraud flags, fees |

---

## ✨ Features / Highlights

### 🔴 Business Problem

Zephyr Bank operates entirely digitally — all transactions flow through its mobile app, web browser, or automated payment rails. Leadership needed answers to three critical questions:

- Where are we **losing revenue?**
- Where are we **exposed to fraud?**
- Where are we **failing operationally?**

Key challenges included:
- Fraud patterns skewing towards digital channels
- FX fees representing a meaningful revenue lever
- High transaction failure rates creating operational and financial risk
- Customer segments behaving very differently across channels

---

### 🎯 Goal of the Dashboard

To deliver an interactive 4-page Power BI report that:

- Monitors transaction health across all digital channels
- Identifies fraud hotspots by customer, merchant, and region
- Quantifies fee revenue and detects leakage
- Supports Risk, Finance, Product and Compliance decision-making

---

### 💡 Business Impact & Findings

| Finding | Impact |
|---|---|
| 🚨 **80% settlement failure rate** | Critical payment rail issue requiring immediate audit |
| 💰 **£1.19M fraud exposure** | Concentrated in 4 accounts — freeze and SAR required |
| 📊 **20% fraud rate across GPV** | Direct threat to customer trust and regulatory standing |
| ⚠️ **63% GPV from Premium segment** | Dangerous revenue concentration risk |
| 🌍 **60% fraud rate in London** | Geographic concentration requiring enhanced controls |
| 💸 **-£0.17 fee leakage** | Revenue recovery opportunity in transfer transactions |
| 🏦 **Only 15% completion rate** | 2.6p settles per £1 attempted — systemic failure |
| 🔐 **100% fraud from KYC-verified accounts** | Inverted risk signal — KYC model needs recalibration |

### 💡 Insights & Recommendations

##Operations & Revenue

#CriticalProcessingFailure: Only 15% of transactions complete, with just 2.6p settled per £1 attempted.
#RevenueLeakage: £0.17M in lost fees due to fee-calculation issues and Premium waivers.

##Fraud Concentration

#FraudConcentration: £1.19M fraud exposure, with 59% linked to one customer and 98% concentrated in London.
#PremiumSegmentRisk: Premium customers drive 63% of portfolio value and most of the fraud exposure.

##Risk & KYC Controls

#RiskModelMismatch: Fraud is concentrated in Fuel & Gambling, not in current high-risk categories.
#KYCControlGap: 100% of fraud originates from verified accounts, indicating gaps in KYC-based risk logic.

##High-Risk Customers

#LargestSingleExposure: One fraud-flagged crypto transaction equals £112K exposure (highest single risk).
#CustomerConcentrationRisk: 30% of customers hold 63% of portfolio value, increasing systemic risk.

##Data & Channel Performance

#DataQualityIssue: 80% of failed transactions (900–1,200) are labeled "Unknown", blocking root-cause analysis.
#ATMChannelFailure: ATM channel failure rate is 63%, the highest across all channels.

---

## 📸 Screenshots

### Page 1 — Overview
![Overview](https://github.com/Payal281119/zephyr-bank-transaction-health-dashboard/blob/main/Overview%20Page.png)

### Page 2 — Risk & Fraud
![Risk & Fraud](https://github.com/Payal281119/zephyr-bank-transaction-health-dashboard/blob/main/Risk%20Page.png)

### Page 3 — Customer & Segment
![Customer](https://github.com/Payal281119/zephyr-bank-transaction-health-dashboard/blob/main/Customer%20Page.png)

### Page 4 — Operations
![Operations](https://github.com/Payal281119/zephyr-bank-transaction-health-dashboard/blob/main/Operations%20Page.png)

---


## 👤 Author

**Payal Sahu**
Data Analyst | SQL | Power BI | Python | Excel
📍 Pune, Maharashtra
🔗 [LinkedIn](www.linkedin.com/in/payal-sahu-7972b48a)

---

## 🏆 Challenge

Built for **Onyx Data #dataDNA Challenge — June 2026**

🔗 [Onyx Data LinkedIn](https://www.linkedin.com/company/onyxdata/)

---

⭐ *If you found this project useful, please star the repository!*
