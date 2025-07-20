
# 📊 Swiggy Web Traffic & Conversion Dashboard

Welcome to the **Swiggy Web Analytics Project**, a data-driven exploration into how users interact with Swiggy's platform and how bot activity can distort meaningful KPIs. This project is built using Tableau and provides two comprehensive dashboards to help the marketing team make **data-backed decisions**.

---

## 🎯 Objective

- 📉 Identify and filter out **bot traffic** that inflates performance metrics.
- 👥 Understand **real user behavior**—session patterns, bounce rates, device differences.
- 📈 Drive **conversion improvements** by aligning strategies with actual user behavior.
- 🧠 Provide **clear insights** for Swiggy's marketing and product teams.

---

## 🧩 Dashboards Overview

### 🛡️ 1. Bot Activity Analysis

Helps detect abnormal traffic (likely bots) by analyzing:

- 📊 Campaign-wise New vs Returning traffic
- 🧪 Bot % based on device and browser (Chrome + Mobile prone to bots)
- 🧭 Entry = Exit page + Zero Duration → suspicious behavior
- 🥧 Pie charts: Bots vs Real Users by Landing Page

### 👥 2. User Behavior Analysis

Dives into engagement patterns of genuine users:

- 📈 Session trends over time
- ⏱️ Avg. Session Duration by Source
- 🔄 New vs Returning users (loyalty measure)
- 🌍 Geo analysis (states like Maharashtra, Karnataka)
- 📊 Channel performance: Paid vs Direct

---

## 📌 Key KPIs Tracked

| KPI | Description |
|-----|-------------|
| **Sessions** | Total user visits to the platform |
| **% of Bots** | Ratio of suspected bot sessions |
| **Bounce Rate** | Users who left after one page |
| **Conversion Rate** | Successful transactions per session |
| **Avg. Session Duration** | Time users spend on the platform |
| **Device/OS/Browser** | Technical engagement metrics |
| **Campaign Source** | Performance across marketing efforts |

---

## 🧠 Hypotheses Tested

| ID | Hypothesis |
|----|------------|
| **H1** | OS/Browser differences impact user retention |
| **H2** | New users bounce more often than returners |
| **H3** | Bots inflate sessions with short durations |
| **H4** | Conversion linked to source + session time |
| **H5** | Some campaigns bring traffic, not conversions |
| **H6** | City-wise growth reveals targeting potential |
| **H9** | Bot spikes occur via Chrome during peak traffic |

---

## 🗂️ Repository Structure

```
swiggy-dashboard/
├── data/
│   └── [DAF] - Tableau milestone data.csv
├── dashboard/
│   └── Final Dashboard.twb
├── docs/
│   └── Swiggy_Project_Outline.docx
└── README.md
```
---
## 🛠️ Tools Used

- 📊 **Tableau** – Visualization and storytelling
- 🧾 **Excel/CSV** – Data cleanup
- 💻 **GitHub** – Version control & documentation

---

## 🙋‍♂️ Author

Ansh Jain

Fellow – NextLeap Data Analyst Program  
Gmail:anshjain14092004@gmail.com
