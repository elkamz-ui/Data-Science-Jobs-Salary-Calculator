# 📊 Data Science Salary Calculator Dashboard

![alt text](/images/Dashboard.png)
---

# 📌 Project Overview

The **Data Science Salary Calculator Dashboard** is an interactive analytics solution designed to evaluate global compensation trends across the data science and analytics ecosystem. The dashboard delivers data-driven insights into salary distributions by enabling users to dynamically filter and analyze data across three core dimensions:

- **Job Title**
- **Country**
- **Employment Type**

Developed using advanced Excel data modeling techniques, the project transforms raw labor-market datasets into structured analytical outputs through dynamic references, conditional aggregations, and automated KPI computation.

The dashboard is designed to support career benchmarking, market intelligence, and compensation analysis for data professionals and recruiters alike.

---

# 🚀 Interactive Dashboard Interface

The dashboard provides an intuitive and fully interactive interface capable of generating real-time analytical slices based on selected parameters.

The example displayed evaluates the compensation profile of a:

- **Senior Data Engineer**
- **United States**
- **Full-time Employment**

---

# 📸 Dashboard Preview

## Main Dashboard

![alt text](/images/Dashboard.png)
---

# 🔍 Dashboard Analytics Breakdown

The interface consolidates complex datasets into three high-level KPI indicators and multiple analytical visualization layers.

---

## 1️⃣ Key Performance Indicators (KPIs)

### 💰 Median Salary — **$150,000**
The median salary metric is dynamically calculated using conditional aggregation logic to minimize compensation skewness and reduce the influence of outliers. This provides a more reliable market benchmark for the selected role and region.

---

### 🔗 Top Job Platform — **LinkedIn**
This indicator identifies the dominant recruitment platform associated with the selected segment, providing insight into the most active hiring channel within the data industry.

---

### 📈 Job Count — **1,223**
Represents the total number of matching job records within the filtered dataset, serving as a market-demand indicator for the selected role configuration.

---

# 📊 Analytical Visualization Layers

## 📌 Job Title Salary Distribution
A comparative horizontal bar chart displaying salary variations across major data-related careers, including:

- Data Analyst
- Business Analyst
- Data Engineer
- Machine Learning Engineer
- Data Scientist
- Senior Data Analyst
- Senior Data Engineer
- Cloud Engineer
- Software Engineer
- Senior Data Scientist

This visualization highlights compensation progression across technical career paths and seniority levels.

---

## 🌍 Global Salary Distribution Map
A geospatial choropleth map illustrating salary density and country-level participation within the global data job market. This layer enables users to identify high-paying regions and internationally competitive markets.

---

## 🕒 Employment Type Comparison
A comparative visualization analyzing salary differences across employment structures, including:

- Full-time
- Part-time
- Contract
- Temporary
- Internship

This chart provides insight into compensation trends across flexible and traditional employment models.

---

# 🛠️ Data Engineering & Excel Architecture

The backend structure of the project is organized into multiple analytical layers to maintain processing efficiency, scalability, and data integrity.

---

## 📂 Data Layer
The foundational dataset contains raw job-market attributes, including:

- Job classifications
- Salary metrics
- Employment schedules
- Hiring platforms
- Geographic locations
- Remote-work indicators

---

## 📊 Aggregation & Processing Layer
Dedicated matrix tables perform conditional calculations and dynamic filtering operations using advanced Excel functions and array-based logic.

Error-handling mechanisms were implemented to systematically manage calculation exceptions such as:

- `#NUM!`
- `#NAME?`
- Null-value inconsistencies

This ensures clean and stable analytical outputs across all dashboard filters.

---

## 🔗 Platform Intelligence Layer
A frequency-distribution model dynamically evaluates hiring-platform occurrence rates to identify the dominant recruitment channel within each filtered segment.

This layer powers responsive KPI text outputs and recruitment-market analysis.

---

# 📈 Technologies Used

| Technology | Purpose |
|------------|----------|
| Microsoft Excel | Dashboard Development & Data Modeling |
| Dynamic Arrays | Conditional Processing |
| Bing Maps | Geospatial Visualization |
| Git & GitHub | Version Control & Portfolio Hosting |

---

# 📁 Repository Structure

```bash

├── images/
│   └── dashboard-preview.png
├── README.md
└── Data Science Job Salary Calculator Project.xlsx