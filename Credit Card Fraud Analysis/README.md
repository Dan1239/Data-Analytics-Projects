# Credit Card Fraud Risk Analysis

An interactive Power BI dashboard that analyzes credit card transaction data to identify fraud patterns, assess risk levels, and surface actionable insights for fraud prevention teams.

![Dashboard Theme](https://img.shields.io/badge/tool-Power%20BI-yellow) ![Status](https://img.shields.io/badge/status-active-brightgreen)

## 📊 Overview

This dashboard provides a consolidated view of fraudulent credit card activity across transaction categories, geographic states, fraud types, and time periods. It's designed to help fraud analysts and risk teams quickly spot high-risk patterns and prioritize investigations.

## ✨ Key Features

- **Dynamic Filter Panel** — Slice data by Fraud Type, State, and Merchant Name
- **KPI Summary Cards** — At-a-glance metrics including:
  - Fraud Rate %
  - Fraudulent Transaction Count
  - Critical Risk Transaction %
  - Total Fraudulent Transaction Amount
  - Top Fraud Type
- **Fraud Type × Category Breakdown** — Transaction amounts segmented by fraud type (e.g., Card Skimming) across categories like Apparel, E-commerce, Electronics, Food Delivery, Groceries, and Transportation
- **Risk Distribution Donut Chart** — Transaction amounts categorized into Critical, High, Medium, and Low risk tiers
- **Geographic Analysis** — Fraudulent transaction counts by state, highlighting hotspots (e.g., Kerala, Karnataka, Maharashtra)
- **Monthly Trend Analysis** — Time-series view of fraudulent transactions to identify seasonal spikes

## 🔍 Key Insights (Sample)

- Overall fraud rate stands at **25.84%**
- **54** transactions flagged as fraudulent, with **11.96%** classified as critical risk
- **Card Skimming** is the top fraud type by volume
- **Kerala, Karnataka, and Maharashtra** report the highest number of fraudulent transactions
- Fraud activity shows noticeable spikes in **May, July, and December**

## 🛠️ Tools & Technologies

- **Power BI** — Dashboard design and data visualization
- **DAX** — Calculated measures for KPIs and risk categorization
- **Power Query** — Data cleaning and transformation

## 📁 Repository Structure

```
├── data/                  # Raw and cleaned transaction datasets
├── dashboard.pbix         # Power BI dashboard file
├── screenshots/           # Dashboard preview images
└── README.md
```

## 🚀 Getting Started

1. Clone this repository
2. Open `dashboard.pbix` in Power BI Desktop
3. Refresh the data source if connected to a live dataset
4. Use the Filter Panel to explore fraud patterns by type, state, or merchant

## 📌 Use Cases

- Fraud detection and monitoring
- Risk prioritization for investigation teams
- Identifying geographic and category-based fraud hotspots
- Supporting data-driven fraud prevention strategies

## 📷 Preview
![image alt](https://github.com/Dan1239/Data-Analytics-Projects/blob/48bbf06b9dd1708b00314e07ebb8db34c565b7a8/Sales%20Analytics%20Project/FINAL%20-%20PowerBI%20Sales%20Dashboard_page-0001.jpg)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built to help visualize and understand credit card fraud patterns for smarter risk management.*
