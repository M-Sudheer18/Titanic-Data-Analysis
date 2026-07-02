# 🚢 Titanic Survival & Fatality Analysis Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Python](https://img.shields.io/badge/Python-Data%20Processing-blue?logo=python)
![Status](https://img.shields.io/badge/Project-Completed-success)
![License](https://img.shields.io/badge/License-MIT-green)

---

# 📌 Project Overview

The **Titanic Survival & Fatality Analysis Dashboard** is a complete Business Intelligence (BI) project developed using **Power BI**. The dashboard explores the famous Titanic dataset to identify patterns affecting passenger survival and fatalities.

The project consists of multiple interactive dashboard pages covering:

- Passenger Overview
- Survival Analysis
- Fatality Analysis
- Comparative Analysis
- Final Report

The dashboards provide deep insights into how **Age, Gender, Passenger Class, Family Size, Fare, and Embarkation Port** influenced survival during the Titanic disaster.

---

# 🎯 Project Objectives

The main objectives of this project are:

- Analyze passenger demographics
- Study survival patterns
- Understand fatality trends
- Compare survival and death rates
- Discover influential factors
- Create interactive visual reports
- Present business-style insights

---

# 🛠 Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- Titanic Dataset
- Data Modeling
- Data Visualization

---

# 📂 Project Architecture

```
                    Titanic Dataset
                           │
                           ▼
                 Data Collection (CSV)
                           │
                           ▼
                  Data Cleaning (Power Query)
                           │
         ┌─────────────────┼─────────────────┐
         ▼                 ▼                 ▼
 Missing Values      Data Formatting     Remove Duplicates
         │                 │                 │
         └─────────────────┼─────────────────┘
                           ▼
                  Feature Engineering
                           │
        ┌──────────────────┼──────────────────┐
        ▼                  ▼                  ▼
   Age Groups        Family Category     Survival Rate
                           │
                           ▼
                  Data Modeling (Power BI)
                           │
                           ▼
                    DAX Calculations
                           │
                           ▼
                  Dashboard Development
                           │
        ┌──────────────────┼────────────────────┐
        ▼                  ▼                    ▼
 Survival Dashboard   Fatality Dashboard   Comparison Dashboard
                           │
                           ▼
                    Interactive Report
```

---

# 📊 Dataset Information

The Titanic dataset contains passenger information including:

| Feature | Description |
|----------|-------------|
| PassengerId | Passenger ID |
| Survived | Survival Status |
| Pclass | Passenger Class |
| Name | Passenger Name |
| Sex | Gender |
| Age | Passenger Age |
| SibSp | Number of Siblings/Spouses |
| Parch | Number of Parents/Children |
| Ticket | Ticket Number |
| Fare | Ticket Fare |
| Cabin | Cabin Number |
| Embarked | Boarding Port |

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns
- Handled missing values
- Corrected data types
- Created Age Groups
- Created Family Categories
- Removed duplicate records
- Built calculated columns
- Created DAX Measures
- Standardized column names

---

# 📈 Dashboard Pages

## 1️⃣ Titanic Survival Overview

This dashboard provides:

- Total Passengers
- Total Survivors
- Survival Rate
- Survivors by Age Group
- Passenger Class Distribution
- Gender-wise Survival Count
- Survival by Passenger Class
- Age Group Analysis

### Key KPIs

- Total Passengers
- Total Survivors
- Survival Rate

---

## 2️⃣ Titanic Fatality Analysis

The second dashboard focuses on fatalities.

Includes:

- Total Deaths
- Death Rate
- Male Deaths
- Female Deaths
- Death by Passenger Class
- Death by Age Group
- Death by Family Category
- Death by Embarkation

---

## 3️⃣ Survival vs Death Analysis

This page compares:

- Total Survivors
- Total Deaths
- Survival Rate
- Death Rate
- Family Fare Analysis
- Survival Table
- Death Comparison

---

## 4️⃣ Final Report

The report summarizes all dashboard findings into business insights.

---

# 📊 Dashboard Workflow

```
Dataset
   │
   ▼
Power Query
   │
   ▼
Cleaning
   │
   ▼
Transformation
   │
   ▼
Data Model
   │
   ▼
Relationships
   │
   ▼
DAX Measures
   │
   ▼
Visualizations
   │
   ▼
Interactive Dashboard
```

---

# 📐 Data Model Architecture

```
                Titanic Dataset
                       │
         ┌─────────────┴─────────────┐
         ▼                           ▼
 Passenger Table              Calculated Columns
         │                           │
         ▼                           ▼
      Measures                 Age Groups
         │                  Family Category
         ▼                  Survival Status
         └─────────────┬─────────────┘
                       ▼
                  Dashboard Pages
```

---

# 📊 DAX Measures

Examples:

```DAX
Total Passengers = COUNT(Titanic[PassengerId])

Total Survivors = SUM(Titanic[Survived])

Total Deaths =
COUNT(Titanic[PassengerId]) - SUM(Titanic[Survived])

Survival Rate =
DIVIDE([Total Survivors],[Total Passengers])*100

Death Rate =
DIVIDE([Total Deaths],[Total Passengers])*100
```

---

# 📊 Visualizations Used

- KPI Cards
- Clustered Bar Chart
- Stacked Column Chart
- Pie Chart
- Line Chart
- Funnel Chart
- Treemap
- Matrix/Table
- Slicers

---

# 🔍 Business Insights

### Passenger Statistics

- Total Passengers: **712**
- Survivors: **288**
- Deaths: **424**
- Survival Rate: **40.45%**
- Death Rate: **59.55%**

---

### Age Analysis

- Adults recorded the highest number of survivors.
- Children achieved the highest survival rate.
- Senior citizens had the lowest survival rate.

---

### Gender Analysis

- Female passengers had a much higher survival probability.
- Male passengers experienced the highest number of fatalities.

---

### Passenger Class Analysis

- Third Class contained the largest number of passengers.
- Third Class suffered the highest fatalities.
- First Class passengers had better survival chances.

---

### Family Analysis

- Small families generally experienced better survival.
- Large families paid the highest average fare.

---

### Embarkation Analysis

- Southampton had the largest passenger count.
- Southampton also recorded the highest fatalities.

---

# 📈 Dashboard Features

✅ Interactive Filters

✅ KPI Cards

✅ Dynamic Charts

✅ Drill-down Analysis

✅ Business Insights

✅ Responsive Layout

✅ Professional Theme

---

# 🚀 Project Architecture (Complete)

```
                           Titanic Dataset
                                  │
                                  ▼
                       Data Collection (CSV)
                                  │
                                  ▼
                     Power Query Data Cleaning
                                  │
          ┌───────────────────────┼────────────────────────┐
          ▼                       ▼                        ▼
   Missing Values          Duplicate Removal       Data Formatting
          │                       │                        │
          └───────────────────────┼────────────────────────┘
                                  ▼
                      Feature Engineering
                                  │
      ┌───────────────────────────┼───────────────────────────┐
      ▼                           ▼                           ▼
 Age Groups               Family Category              Passenger Status
                                  │
                                  ▼
                        Data Modeling (Power BI)
                                  │
                                  ▼
                          DAX Calculations
                                  │
                                  ▼
                     Interactive Visualizations
                                  │
          ┌───────────────────────┼────────────────────────┐
          ▼                       ▼                        ▼
   Survival Dashboard      Fatality Dashboard     Comparison Dashboard
                                  │
                                  ▼
                          Final Business Report
```

---

# 📌 Project Outcomes

- Improved understanding of Titanic survival trends.
- Identified demographic patterns influencing survival.
- Demonstrated Power BI dashboard development skills.
- Applied data cleaning, modeling, and visualization techniques.
- Delivered an interactive dashboard for exploratory analysis.

---

# 📚 Future Enhancements

- Integrate real-time datasets.
- Add predictive analytics using Machine Learning.
- Publish dashboard to Power BI Service.
- Enable Row-Level Security (RLS).
- Include forecasting and advanced statistical analysis.

---

# 👨‍💻 Author

**Sudheer Muthyala**

**B.Tech – Electronics & Communication Engineering**

**Aspiring Data Scientist | Power BI Developer | Python Developer**

GitHub: https://github.com/M-Sudheer18

LinkedIn: *(Add your LinkedIn profile here)*

---

# ⭐ If you found this project useful, please consider giving it a Star on GitHub!
