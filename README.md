# 📊 Data Analyst with AI Bootcamp - Batch 6 (KarirNex)

This repository contains a collection of assignments, data analysis projects, and portfolio dashboards completed during the **Data Analyst with AI Bootcamp** organized by **KarirNex (PT Ebiz Karisma Internasional)** from **July 1st to July 8th, 2026**.

Upon completion of the program, I graduated with an **Expert** proficiency level, completing a total of **20 Credit Hours (JP)** of intensive training.

---

## 🎖️ Credentials & Certification
* **Full Name:** Kevin Nugraha Santika Permana
* **Skill Level Predicate:** Expert
* **Certificate No.:** 1019/B-17/KBT.DA.6/KRX/VII/2026
* **Organizer:** KarirNex by PT Ebiz Karisma Internasional

---

## 🛠️ Tech Stack & Competencies
Throughout this bootcamp, the primary focus was mastering modern data analysis tools enhanced by artificial intelligence (*AI-driven analysis*):
1. **Advanced Microsoft Excel:** Data Formatting, Data Cleansing, & Pivot Tables.
2. **SQL (Google BigQuery):** Database management, data aggregation, window functions, Pareto analysis, and CTEs.
3. **Python (Google Colab / Jupyter Notebook):** Data Manipulation (`pandas`, `numpy`) and Data Visualization (`matplotlib`, `seaborn`).
4. **Google Looker Studio:** Interactive Dashboard Building & Narrative Analytics.

---

## 📂 Project & Assignment Breakdown

### 📁 Day 1: Data Formatting & Data Cleansing (Excel)
* **Topic:** Text data cleaning, category standardization, and data summarization using Pivot Tables.
* **Key Implementation:**
  * Handled irregular spacing in city data using the `=TRIM()` formula to create a standardized `city_clean` column.
  * Standardized 9 diverse raw product categories into 3 streamlined groups (*Cooking Ware, Serving Ware, Storage Ware*) using `=VLOOKUP()`.
* **Key Insights:**
  * South Tangerang (*Tangerang Selatan*) generated the lowest revenue, accounting for only **IDR 532,133,000**.
  * The *Cooking Ware* (*Alat Masak*) category dominated successful (*completed*) transactions with a massive **IDR 4,189,161,200**.

### 📁 Day 2: Advanced SQL Cloud Analytics (Google BigQuery)
* **Topic:** Querying a large-scale dataset (*10,000+ orders*) to uncover operational and commercial performance on Google Cloud Platform.
* **Key Implementation:** Advanced aggregation (`SUM`, `AVG`, `COUNT DISTINCT`), Window Functions (`ROW_NUMBER`, `CUMULATIVE SUM`), Conditional Logic (`CASE WHEN`), and Date Functions.
* **Key Insights:**
  * **Pareto 80/20 Law:** Analysis revealed that 25 top-performing products (out of 57 total items) contributed to 80% of the store's successful revenue.
  * **Financial & Risk Analysis:** Total revenue leakage due to refunded orders reached **IDR 279,711,700** (4.76% of total gross sales). The *20 cm Stainless Pot* had the highest refund rate (8.61%), presenting an opportunity to recover **IDR 3,288,750** if mitigated to the store's average target of 5%.
  * **Customer Loyalty:** `Customer_3` was identified as the most valuable customer with 29 completed orders and an impressive repeat purchase cycle averaging every 9.93 days.

### 📁 Day 3: Data Cleansing & Plotting (Python)
* **Topic:** End-to-end data pre-processing using Python to detect anomalies and visualize business correlations.
* **Key Implementation:** Leveraged `pandas` for duplicate removal, missing value imputation (`fillna("Unknown")`), date-time formatting, and visual exploratory data analysis (EDA) [cite: ].
* **Key Insights:**
  * Developed a *Horizontal Bar Chart* using `seaborn` to contrast total revenue performance across cities [cite: ].
  * The visualization confirmed that **North Jakarta** (*Jakarta Utara*) and **West Jakarta** (*Jakarta Barat*) led the market, contributing **IDR 5.06 Billion** and **IDR 5.02 Billion** respectively [cite: ].

### 📁 Day 4: Capstone Mini Project - Kitchen Equipment Sales Performance Dashboard (Looker Studio)
* **Topic:** Developing an interactive executive dashboard to deliver actionable insights to management.
* **Core Dashboard Metrics:**
  * **Total Sales:** IDR 5.9 Billion
  * **Total Orders:** 10,000
  * **Order Completed Rate:** 89.7%
* **Strategic Recommendations (Insights):**
  * *Cooking Ware* generates 79.5% of total sales. Management should prioritize inventory optimization for this high-demand line.
  * The *Espresso Coffee Machine* stands out as the highest revenue driver. It should be leveraged as the primary anchor for bundling or cross-selling strategies with secondary electrical appliances.

---

## 📈 Curriculum & Training Hours
The official certificate and syllabus breakdown are available in the `/certificate` folder. The competency hours consist of:
* Introduction to Data Analyst & Analytics: 2 Hours
* Data Formatting & Data Cleansing: 2 Hours
* Systematic Data Analyst: 1 Hour
* Google BigQuery & SQL Language: 3 Hours
* Python & Google Colab: 3 Hours
* Data Visualization & Looker Studio: 4 Hours
* Capstone Mini Project: 5 Hours
