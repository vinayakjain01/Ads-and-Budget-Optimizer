# Swastik Diya Campaign Optimization Dashboard 📊

## 📌 Project Overview

**Role:** Data Analyst Intern
**Company:** Madvertise
**Timeline:** July 2024 – Sept 2024

This project focuses on analyzing **digital advertising performance data** from a real client campaign managed by Madvertise. The objective was to transform messy marketing data exported from Facebook Ads Manager into an **interactive Power BI dashboard** that helps marketing teams evaluate campaign performance, run A/B testing, and optimize advertising budgets.

The final dashboard analyzed campaign metrics including **₹38K total ad spend, ₹53K revenue generated, and 188K impressions**, enabling stakeholders to monitor performance and identify high-performing campaigns. 

---

# 💼 Business Problem

The marketing team was running multiple ad campaigns but lacked a **centralized analytical system** to track performance.

The raw advertising data was exported directly from **Facebook Ads Manager**, but it contained inconsistencies and was difficult to analyze.

Key questions stakeholders needed answered:

• Which campaigns generate the highest **Return on Ad Spend (ROAS)**?
• Which campaigns are consuming budget but producing low returns?
• How does performance vary across **age groups and gender segments**?
• Which campaign should receive more budget through **A/B testing**?

Without a proper analytics dashboard, it was difficult to make **data-driven advertising decisions**.

---

# 🛠️ The Solution

To solve this problem, I built a **3-component Power BI analytics solution**:

### 1️⃣ Campaign Performance Dashboard

Provides a high-level overview of advertising performance using key KPIs:

• Total Ad Spend
• Revenue Generated
• ROAS (Return on Ad Spend)
• Impressions
• Clicks
• CPA (Cost per Acquisition)

The dashboard also allows filtering by **campaign name, age group, and date range** to analyze performance across different segments. 

<img width="1216" height="684" alt="image" src="https://github.com/user-attachments/assets/8def5398-28d9-47d2-81b9-e0a18e10879e" />

---

### 2️⃣ Campaign Efficiency Analysis

To identify profitable campaigns, I built visualizations comparing:

• **Spend vs Revenue trends over time**
• **ROAS by gender segmentation**
• **Ad spend distribution across age groups**
• **Campaign efficiency scatter plot (Spend vs ROAS)**

This helped stakeholders quickly identify campaigns that were **high spend but low return**, allowing them to pause or optimize those campaigns. 

---

### 3️⃣ A/B Testing Decision Engine

One of the core features of this dashboard is an **A/B testing comparison tool**.

Users can select two campaigns:

• Variant A (Control)
• Variant B (Challenger)

The dashboard automatically compares them using:

• ROAS
• CPA
• Conversion Rate (CVR)
• Ad Spend
• Traffic Lift

The system then highlights the **winning campaign**, helping marketing teams make quick optimization decisions. 

<img width="1220" height="689" alt="image" src="https://github.com/user-attachments/assets/30cfb014-f421-46e6-8385-d020eb959923" />

---

# 🔍 Key Insights & Discoveries

The analysis generated several actionable insights for campaign optimization:

### High Performing Campaign

The campaign **“Swastik Diya Ad 1 (Delhi NCR)”** delivered the highest performance with:

• **ROAS: 2.2**
• Strong revenue generation relative to spend.

This campaign became the **primary candidate for budget scaling**. 

---

### Underperforming Campaigns

Several campaigns generated **low or zero ROAS**, indicating inefficient budget allocation.

These campaigns were recommended for:

• Budget reduction
• Creative improvement
• Audience targeting changes. 

---

### Audience Insights

The demographic analysis revealed that:

• **Age group 25-34 drove the highest ad spend engagement**
• Female users generated slightly higher ROAS compared to male users. 

These insights helped refine **target audience strategies**.

---

# 📈 Budget Optimization

A **budget optimizer simulation** was created to test how budget reallocation could improve campaign performance.

By shifting spend from low-ROAS campaigns to high-ROAS campaigns:

• **Projected Revenue:** ₹82.6K
• **Projected ROAS:** 1.65
• **Revenue Uplift:** ₹30K
• **ROAS Improvement:** 18.5% 

This provided stakeholders with a **data-driven approach to maximize marketing ROI**.

<img width="1214" height="682" alt="image" src="https://github.com/user-attachments/assets/f01efe9c-3062-4d2a-b0b0-8a92e58e9df4" />

---

# ⚙️ Technical Process

## 1️⃣ Data Cleaning & Preparation

**Source:** Facebook Ads Manager export (Excel dataset)

Key steps:

• Standardized date formats
• Validated marketing metrics (spend, clicks, conversions)
• Structured the dataset for analytical modeling

---

## 2️⃣ Data Modeling

The dataset was structured in Power BI to enable efficient analysis:

• Campaign performance metrics
• Demographic segmentation
• Time-series campaign analysis

---

## 3️⃣ KPI Calculations (DAX)

Several key marketing metrics were calculated using DAX:

```
ROAS = DIVIDE([Revenue],[Spend])

CTR = DIVIDE([Clicks],[Impressions])

CPA = DIVIDE([Spend],[Conversions])

CVR = DIVIDE([Conversions],[Clicks])
```

These measures helped evaluate campaign profitability and efficiency.

---

## 4️⃣ Visualization

The dashboard includes multiple visual analytics techniques:

• KPI cards for high-level metrics
• Scatter plot for campaign efficiency
• Time series chart for spend vs revenue trends
• Demographic distribution charts
• A/B testing comparison visuals

---

# 🚀 How to Run the Project

1️⃣ Clone the repository

```
git clone https://github.com/yourusername/madvertise-campaign-dashboard.git
```

2️⃣ Open the `.pbix` file in **Microsoft Power BI Desktop**

3️⃣ If required, update the data source path:

```
Transform Data → Data Source Settings
```

---

# 📬 Contact

**Vinayak Jain**
LinkedIn:
[https://www.linkedin.com/in/vinayak-jain-69801b328/](https://www.linkedin.com/in/vinayak-jain-69801b328/)

Email:
[vinayakjainn11@gmail.com](mailto:vinayakjainn11@gmail.com)
