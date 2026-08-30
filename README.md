<div align="center">

# 📊 Sales Tracker Dashboard | Power BI

### An End-to-End Interactive Sales Performance & Trend Analysis Report

<img width="92" height="28" alt="Powerbi" src="https://github.com/user-attachments/assets/9b11285c-55ff-4055-9018-9a2389d4b0b9" />
<img width="51" height="28" alt="DAX" src="https://github.com/user-attachments/assets/3059feb3-f0b6-4e8c-b6cc-62b7d80793aa" />


</div>

---

## 🖼️ Dashboard Preview

<img width="863" height="494" alt="Sales Tracker" src="https://github.com/user-attachments/assets/7b041f54-bcc7-4b30-acc7-3bf33b332702" />

> *A single-page, fully interactive Power BI dashboard built to track sales value, volume, and pricing trends across brands, categories, and territories.*

---

## 📌 Project Overview

This **Sales Tracker Dashboard** was designed to give business stakeholders a **360° view of sales performance** — from high-level KPIs down to brand, category, and regional breakdowns. It enables decision-makers to quickly spot trends, compare brand/category performance, and identify top- and under-performing territories, without needing to touch raw data.

As the **Data Analyst** on this project, my role covered the full analytics lifecycle:

- 🔍 Understanding raw transactional sales data (date, brand, category, territory, area, volume, value)
- 🧹 Cleaning and shaping the data model in Power Query
- 🧮 Building DAX measures for KPIs (Total Sales Value, Total Sales Ton, Avg. Price per Ton)
- 🎨 Designing an intuitive, single-page report layout with slicers for self-service filtering
- 📈 Selecting the right visuals for each business question (trend, composition, ranking, comparison)

---

## 🎯 Business Objective

The dashboard answers key business questions such as:

- What is our **overall sales value, volume, and average price**?
- Which **brands and categories** are driving the most revenue?
- How is sales **distributed across territories/regions**?
- How does sales performance **trend over time** (daily/monthly)?
- How can stakeholders **filter by Area, Category, Brand, or Territory** to drill into specifics?

---

## 🧩 Key Features

| Feature | Description |
|---|---|
| **KPI Cards** | Instant snapshot of Total Sales Value, Total Sales (Ton), and Avg. Price per Ton |
| **Dynamic Slicers** | Filter the entire report by `Area Name`, `Category Name`, `Brand Name`, and `Territory Name` |
| **Cross-Filtering Tables** | Ranked tables for Category, Territory, and Brand sales performance with running totals |
| **Donut Chart** | Brand-wise contribution to total sales value (% share) |
| **Trend Lines** | Time-series analysis of sales value by date, and by date + category |
| **Ranked Bar Chart** | Territory-wise sales value comparison, sorted highest to lowest |
| **Brand vs Category Combo View** | Comparative performance of top brands across categories |

---

## 📊 Visualization Breakdown

### 1. KPI Summary Cards
- **Total Sales Value:** `298.10M`
- **Total Sales (Ton):** `676.32`
- **Avg. Price per Ton:** `440.77K`

These give an at-a-glance performance summary before diving into the details.

### 2. Filter Panel (Slicers)
Located on the left side, allowing dynamic, self-service filtering by:
- `Area Name`
- `Category Name`
- `Brand Name`
- `Territory Name`

### 3. Category, Territory & Brand Tables
Three ranked matrix tables showing **Total Sales Value** broken down by:
- **Category** (e.g., Biscuit, Butter Oil, Crackers, Gift, Milk, Noodles)
- **Territory** (e.g., B. Baria, Badda ND, Bahaddarhat, Banasree, C&B, Choddagram, Cox's Bazar)
- **Brand** (e.g., Diploma, Happy Cow, Poppers, Belleame-HD, Detos, Belleame-SD)

Each includes a **Total row** for quick summation and validation.

### 4. Brand Contribution Donut Chart
Shows each brand's **percentage share of total sales value** — highlighting **Diploma** as the dominant brand at over **60%** of total sales.

### 5. Total Sales on Brand (Comparative View)
A combo panel comparing **Biscuit vs Butter Oil** performance across brands, useful for identifying which product line each brand leans on most.

### 6. Territory Performance Bar Chart
A horizontal bar chart ranking territories (e.g., Feni, Cumilla, Shantinagar, Khilgaon, Vatara, Demra, Banasree) by total sales value — instantly surfacing top and bottom performing regions.

### 7. Sales Trend Over Time
Two time-series line charts:
- **Overall daily sales value trend** (Dec 01 – Dec 29), revealing volatility and dips
- **Sales trend segmented by category** (Biscuit vs Butter Oil), showing how each category behaves over the same period

---

## 🗂️ Data Model (Fields Used)

| Field | Type | Description |
|---|---|---|
| `sales_date` | Date | Transaction date, used for time-series trend analysis |
| `area_name` | Text | Higher-level geographic grouping |
| `territory_name` | Text | Sales territory / distribution zone |
| `category_name` | Text | Product category (Biscuit, Milk, Noodles, etc.) |
| `brand_name` | Text | Product brand (Diploma, Happy Cow, Poppers, etc.) |
| `Total_Sales_Value` | Measure (DAX) | Sum of sales revenue |
| `Total_Sales_Ton` | Measure (DAX) | Sum of sales volume in tons |
| `Avg_Price_Per_Ton` | Measure (DAX) | `Total_Sales_Value / Total_Sales_Ton` |

---

## 💡 Key Insights

- 🏆 **Diploma** is the clear market leader, contributing over **60%** of total sales value — a strong candidate for continued investment and stock prioritization.
- 📦 **Biscuit** and **Butter Oil** are the leading product categories by revenue contribution.
- 📍 Territories like **Feni** and **Cumilla** consistently outperform others, suggesting stronger distribution or demand in those regions.
- 📉 The daily sales trend shows a **notable dip around early-to-mid December**, which could warrant investigation into supply, demand, or reporting gaps for that period.
- 🔄 Category-level trend lines show **Biscuit sales are far more volatile** than Butter Oil, which stays relatively flat — useful for demand planning.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Report design & data visualization
- **Power Query (M)** – Data cleaning & transformation
- **DAX (Data Analysis Expressions)** – KPI and measure creation
- **Data Modeling** – Star-schema style relationships between date, product, and territory dimensions

---

## 📁 Repository Structure

```
├── assets/
│   └── dashboard-preview.png     # Dashboard screenshot used in this README
├── Sales_Tracker_Dashboard.pbix  # Power BI report file
└── README.md                     # Project documentation (this file)
```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `Sales_Tracker_Dashboard.pbix` in **Power BI Desktop**.
3. Use the slicers (Area, Category, Brand, Territory) to explore the data interactively.
4. Hover over any visual for tooltips with detailed values.

---

## 👤 Author

**Data Analyst Portfolio Project**
📈 Focused on turning raw sales data into actionable business insights through interactive BI dashboards.

*If you found this project useful or interesting, feel free to ⭐ star the repository!*
