# 📊 Marketing Campaign Performance Dashboard (Excel)

## 📌 Project Overview

This project focuses on transforming raw multi-channel marketing campaign data into an interactive Excel dashboard that delivers actionable business insights. The dashboard helps stakeholders evaluate campaign effectiveness, optimize ad spend, and improve ROI through data-driven decisions  

---

## 🧩 Business Context

Marketing teams invest heavily across platforms such as Google Ads and Facebook. However, raw campaign data alone does not provide value unless it is analyzed and visualized effectively. This project bridges that gap by converting campaign metrics into meaningful KPIs and visual dashboards for real-time performance tracking 

---

## 🎯 Business Objectives

* Track campaign performance across channels and regions
* Analyze profitability, efficiency, and Return on Ad Spend (ROAS)
* Monitor key KPIs such as CTR, CPC, Conversions, and ROAS
* Build an interactive Excel dashboard to support decision-making



---

## ❗ Problem Statement

Transform raw marketing campaign data into a comprehensive Excel dashboard using advanced Excel techniques, enabling stakeholders to identify underperforming channels and optimize marketing investments 

---

## 📁 Dataset Overview

* **Dataset Name:** Marketing_Campaign_Data.xlsx
* **Records:** 500 rows

### Key Columns

| Column      | Description                |
| ----------- | -------------------------- |
| Campaign_ID | Unique campaign identifier |
| Date        | Campaign activity date     |
| Channel     | Marketing platform         |
| Region      | Geographic region          |
| Budget ($)  | Allocated budget           |
| Spend ($)   | Actual spend               |
| Impressions | Number of ad views         |
| Clicks      | Number of ad clicks        |
| Conversions | Customer actions           |
| Revenue ($) | Revenue generated          |



---

## 🔄 Project Workflow

### 1. Data Understanding

* Reviewed dataset structure and data types
* Identified categorical vs numerical columns
* Understood campaign lifecycle

### 2. Data Cleaning & Preprocessing

* Removed duplicates
* Fixed date and currency formatting
* Checked and handled missing values

### 3. Data Transformation

Created calculated KPI columns:

* **CTR** = Clicks / Impressions
* **CPC** = Spend / Clicks
* **CPA** = Spend / Conversions
* **ROAS** = Revenue / Spend
* **Profit** = Revenue − Spend
* **Profit Margin %** = (Profit / Revenue) × 100

Also extracted **Year–Month** from the Date column for trend analysis 

---

## 📈 Dashboard Components

### Visualizations

* Spend vs Revenue trend over time
* Channel-wise ROAS (Bar Chart)
* Region-wise Conversions (Bar Chart)
* Budget allocation by channel (Pie Chart)
* Marketing funnel: Impressions → Clicks → Conversions

### Interactive Filters / Slicers

* Channel
* Region
* Date Range



---

## 🛠 Tools & Skills Used

* Microsoft Excel
* Data Cleaning & Preprocessing
* KPI Creation
* Pivot Tables
* Dashboard Design
* Business Analysis

---

## ✅ Key Outcomes

* Built an end-to-end Excel analytics solution
* Delivered clear visibility into campaign ROI and efficiency
* Identified high-performing channels and regions
* Enabled data-driven marketing optimization

---

## 📂 Repository Structure (Suggested)

```
📁 Marketing-Campaign-Performance-Dashboard
│── 📄 Marketing_Campaign_Data.xlsx
│── 📄 Cleaned_Data.xlsx
│── 📄 Pivot_Tables.xlsx
│── 📄 Final_Dashboard.xlsx
│── 📄 README.md
│── 📁 Screenshots
```

---

## 🚀 Future Enhancements

* Add automated refresh using Power Query
* Integrate Power BI for advanced visuals
* Include predictive analysis for future campaign performance

---

## 👤 Author

**A Vikash**
