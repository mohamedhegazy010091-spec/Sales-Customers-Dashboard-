# 📊 Tableau Project: Sales Performance & Customer Insights Dashboards

## 🧠 Introduction

This Tableau project presents two interactive dashboards — **Sales Dashboard** and **Customer Dashboard** — designed to help stakeholders such as **sales managers**, **executives**, and **marketing teams** analyze business performance and customer behavior.

The dashboards enable data-driven decision-making by visualizing key metrics, trends, and year-over-year comparisons across multiple dimensions such as time, product, and location.

---

## 📈 Sales Dashboard

### 🎯 **Purpose**
The **Sales Dashboard** provides an overview of core sales metrics and trends, enabling users to analyze **year-over-year performance** and identify key growth opportunities or declines.

---

### 🔑 **Key Requirements**

#### 🧾 KPI Overview
- Display **Total Sales**, **Total Profit**, and **Quantity** for the **Current Year (CY)** and **Previous Year (PY)**.  
- Implemented using **BANs (Big-As-Numbers)** charts for quick at-a-glance insights.

#### 📆 Sales Trends
- Visualize monthly performance for each KPI across CY and PY.  
- Highlight **highest** and **lowest** sales months for better recognition of performance peaks.  
- Built using **Sparkline Charts** for compact trend analysis.

#### 📊 Product Subcategory Comparison
- Compare **Sales** and **Profit** by product **Sub-Category** for CY vs. PY.  
- Highlight top and underperforming products.  
- Implemented using **Bar-in-Bar (Side-by-Side)** charts.

#### 📈 Weekly Trends for Sales & Profit
- Present **weekly sales and profit trends** for the current year.  
- Display **average weekly values** as reference lines.  
- Highlight weeks **above or below the average** for quick trend spotting.  
- Implemented using **Line Charts (Change Over Time)**.

---

## 👥 Customer Dashboard

### 🎯 **Purpose**
The **Customer Dashboard** provides a clear overview of customer trends and purchasing behaviors.  
It helps the **marketing** and **sales teams** generate insights to enhance engagement, retention, and satisfaction.

---

### 🔑 **Key Requirements**

#### 🧾 KPI Overview
- Display **Total Customers**, **Sales per Customer**, and **Total Orders** for CY and PY.  
- Use BANs for a clear comparison between years.

#### 📅 Customer Trends
- Present customer KPIs on a **monthly basis** for both CY and PY.  
- Highlight **peak and low months** in sales and engagement for pattern recognition.

#### 📦 Customer Distribution by Number of Orders
- Show how customers are distributed by their **order frequency**.  
- Identify **repeat customers**, **loyal buyers**, and **engagement levels**.
- Implemented using **Histogram** 

#### 💰 Top 10 Customers by Profit
- Highlight the **top 10 customers** who generated the highest profit.  
- Include details such as:
  - Rank  
  - Number of Orders  
  - Current Sales  
  - Current Profit  
  - Last Order Date
- So, I go with a **simple table**

---

## 🎨 Design & Interactivity Requirements

### ⚙️ Dashboard Dynamics
- Allow users to **analyze historical data** by selecting any desired year using a **Parameter Control**.  
- Enable seamless **navigation between dashboards** using **Navigation Buttons**.  
- Make all charts and graphs **interactive**, allowing users to **filter data directly from visualizations** using **Filter Actions**.

### 🔍 Data Filters
- Provide flexible data filtering by:
  - **Product Information:** Category, Sub-Category  
  - **Location Information:** Region, State, City  

These filters allow users to drill down into specific product lines or geographical areas for deeper insights.

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|------|----------|
| **Tableau Public** | Data visualization and dashboard design |
| **CSV Dataset** | Data source for analysis |
| **GitHub** | Documentation and version control |

---

## 📸 Dashboard Preview

Add your dashboard screenshots here 👇

```markdown
[View the steps here](https://www.notion.so/Sales-Dashboard-2a1f32e56408811fbc06f73f70057167)

![Customer Dashboard](screenshots/customer_dashboard.png)
