<img width="579" height="326" alt="1_Home" src="https://github.com/user-attachments/assets/145fe005-2eb0-4d8e-b19e-6714770e1e71" />
# 📊 Vodafone Qatar Telecom Data Analysis Dashboard

## 📌 Project Overview
This interactive analytical dashboard was developed using **Power BI** to analyze the performance of **Vodafone Qatar** from **2021 to 2023**. The project aims to provide comprehensive, data-driven insights to support senior management in making strategic decisions, focusing on revenue sustainability, digital transformation, and customer risk management.

The analysis evaluates financial performance, customer behavior, service quality, and digital adoption trends within the telecommunications sector.

---

## 🎯 Project Objectives
- **Financial Growth Analysis:** Monitor total revenue trends and overall financial stability.
- **Customer Value Metrics:** Measure and track the Average Revenue Per User (ARPU).
- **Churn & Retention Management:** Analyze Churn Rates and customer behavior to improve retention strategies.
- **Service Quality Evaluation:** Assess Customer Satisfaction (CSAT) and measure the impact of network efficiency on loyalty.
- **Digital Transformation Tracking:** Evaluate the growth of digital sales and customer adoption of digital channels.

---

## 🧩 Dashboard Structure
The dashboard is structured into five core analytical modules for seamless navigation and insight discovery:

1. **1️⃣ Executive Overview:** Displays high-level Key Performance Indicators (KPIs) including Revenue, Total Subscribers, ARPU, Churn Rate, and Customer Satisfaction.
2. **2️⃣ Customers & Churn Analysis:** Focuses on customer profiles, analyzing churn rates across different market segments and geographic regions.
3. **3️⃣ Revenue & Financial Performance:** Provides a deep dive into revenue streams, ARPU growth, and performance across various business sectors.
4. **4️⃣ Usage & Digital Behavior:** Tracks customer engagement with digital services, recharge behaviors, and online platform adoption.
5. **5️⃣ Customer Service & Operations:** Analyzes support ticket performance, complaint resolution efficiency, and its direct impact on customer loyalty.

---

## 📈 Key Insights
- **Financial Growth Drivers:** Total revenue growth was simultaneously driven by an increase in subscriber base and higher ARPU, reflecting healthy market expansion and strong profitability.
- **Segmented Churn Risks:** Certain segments exhibited higher churn rates despite generating stable ARPU, indicating that customer experience—rather than pricing—is the primary driver for retention.
- **Growth Sustainability:** While financial performance remained strong, customer satisfaction indices in specific periods fell slightly below targets, highlighting a potential long-term risk to sustainable growth.
- **Digital Adoption Impact:** The accelerating digital transformation significantly boosted commercial efficiency and reduced operational overhead, evidenced by a sharp increase in digital sales.
- **Operational Efficiency:** Network availability and rapid complaint resolution times showed a direct, statistically positive correlation with lower churn rates and higher CSAT scores.

---

## ⚙️ Technical Implementation

### 📌 Data Source & Structure
- **Data Source:** The dataset used in this project was sourced from **Kaggle** (Telecom industry sample dataset).
- **Data Structuring:** Consolidated raw telecom records into a unified analytical dataset (`Vodafone qatar dataset`), bridging financial KPIs, operations, and customer demographics into a flat structure optimized for rapid DAX execution and report performance.
- **Calculated Measures:** Developed custom business metrics directly from base columns to compute precise formulas for Churn, ARPU, and CSAT, comparing performance dynamically against preset business benchmarks.

### 📌 Advanced DAX & KPI Calculations
Utilized **DAX** to build robust, dynamic measures and leveraged **Time Intelligence** functions for comprehensive Year-over-Year (YoY) and Quarter-over-Quarter (QoQ) comparative analysis. Key calculations include:
- **Revenue & Growth KPIs:** `Revenue Growth % YoY`, `Net Customer Growth`.
- **Customer Value Metrics:** `ARPU Growth %`, `Digital Sales Performance` (`Digital_Sales_Pct`).
- **Retention & Satisfaction:** `Churn Rate Analysis` (`Churn_Rate_Pct`), `Customer Satisfaction Index`.
- **Operational Excellence:** Network availability KPIs and average resolution tracking.

### 🎯 KPI Tracking & Target Benchmarking
- **Performance Cards:** Designed intuitive `KPI Cards` and `Gauge Charts` to evaluate actual figures against strategic corporate objectives.
- **Target Benchmarking:** Set dynamic goals based on internal historical averages and telecom industry benchmarks.
- **Conditional Formatting:** Implemented clear color-coded visual alerts (Green/Red indicators) to highlight performance wins and isolate operational areas requiring immediate attention.

### 🎨 Interactive Dashboard Design & Visualizations
Engineered the interface to prioritize data scannability and user experience (UX) through advanced Power BI interactive features:
- **Interactive Elements:** Deployed custom `Slicers` (Timeframe, Region, Segment) and an intuitive vertical `Page Navigation` panel for streamlined switching between the 5 reports.
- **Dynamic Exploration:** Enabled page-wide `Cross-filtering` to allow cross-visual interactivity, ensuring that selecting any specific data point updates the entire page context dynamically.
- **Visualization Techniques:** Handpicked visuals mapped specifically to analytical use cases:
  - `Line & Area Charts` for temporal trend analysis.
  - `Scatter Plots` to uncover complex multidimensional correlations (e.g., Complaint Resolution Time vs. Churn Rate).
  - `Clustered & Stacked Bar Charts` for explicit categorical and geographic comparisons.

---

## 🛠 Tools & Technologies Used
- **Power BI Desktop** (Data Structuring & Interactive Report Authoring)
- **DAX** (Data Analysis Expressions - Advanced Calculations)
- **Power Query** (ETL - Data Cleaning & Transformation)

---

## 👩‍💻 Developed By
**Hend Abdelnasser**  (https://www.linkedin.com/in/hend-abd-elnasser-095764218/)

---

> ⚠️ **Disclaimer:** This project is created strictly for **portfolio and educational purposes**. The dataset used is completely **simulated/synthetic** sourced from Kaggle and does **not** reflect the actual financial, operational, or customer data of Vodafone Qatar. This project is entirely independent and is **not affiliated with, endorsed by, or connected to** Vodafone Qatar.
