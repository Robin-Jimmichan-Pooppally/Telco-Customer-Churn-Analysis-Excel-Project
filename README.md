# 📊 Telco Customer Churn Analysis – Retention & Attrition Insights

[![Excel](https://img.shields.io/badge/Excel-Dashboard-green?logo=microsoft-excel)](https://www.microsoft.com/excel)
[![Pivot Tables](https://img.shields.io/badge/Type-Churn_Analysis-blue)](https://github.com)
[![Data Visualization](https://img.shields.io/badge/Analysis-Customer_Retention-orange)](https://github.com)

An Excel-based solution built to analyze customer churn patterns in a telecom company and identify key factors contributing to customer attrition. It transforms raw customer data into actionable insights — enabling stakeholders to understand retention drivers, segment high-risk customers, and develop targeted retention strategies across multiple customer dimensions.

---

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Project Objective](#project-objective)
- [Dataset Description](#dataset-description)
- [Excel Techniques Used](#excel-techniques-used)
- [Dashboard Overview](#dashboard-overview)
- [Key Metrics & Insights](#key-metrics--insights)
- [Installation & Prerequisites](#installation--prerequisites)
- [How to Use](#how-to-use)
- [Key Insights](#key-insights)
- [Business Recommendations](#business-recommendations)
- [Tech Stack](#tech-stack)
- [Skills Demonstrated](#skills-demonstrated)

---

## 📊 Project Overview

This Excel project provides an **interactive analysis of customer churn behavior and retention patterns** using pivot tables, pivot charts, and dashboard visualization. It enables monitoring of:

- 📈 **Overall churn distribution** (Retained vs Churned customers)
- 📋 **Churn rate by contract type** (Month-to-month, One-year, Two-year contracts)
- ⏱️ **Churn trend by tenure** (Customer loyalty over time)
- 💳 **Churn rate by payment method** (Electronic check, Bank transfer, etc.)
- 👥 **Churn by demographic factors** (Gender, Senior citizen status, Partner status)
- 🌐 **Churn by internet service type** (Fiber optic, DSL, No internet)
- 📊 **Churn by billing method** (Paperless vs Traditional billing)
- 💰 **Churn by monthly charges category** (High, Medium, Low spenders)

---

## 🎯 Project Objective

To analyze customer churn patterns in a telecom company and identify key factors contributing to customer attrition:

✅ **Identify major churn drivers** across customer segments  
✅ **Analyze retention patterns** by contract type and tenure  
✅ **Evaluate payment method impact** on customer retention  
✅ **Segment customers** by churn risk factors  
✅ **Generate actionable insights** for retention strategy  
✅ **Support data-driven decision-making** in customer success and marketing  

---

## ⚙️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Microsoft Excel** | Data cleaning, pivot tables, dashboard creation |
| **Pivot Tables** | Categorical churn analysis and segmentation |
| **Pivot Charts** | Visual insights (Column, Bar, Donut, Line charts) |
| **Slicers** | Interactive filtering across dashboard |
| **Conditional Formatting** | Data highlighting and color coding |

---

## 📋 Dataset Description

### File Details

**File Name:** Telco-Customer-Churn-Analysis-[Excel].xlsx

**Source:** Public telecom customer churn dataset

**Total Records:** ~7,043 customer entries

**Total Columns:** 21 attributes

### Columns

| Column | Description |
|--------|-------------|
| **CustomerID** | Unique customer identifier |
| **Gender** | Customer gender |
| **SeniorCitizen** | Senior citizen status (Yes/No) |
| **Partner** | Partner status (Yes/No) |
| **Dependents** | Dependent family members (Yes/No) |
| **Tenure** | Duration of customer relationship (months) |
| **PhoneService** | Phone service subscription |
| **MultipleLines** | Multiple phone lines subscription |
| **InternetService** | Internet service type (Fiber, DSL, None) |
| **OnlineSecurity** | Online security service |
| **OnlineBackup** | Online backup service |
| **DeviceProtection** | Device protection service |
| **TechSupport** | Tech support service |
| **StreamingTV** | Streaming TV service |
| **StreamingMovies** | Streaming movies service |
| **Contract** | Contract type (Month-to-month, One-year, Two-year) |
| **PaperlessBilling** | Paperless billing status |
| **PaymentMethod** | Payment method used |
| **MonthlyCharges** | Monthly subscription charges |
| **TotalCharges** | Total charges to date |
| **Churn** | Customer churn status (Yes/No) |

---

## ⚙️ Excel Techniques Used

**Data Cleaning & Preparation**
- Data filters for data validation
- Conditional formatting for visual highlighting

**Data Transformation**
- Derived columns for segmentation (MonthlyChargesGroup, TenureGroup)

**Analysis & Aggregation**
- Pivot Tables for categorical churn analysis
- Pivot Charts for visual representation

**Visualization**
- Column charts for comparative analysis
- Bar charts for categorical insights
- Donut charts for distribution overview
- Line charts for trend analysis

**Interactivity**
- Slicers for interactive filtering
- Cross-filtering capability across dashboard elements

**Dashboard Design**
- Consistent color coding (Green → Retained, Red → Churned)
- Unified dashboard layout

---

## 📈 Dashboard Overview

**Dashboard Title:** Customer Churn Analysis Dashboard (Telecom Data)

The dashboard summarizes churn behavior across key dimensions with the following visualizations:

### 1️⃣ Overall Churn Distribution
- **Visual Type:** Donut Chart
- **Purpose:** Shows overall percentage of Retained vs Churned customers
- **Insight:** Provides high-level churn overview

### 2️⃣ Churn Rate by Contract Type
- **Highest Churn:** Month-to-month contracts (40.48%)
- **Lowest Churn:** Two-year contracts (0.38%)
- **Insight:** Longer contracts clearly reduce churn

### 3️⃣ Customer Churn Trend by Tenure (Months)
- **<12 months:** 23.76% churn
- **49+ months:** 14.76% churn
- **Insight:** Customer loyalty increases over time

### 4️⃣ Churn Rate by Payment Method
- **Highest Churn:** Electronic check (23.97%)
- **Lowest Churn:** Bank transfer (automatic) (19.44%)
- **Insight:** Customers using auto-pay methods are more likely to stay

### 5️⃣ Churn Rate by Gender
- **Female:** 21.62%
- **Male:** 21.29%
- **Insight:** No major difference by gender

### 6️⃣ Churn Rate by Internet Service Type
- **Fiber Optic:** 21.82%
- **DSL:** 21.17%
- **No Internet Service:** 21.16%
- **Insight:** Potential dissatisfaction with fiber service or higher pricing

### 7️⃣ Churn Rate by Senior Citizen Status
- **Seniors:** 22.41%
- **Non-seniors:** 21.29%
- **Insight:** Seniors churn slightly more

### 8️⃣ Churn Rate by Partner Status
- **Partnered:** 21.73%
- **No Partner:** 21.13%
- **Insight:** Minimal variation by partner status

### 9️⃣ Churn Rate by Paperless Billing
- **Paperless Billing:** 24.05% churn
- **Traditional Billing:** 16.61% churn
- **Insight:** Paperless billing users churn more — possibly linked to month-to-month plans

### 🔟 Churn Rate by Monthly Charges Category
- **High Spenders (>$70):** 21.76% churn
- **Medium Spenders:** 20.99% churn
- **Low Spenders:** 21.58% churn
- **Insight:** High-paying customers churn the most, indicating pricing sensitivity

---

## 💡 Key Metrics & Insights

### Churn Analysis

✅ **Contract Type Impact**  
Short-term (month-to-month) contracts show significantly higher churn (40.48%) compared to long-term contracts (0.38% for two-year)

✅ **Tenure & Loyalty**  
Churn decreases steadily with higher tenure — customers staying >49 months show only 14.76% churn rate

✅ **Payment Method Behavior**  
Electronic check users are more likely to churn (23.97%) than bank transfer (automatic) users (19.44%)

✅ **Billing Method Effect**  
Paperless billing users churn at 24.05% compared to 16.61% for traditional billing customers

✅ **Pricing Sensitivity**  
High-paying customers (>$70/month) show the highest churn rate (21.76%), indicating potential pricing sensitivity

✅ **Demographic Factors**  
Senior citizens show slightly higher churn (22.41%) than non-seniors (21.29%)

---

## ⚙️ Installation & Prerequisites

### System Requirements

- **Microsoft Excel** (2016 or later recommended)
- **Windows 10** or later / **macOS** with Excel installed
- **2GB RAM** minimum (4GB+ recommended)
- **100MB** free disk space

### Installation Steps

```
1. Download the Excel File
   → Telco-Customer-Churn-Analysis-[Excel].xlsx

2. Open Microsoft Excel

3. File → Open → Select Telco-Customer-Churn-Analysis-[Excel].xlsx

4. Wait for file to load completely

5. Navigate to Dashboard sheet to view visuals
```

---

## 📊 How to Use

### Accessing the Dashboard

**Step 1: Open the File**
```
Microsoft Excel → File → Open → Telco-Customer-Churn-Analysis-[Excel].xlsx
```

**Step 2: Navigate to Dashboard Sheet**
- Select the Dashboard tab/sheet from the sheet tabs at the bottom
- All visualizations and metrics are displayed on this sheet

**Step 3: Use Interactive Elements**

| Feature | Action |
|---------|--------|
| **Slicers** | Click to filter by Contract Type, Payment Method, Internet Service, Billing Method, or other dimensions |
| **Charts** | Click on chart elements to view filtered data |
| **Conditional Formatting** | Color-coded cells indicate churn status (Green/Red) |

### Interpreting the Data

- **Donut Chart** → Overall churn distribution at a glance
- **Column Charts** → Churn rate comparison across categories
- **Bar Charts** → Categorical churn insights
- **Line Charts** → Churn trends over tenure periods
- **Slicers** → Filter dashboard by specific segments

---

## 💡 Key Insights

### Churn Drivers

✅ **Short-term & Paperless billing customers** show significantly higher churn → focus area for retention

✅ **Electronic check users** are more likely to churn than auto-pay users → consider incentives for switching to automatic payment

✅ **Customers with long tenure and contracts** exhibit strong loyalty → onboarding and engagement programs should target early months

✅ **High-paying customers** may need added value or discount-based loyalty programs to reduce churn risk

---

## 💼 Business Recommendations

**Contract Strategy**
- Introduce contract upgrade offers for month-to-month users

**Payment Method Incentives**
- Offer auto-pay discounts to reduce churn from electronic check users

**Loyalty Programs**
- Launch loyalty rewards for customers with tenure >12 months

**Pricing Strategy**
- Conduct price-value surveys for high-paying customers to identify pain points

**Retention Campaigns**
- Use targeted retention campaigns for paperless billing customers

---

## 🧰 Tech Stack

| Component | Technology |
|-----------|------------|
| **Platform** | Microsoft Excel |
| **Analysis Tool** | Pivot Tables & Pivot Charts |
| **Data Visualization** | Excel Charts (Column, Bar, Donut, Line) |
| **Interactivity** | Slicers & Conditional Formatting |
| **Data Source** | Public telecom customer churn dataset |

---

## 📁 Project Files

**File:** `Telco-Customer-Churn-Analysis-[Excel].xlsx`
- Excel workbook with data and dashboard
- Contains cleaned dataset, pivot tables, and visual dashboard
- Ready for immediate use and analysis

---

## 💼 Skills Demonstrated

✅ **Data Cleaning & Validation** in Excel  
✅ **Pivot Table Creation** for data aggregation  
✅ **Pivot Chart Design** for visual analysis  
✅ **Data Segmentation & Grouping** for customer categorization  
✅ **Dashboard Design & Layout** for effective presentation  
✅ **Business Insight Generation** from data patterns  
✅ **Churn Trend Interpretation** and analysis  
✅ **Conditional Formatting** for data highlighting  

---

## 📝 Notes

- Dataset contains ~7,043 customer records from public telecom churn data
- All pivot tables and charts are production-ready
- Dashboard uses color coding (Green → Retained, Red → Churned) for quick visual reference
- Slicers enable flexible filtering across multiple dimensions
- Analysis directly supports retention strategy and customer success initiatives

---

*This Excel-based Telco Customer Churn Analysis demonstrates practical business intelligence expertise in customer analytics, combining data cleaning, pivot table aggregation, and interactive dashboard visualization to enable data-driven decision-making through comprehensive monitoring of churn patterns, retention drivers, and customer segmentation across contract types, payment methods, tenure, and demographic factors.*
