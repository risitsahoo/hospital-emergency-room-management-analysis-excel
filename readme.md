# 🏥 Hospital Emergency Room Analytics - Healthcare

### Excel Data Analytics Portfolio Project | 9,216 Patient Records | Apr 2023 – Oct 2024

> **An end-to-end Excel analytics project** transforming Emergency Room patient records into actionable KPIs, operational trends, dashboard reporting, data-quality insights, and business recommendations.

[![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?logo=microsoftexcel&logoColor=white)](#-tools--techniques)
[![Records](https://img.shields.io/badge/Records-9%2C216-blue)](#-dataset-overview)
[![Period](https://img.shields.io/badge/Period-Apr%202023--Oct%202024-orange)](#-dataset-overview)
[![Portfolio](https://img.shields.io/badge/Project-Portfolio-success)](#-project-overview)

---

## 📑 Table of Contents

- [📌 Project Overview](#-project-overview)
- [❗ Business Problem](#-business-problem)
- [🎯 Business Objectives](#-business-objectives)
- [🗂️ Dataset Overview](#dataset-overview-custom)
- [🛠️ Tools & Techniques](#tools-techniques-custom)
- [🧹 Data Preparation](#-data-preparation)
- [⚙️ Analytical Workflow](#analytical-workflow-custom)
- [📊 Dashboard](#-dashboard)
- [📈 Key Performance Indicators](#-key-performance-indicators)
- [🔎 Key Insights](#-key-insights)
- [💡 Business Recommendations](#-business-recommendations)
- [📁 Repository Structure](#-repository-structure)
- [🚀 How to Run](#how-to-run-custom)
- [⚠️ Data Quality & Limitations](#data-quality-limitations-custom)
- [📄 Detailed Reports](#-detailed-reports)
- [🏁 Conclusion](#-conclusion)
- [📬 Contact](#-contact)
- [⭐ Project Highlights](#-project-highlights)

---

## 📌 Project Overview

This individual portfolio project demonstrates a practical **data analysis and operational reporting workflow using Microsoft Excel**.

The project analyzes **9,216 unique Emergency Room records** across **19 monthly reporting periods**, focusing on:

- Patient demand and volume trends
- Admission outcomes
- Waiting-time performance
- >30-minute delay rates
- Patient satisfaction
- Demographic segmentation
- Department referral patterns
- Data quality
- KPI and dashboard reporting

### 🎯 Portfolio Goal

Demonstrate the ability to take a raw dataset, **clean and structure the data, define meaningful KPIs, identify operational patterns, build a management-style dashboard, and translate findings into business recommendations.**

---

## ❗ Business Problem

Emergency Room data contains valuable operational information, but raw patient-level records do not immediately provide a clear view of workload, waiting-time pressure, admission outcomes, or data-quality issues.

This project addresses questions such as:

- How does patient volume change over time?
- What proportion of encounters result in admission?
- How often do patients wait more than 30 minutes?
- Which periods show higher waiting-time pressure?
- What does the available satisfaction data indicate?
- What demographic and referral patterns are visible?
- What limitations should be considered before interpreting the results?

---

## 🎯 Business Objectives

- Analyze patient volume across the project period
- Track monthly operational performance
- Measure admission and non-admission outcomes
- Evaluate waiting time and delay performance
- Analyze patient satisfaction and response coverage
- Explore demographic and referral patterns
- Build management-oriented KPIs and dashboard reporting
- Identify important data-quality limitations
- Convert analytical findings into practical recommendations

---

<a id="dataset-overview-custom"></a>
## 🗂️ Dataset Overview

**Source:** Publicly sourced Kaggle Emergency Room dataset.

| Metric | Value |
|---|---:|
| Total Records | **9,216** |
| Unique Patient IDs | **9,216** |
| Reporting Period | **Apr 2023 – Oct 2024** |
| Monthly Periods | **19** |
| Wait-Time Range | **10–60 min** |
| Satisfaction Responses | **2,517 (27.3%)** |
| Missing Department Referral | **5,400 (58.6%)** |

### Core Fields

`Patient ID` · `Admission Date` · `Gender` · `Age` · `Race` · `Department Referral` · `Admission Flag` · `Satisfaction Score` · `Waittime`

---

<a id="tools-techniques-custom"></a>
## 🛠️ Tools & Techniques

**Primary Tool:** Microsoft Excel

- Excel Tables / structured data
- Data cleaning and validation
- Formula-based KPI calculations
- Conditional logic
- Monthly aggregation
- Pivot-style analysis
- Time-series analysis
- Segmentation
- Charts and visual reporting
- Dashboard development
- Data-quality assessment
- Business interpretation

> **Scope:** This project is intentionally documented as an **Excel-based analysis**. SQL, Python, and Power BI are not claimed as tools used for this project.

---

## 🧹 Data Preparation

- Validated structure, field names, data types and date coverage
- Standardized admission dates
- Validated Patient ID uniqueness
- Normalized gender values
- Converted analytical fields to appropriate numeric types
- Created age groups from **0–9 through 70–79**
- Created monthly reporting periods
- Classified waiting time as **Delay (>30 min)** or **On-time (≤30 min)**
- Retained missing referrals as **No Department Referral**
- Excluded blank satisfaction scores from satisfaction averages rather than treating them as zero

---

<a id="analytical-workflow-custom"></a>
## ⚙️ Analytical Workflow

```text
Raw Data
   ↓
Validation & Cleaning
   ↓
Transformation
   ↓
Monthly Aggregation
   ↓
KPI Calculation
   ↓
Trend & Segment Analysis
   ↓
Dashboard
   ↓
Business Insights
   ↓
Recommendations
```

### Analysis Areas

**Operational:** Patient volume · Wait time · Delay performance · Admission outcomes

**Patient Experience:** Satisfaction · Response coverage

**Segmentation:** Age · Gender · Race · Referral · Admission · Delay status

---

## 📊 Dashboard

The Excel dashboard provides a **monthly operational reporting view** with year/month navigation.

**Includes:**
- Patient Volume
- Average Wait Time
- Patient Satisfaction
- Admission Status
- Age Group Distribution
- Department Referral
- Delay vs On-Time Performance
- Gender Distribution
- Year / Month Selectors

![Hospital Emergency Room Dashboard](hospital_emergency_room_management_Analysis_Dashboard_images/Hospital%20Management%20Excel%20Project%20Image.png)

### 📊 Supporting Trend Analysis

![Average Wait Time Trend](hospital_emergency_room_management_Analysis_Dashboard_images/Avg%20Wait%20Time%20Trend.png)

![Daily Number of Patients Trend](hospital_emergency_room_management_Analysis_Dashboard_images/Daily%20No%20of%20Patient%20Trend.png)

![Patient Satisfaction Trend](hospital_emergency_room_management_Analysis_Dashboard_images/Patient%20satisfaction%20trend.png)

> **Dashboard purpose:** provide a concise management view of workload, service-time performance, patient experience, and patient segmentation.

---

## 📈 Key Performance Indicators

| KPI | Result |
|---|---:|
| **Total Patients** | **9,216** |
| **Admission Rate** | **50.04%** |
| **Average Wait Time** | **35.26 min** |
| **Median Wait Time** | **35 min** |
| **Delay Rate (>30 min)** | **59.32%** |
| **On-Time Rate (≤30 min)** | **40.68%** |
| **Average Satisfaction** | **4.99 / 10** |
| **Satisfaction Coverage** | **27.3%** |

**Definitions:** Admission Rate = admitted ÷ total; Delay Rate = wait >30 min ÷ total; On-Time Rate = wait ≤30 min ÷ total; Satisfaction = mean of non-blank scores.

---

## 🔎 Key Insights

### ⏱️ Waiting-Time Performance
**59.32%** of encounters exceeded the 30-minute threshold.

- Average wait: **35.26 min**
- Median wait: **35 min**
- Delayed encounters: **5,467**
- On-time encounters: **3,749**

### 📅 Monthly Performance

| Metric | Period | Result |
|---|---|---:|
| Highest Avg. Wait | Feb 2024 | **36.67 min** |
| Lowest Avg. Wait | Oct 2024 | **34.05 min** |
| Highest Delay Rate | Feb 2024 | **65.66%** |
| Lowest Delay Rate | Sep 2023 | **54.80%** |

### 👥 Patient Demand
Monthly volume ranged from **431 to 530 patients**.

### 🏥 Admission Outcomes
**4,612 admitted (50.04%)** vs **4,604 non-admitted (49.96%)**.

### 😊 Satisfaction
Average recorded satisfaction was **4.99 / 10**, based on **2,517 responses (27.3%)**. This limited coverage should be considered when interpreting the KPI.

### 📋 Referral Data
**5,400 records (58.6%)** had no department referral, making referral completeness an important data-quality consideration.

---

## 💡 Business Recommendations

1. **Waiting-Time Monitoring** — Track >30-minute delay rates and investigate sustained elevated periods.
2. **Demand & Capacity Planning** — Use patient-volume trends to identify higher-demand periods.
3. **Referral Data Quality** — Standardize referral capture and apply validation rules.
4. **Satisfaction Data Collection** — Improve consistency of satisfaction-score collection.
5. **Exception Reporting** — Flag high-volume, high-delay or low-satisfaction periods.
6. **Dashboard Drill-Down** — Filter by date, age, department, admission and delay status.

---

## 📁 Repository Structure

```text
Hospital-Emergency-Room-Analytics/
│  
├── 🗂️ hospital_emergency_room_management_Analysis_data (.xlsx)                      # Project dataset
├── 📊 hospital_emergency_room_management_Analysis_Dashboard (.xlsx)                 # project dashboard
├── 📄 hospital_emergency_room_management_Analysis_Full_Period_Report (.pdf)         # Detailed project report        
├── 🖼  hospital_emergency_room_management_Analysis_Dashboard_images (.png)           # Dashboard screenshot
├── 📘 readme.md                                                                     # Project documentation

---

## 🚀 How to Run

### Open the Workbook

```text
data/Hospital_Emergency_Room_Analytics.xlsx
```

### Review the Dataset

```text
data/Hospital_Emergency_Room_Data.csv
```

### Read the Full Report

```text
reports/Hospital_Emergency_Room_Analytics_Full_Period_Report.pdf
```

### Clone the Repository

```bash
git clone https://github.com/risitsahoo/hospital-emergency-room-analytics.git
cd hospital-emergency-room-analytics
```

---

<a id="data-quality-limitations-custom"></a>
## ⚠️ Data Quality & Limitations

- **9,216 unique records** covering April 2023 – October 2024
- 2023 vs 2024 is a **partial-period comparison**, not a full-calendar-year comparison
- Department Referral missing for **5,400 records (58.6%)**
- Satisfaction Score missing for **6,699 records (72.7%)**
- Satisfaction averages use non-blank scores only
- Gender values were normalized before reporting
- Source patient-name fields are not used in aggregated reporting
- Analysis is **descriptive and operational**, not clinical decision support
- Dataset is publicly sourced; no proprietary hospital data is claimed

---

## 📄 Detailed Reports

For readers who want the full analytical documentation:

- **Full-Period Report:** `reports/Hospital_Emergency_Room_Analytics_Full_Period_Report.pdf`
- **October 2024 Supporting Analysis:** `reports/Hospital_Emergency_Room_Analytics_October_2024_Report.pdf`

> **README = project overview | Workbook = analysis | Reports = detailed documentation**

---

## 🏁 Conclusion

This project demonstrates the complete journey from **raw data to business insight** using Microsoft Excel:

> **Clean → Analyze → Measure → Visualize → Interpret → Recommend**

With **9,216 records across 19 months**, the project demonstrates practical capability in **Excel Analytics, KPI Reporting, Time-Series Analysis, Dashboard Development, Data Quality, and Business Storytelling**.

---

## 📬 Contact

### **Risit Sahoo**

**Aspiring Data Analyst | Excel | SQL | Power BI | Python**

- 📍 Bengaluru, India
- 📧 Email: risit.sahoo121@gmail.com
- 💼 LinkedIn: https://linkedin.com/in/risitsahoo 
- 🐙 GitHub: https://github.com/risitsahoo

**Open to Data Analyst, BI Analyst, MIS Analyst and Business Analyst opportunities.**

---

### ⭐ Project Highlights

**9,216 Records** · **19 Months** · **Excel Dashboard** · **8 Core KPIs** · **Time-Series Analysis** · **Data Quality** · **Business Insights**
