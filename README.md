<h1 align="center">⚡ ElectroHub Sales & Profit Performance Analysis</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Data%20Analytics-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/DAX-Data%20Analysis-2563EB?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Power%20Query-Data%20Transformation-00A4EF?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Business%20Intelligence-Analytics-111827?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Data%20Visualization-Power%20BI-7C3AED?style=for-the-badge"/>
</p>

<p align="center">
  <b>📊 Turning ElectroHub Sales Data into Meaningful Business Insights</b>
</p>

<p align="center">
  <i>Sales • Profit • Products • Quantity • Discounts • Promotions • Cities • Trends • Orders</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=flat-square"/>
  <img src="https://img.shields.io/badge/Pages-4-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/KPIs-20%2B-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
</p>

---

## 📌 Table of Contents

| # | Section | # | Section |
|---|---------|---|---------|
| 1 | [Project Introduction](#-project-introduction) | 10 | [Page 2 — Product Analysis](#-page-2--product-performance-analysis) |
| 2 | [Project Domain](#-project-domain) | 11 | [Page 3 — Period Comparison](#️-page-3--period-comparison) |
| 3 | [Project Objectives](#-project-objectives) | 12 | [Page 4 — Order-Level Details](#-page-4--order-level-analysis) |
| 4 | [Project Requirements](#-project-requirements) | 13 | [Key Business Insights](#-key-business-insights) |
| 5 | [Tools & Technologies](#️-tools--technologies) | 14 | [Business Recommendations](#-business-recommendations) |
| 6 | [Analytical Procedure](#-complete-analytical-procedure) | 15 | [Future Scope](#-future-scope) |
| 7 | [Dashboard KPIs](#-dashboard-kpi-overview) | 16 | [Repository Structure](#-repository-structure) |
| 8 | [Dashboard Structure](#️-dashboard-structure) | 17 | [Skills Demonstrated](#-skills-demonstrated) |
| 9 | [Page 1 — Sales Overview](#-page-1--sales-overview) | 18 | [About & Connect](#-about-the-author) |

---

# 📌 Project Introduction

**ElectroHub Sales & Profit Performance Analysis** is a complete **Power BI Business Intelligence and Data Analytics project** developed to analyze and visualize transactional sales data.

The project provides an interactive analytical environment where users can explore sales, profit, quantity sold, products, discounts, promotions, orders, cities and time-based performance.

The dashboard is designed to convert raw sales transactions into meaningful insights that can help understand:

- 🏆 Product performance
- 💰 Sales performance
- 📈 Profitability
- 📦 Quantity sold
- 💸 Discount behavior
- 🎯 Promotion performance
- 📅 Sales trends
- 🌍 City-wise sales
- 🧾 Order-level details
- 🔄 Period-to-period performance

### 🔄 Analytics Workflow

```text
        ┌──────────────┐
        │  RAW DATA    │
        └──────┬───────┘
               ▼
      Data Understanding
               ▼
        Data Cleaning
               ▼
     Data Transformation
               ▼
        Data Modeling
               ▼
       DAX Calculations
               ▼
    Dashboard Development
               ▼
        Data Analysis
               ▼
      Business Insights
               ▼
      Recommendations
```

---

# 🏢 Project Domain

> **🛒 Retail / E-Commerce Analytics**

ElectroHub is analyzed as a retail/e-commerce business containing multiple product categories.

### 🗂️ Product Categories

| | Category | | Category |
|---|----------|---|----------|
| 💻 | Electronics | 👟 | Footwear |
| 👕 | Clothing | 🏠 | Home Appliances |
| 🎧 | Accessories | 🍳 | Kitchenware |
| 👜 | Bags | 🧴 | Personal Care |

The project focuses on understanding business performance through transactional sales data.

---

# 🎯 Project Objectives

The main objective of this project is to create an interactive Power BI dashboard that answers important business questions from the available sales data.

### 🎯 Primary Objectives

| # | Objective | Description |
|---|-----------|-------------|
| 1 | 🏆 **Product Ranking** | Analyze the Top 5 and Bottom 5 products |
| 2 | 📊 **Multi-Metric Comparison** | Compare products using Sales, Profit & Quantity Sold |
| 3 | 📅 **Trend Analysis** | Analyze how sales trends vary over time |
| 4 | ⏱️ **Time Granularity** | Daily, Monthly, Quarterly & Annual analysis |
| 5 | ⚖️ **Sales ↔ Profit** | Show the relationship between Sales and Profit |
| 6 | 🔄 **Period Comparison** | Compare Sales, Profit & Quantity between two periods |
| 7 | 🎯 **Discount Analysis** | Average discount offered in each promotion category |
| 8 | 🧾 **Order Analysis** | Calculate and display total number of orders |
| 9 | 🔎 **Order-Level Details** | Filterable order-level transactional table |
| 10 | 🌍 **City Analysis** | Analyze sales across different cities |
| 11 | 💡 **Insights** | Generate meaningful business insights |
| 12 | 🚀 **Recommendations** | Provide actionable business recommendations |

---

# 📋 Project Requirements

The project requirements are structured around the following analytical questions:

### 1️⃣ 🏆 Product Ranking

| Ranking Type | Top 5 | Bottom 5 |
|--------------|:-----:|:--------:|
| 💰 By **Sales** | ✅ | ✅ |
| 📈 By **Profit** | ✅ | ✅ |
| 📦 By **Quantity Sold** | ✅ | ✅ |

### 2️⃣ 📅 Sales Trend Analysis

Analyze how sales trends vary over time — **Daily • Monthly • Quarterly • Annually**

### 3️⃣ ⚖️ Sales & Profit Relationship

Show the relationship between **Sales ↔ Profit** to understand how sales performance relates to profitability.

### 4️⃣ 🔄 Period Comparison

Allow users to select any two periods and compare **Sales • Profit • Quantity Sold**.

### 5️⃣ 🎯 Discount Analysis

Show the **Average Discount** offered in each discount/promotion category.

### 6️⃣ 🧾 Order Analysis

Show the **Total Number of Orders**.

### 7️⃣ 🔎 Order-Level Details

Show available order-level fields including **Sales • Profit • Discount • Net Sales** and other available fields.

**Filterable by:**

| Filter | Icon |
|--------|:----:|
| Product | 🛍️ |
| Date | 📅 |
| Customer ID | 👤 |
| Promotion Category | 🎯 |

### 8️⃣ 🌍 City Analysis

Show **Sales by different cities**.

---

# 🧰 Tools & Technologies

| Tool / Technology | Purpose |
|-------------------|---------|
| 📊 **Power BI** | Dashboard development and visualization |
| 🔄 **Power Query** | Data cleaning and transformation |
| 🧮 **DAX** | Measures and calculations |
| 🗂️ **Data Modeling** | Analytical data structure |
| 📈 **Data Visualization** | Business reporting |
| 📋 **Excel / Tabular Data** | Source transactional data |

---

# 🔄 Complete Analytical Procedure

```text
┌──────────────────────────────────────────────────────────┐
│  STEP 1 → STEP 2 → STEP 3 → STEP 4 → STEP 5 → STEP 6 →   │
│  STEP 7 → STEP 8                                         │
└──────────────────────────────────────────────────────────┘
```

### 🔍 Step 1 — Data Understanding

Understand the transactional dataset and identify the fields required for business analysis.

**Important analytical fields:**

| | Field | | Field |
|---|-------|---|-------|
| 👤 | Customer ID | 🧾 | Order ID |
| 📅 | Date | 🛍️ | Product |
| 🔢 | Product ID | 💰 | Sales |
| 💵 | Total Sales | 📉 | Net Sales |
| 📈 | Profit | 💸 | Discount |
| 📊 | Discount Percentage | 🏷️ | Price Per Unit |
| 📦 | Units Sold | 🎯 | Promotion ID |
| 🎯 | Promotion Category | 🌍 | City |

### 🧹 Step 2 — Data Cleaning

The dataset is prepared for analysis by checking:

- ✅ Missing values
- ✅ Data types
- ✅ Duplicate records
- ✅ Date fields
- ✅ Numeric fields
- ✅ Category fields
- ✅ Product information
- ✅ Customer information
- ✅ Promotion information

> The objective is to create reliable data for dashboard calculations.

### 🔄 Step 3 — Data Transformation

**Power Query** is used for preparing the dataset for Power BI analysis.

Typical transformation activities include:

- 🔧 Formatting columns
- 🔢 Changing data types
- 🏷️ Cleaning categorical fields
- 📅 Preparing date information
- 📊 Organizing numerical fields
- 🎨 Preparing data for visualization

### 🗂️ Step 4 — Data Modeling

The cleaned data is structured in Power BI to support:

| Analysis Type | Icon |
|---------------|:----:|
| Product Analysis | 🛍️ |
| Customer Analysis | 👤 |
| Promotion Analysis | 🎯 |
| City Analysis | 🌍 |
| Date Analysis | 📅 |
| Order Analysis | 🧾 |
| Sales Analysis | 💰 |
| Profit Analysis | 📈 |

### 🧮 Step 5 — DAX Calculations

DAX measures are used to calculate important business metrics.

**Main Analytical Measures:**

| Measure | Measure | Measure |
|---------|---------|---------|
| `Total Sales` | `Total Profit` | `Total Orders` |
| `Total Quantity Sold` | `Average Discount` | `Product Sales` |
| `Product Profit` | `Product Quantity` | `Period Sales` |
| `Period Profit` | `Period Quantity` | `Net Sales` |

### 🎨 Step 6 — Visualization

Power BI visuals are used to present the analysis in an interactive and easy-to-understand format.

**Visual types include:**

`KPI Cards` • `Bar Charts` • `Column Charts` • `Line Charts` • `Scatter Charts` • `Maps` • `Tables` • `Slicers` • `Filters`

### 🔍 Step 7 — Business Analysis

The dashboard is used to identify:

- 🥇 High-performing products
- 📉 Low-performing products
- 📅 Sales trends
- 📈 Profit trends
- 💸 Discount patterns
- 🎯 Promotion behavior
- 🌍 City-level performance
- 🔄 Period-level differences

### 💡 Step 8 — Insights & Recommendations

The final stage converts analytical findings into business recommendations.

```text
        DATA
         ↓
     INFORMATION
         ↓
       INSIGHTS
         ↓
  BUSINESS DECISIONS
```

---

# 📊 Dashboard KPI Overview

The supplied dashboard view contains the following major KPIs:

| KPI | Dashboard Value | Icon |
|-----|:---------------:|:----:|
| 🧾 **Total Orders** | **3,510** | 🧾 |
| 💰 **Total Sales** | **122M** | 💰 |
| 📈 **Total Profit** | **12.2M** | 📈 |
| 📦 **Total Quantity Sold** | **7.1K** | 📦 |

> These KPIs provide a quick overview of the business performance represented in the dashboard.

---

# 🖥️ Dashboard Structure

The project is organized into **four major analytical sections**.

```text
┌─────────────────────────────────────────────┐
│        PAGE 1 — SALES OVERVIEW              │
├─────────────────────────────────────────────┤
│  🌍 Sales by City                           │
│  🧾 Total Orders                            │
│  🎯 Average Discount by Promotion           │
│  ⚖️  Profit vs Net Sales                    │
│  📅 Sales Trend                             │
└─────────────────────────────────────────────┘

┌─────────────────────────────────────────────┐
│      PAGE 2 — PRODUCT ANALYSIS              │
├─────────────────────────────────────────────┤
│  🏆 Top 5 Sales      │  📉 Bottom 5 Sales   │
│  📦 Top 5 Quantity   │  📉 Bottom 5 Quantity│
│  💰 Top 5 Profit     │  📉 Bottom 5 Profit  │
└─────────────────────────────────────────────┘

┌─────────────────────────────────────────────┐
│     PAGE 3 — PERIOD COMPARISON              │
├─────────────────────────────────────────────┤
│  🔵 Period 1                                │
│  🟣 Period 2                                │
│  💰 Sales Comparison                        │
│  📈 Profit Comparison                       │
│  📦 Quantity Comparison                     │
└─────────────────────────────────────────────┘

┌─────────────────────────────────────────────┐
│    PAGE 4 — ORDER LEVEL DETAILS             │
├─────────────────────────────────────────────┤
│  📅 Date Filter                             │
│  👤 Customer Filter                         │
│  🛍️  Product Filter                         │
│  🎯 Promotion Filter                        │
│  📋 Detailed Order Table                    │
└─────────────────────────────────────────────┘
```

---

# 🌍 PAGE 1 — Sales Overview

The **Sales Overview** page provides a high-level view of business performance.

### 🎨 Main Visuals

| Visual | Icon |
|--------|:----:|
| Sales by City | 🌍 |
| Total Orders | 🧾 |
| Average Discount by Promotion | 🎯 |
| Profit vs Net Sales | ⚖️ |
| Sales Trend | 📅 |

### 🌍 Sales by City Analysis

The city visualization displays sales performance across different cities.

**🎯 Purpose**

- 📍 Where sales are concentrated
- 🥇 Which cities perform strongly
- 🔍 Which cities may need additional attention
- 🗺️ How sales are distributed geographically

**💼 Business Applications**

| Application | Icon |
|-------------|:----:|
| Regional marketing | 📣 |
| Inventory planning | 📦 |
| Sales target allocation | 🎯 |
| Regional promotions | 🎁 |
| Market expansion decisions | 🚀 |

### 🧾 Total Number of Orders

> ### 📢 **3,510 Total Orders**

This KPI represents the total order count shown in the supplied dashboard. The metric can be used together with sales and quantity to understand overall transaction activity.

### 🎯 Promotion & Discount Analysis

The dashboard analyzes the average discount offered across promotion categories.

**🏷️ Promotion Categories**

| Icon | Promotion Category |
|:----:|--------------------|
| 🔥 | Weekend Flash Sale |
| 🧹 | Clearance Sale |
| ☀️ | Summer Sale |
| 🎉 | New Year Special |
| 🪔 | Festive Diwali |

**📊 Displayed Values**

| Promotion Category | Displayed Value |
|--------------------|:---------------:|
| 🔥 Weekend Flash Sale | **23K** |
| 🧹 Clearance Sale | **18K** |
| ☀️ Summer Sale | **7K** |
| 🎉 New Year Special | **3K** |
| 🪔 Festive Diwali | **0K** |

**🔍 Analysis**

The displayed dashboard shows **Weekend Flash Sale** with the highest value among the listed promotion categories.

> ⚠️ **Discount effectiveness should not be judged by discount size alone.**

A better evaluation is:

```text
   DISCOUNT
      ↓
 ADDITIONAL SALES
      ↓
 ADDITIONAL PROFIT
      ↓
  PROMOTION ROI
```

### ⚖️ Sales & Profit Relationship

The dashboard contains a visual showing the relationship between sales and profit.

| Main Variables |
|----------------|
| 💰 Sales / Net Sales |
| 📈 Profit |

**💼 Business Importance**

Understanding this relationship is useful because:

> ❗ **High sales do not automatically mean high profitability.**

Therefore, **sales and profit should be monitored together**.

### 📅 Sales Trend Analysis

The project analyzes sales over time. The dashboard supports time-based analysis such as:

| Granularity | Icon |
|-------------|:----:|
| Daily | 📆 |
| Monthly | 🗓️ |
| Quarterly | 📊 |
| Annual | 📅 |

*(where the date structure and available data support the selected level)*

**🎯 Purpose** — Time-series analysis helps identify:

`Growth` • `Decline` • `Peaks` • `Drops` • `Seasonal Behavior` • `High-Performing Periods` • `Low-Performing Periods`

---

# 🏆 PAGE 2 — Product Performance Analysis

The **Product Analysis** page provides a detailed comparison of products.

The dashboard evaluates products using:

```text
        💰 SALES
            │
            │
        📈 PROFIT
            │
            │
      📦 QUANTITY SOLD
```

This creates a more complete picture of product performance.

### 🏆 Top 5 Products by Sales

| Rank | Product | Sales |
|:----:|---------|------:|
| 🥇 | Apple iPhone 14 | **21.4M** |
| 🥈 | Apple MacBook Air | **19.6M** |
| 🥉 | Sony Bravia 55" TV | **19.4M** |
| 4️⃣ | Samsung Galaxy S21 | **15.3M** |
| 5️⃣ | HP Pavilion Laptop | **14.4M** |

> 📝 **Observation:** The displayed top-sales products are primarily **electronics**.

### 📉 Bottom 5 Products by Sales

| Rank | Product | Sales |
|:----:|---------|------:|
| 1 | Tupperware Lunch Box | 259K |
| 2 | L'Oréal Shampoo | 168K |
| 3 | Nivea Body Lotion | 83K |
| 4 | Dove Soap Pack | 81K |
| 5 | Colgate Toothpaste | 21K |

### 📦 Top 5 Products by Quantity Sold

| Rank | Product | Units Sold |
|:----:|---------|:----------:|
| 🥇 | Apple iPhone 14 | **281** |
| 🥈 | Raymond Suit | **274** |
| 🥉 | Fossil Smartwatch | **269** |
| 4️⃣ | Zara Casual Shirt | **269** |
| 5️⃣ | IFB Microwave Oven | **259** |

### 📉 Bottom 5 Products by Quantity Sold

| Rank | Product | Units Sold |
|:----:|---------|:----------:|
| 1 | Nivea Body Lotion | 219 |
| 2 | Tupperware Lunch Box | 215 |
| 3 | Milton Thermos Flask | 214 |
| 4 | Fabindia Kurta | 210 |
| 5 | Borosil Glass Set | 203 |

### 💰 Top 5 Products by Profit

| Rank | Product | Profit |
|:----:|---------|-------:|
| 🥇 | Apple iPhone 14 | **2.14M** |
| 🥈 | Apple MacBook Air | **1.96M** |
| 🥉 | Sony Bravia 55" TV | **1.94M** |
| 4️⃣ | Samsung Galaxy S21 | **1.53M** |
| 5️⃣ | HP Pavilion Laptop | **1.44M** |

### 📉 Bottom 5 Products by Profit

| Rank | Product | Profit |
|:----:|---------|-------:|
| 1 | Tupperware Lunch Box | 25.9K |
| 2 | L'Oréal Shampoo | 16.8K |
| 3 | Nivea Body Lotion | 8.3K |
| 4 | Dove Soap Pack | 8.1K |
| 5 | Colgate Toothpaste | 2.1K |

### 📊 Product Performance Matrix

```text
                    PRODUCT
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
        SALES        PROFIT      QUANTITY
          │            │            │
          └────────────┼────────────┘
                       ▼
              PRODUCT PERFORMANCE
```

### ❓ Why All Three Metrics Matter

A product can have:

| Scenario | Example Interpretation |
|----------|------------------------|
| 📈 High sales but low quantity | Premium / high-priced items |
| 📦 High quantity but low sales | Low-priced, high-volume items |
| 💎 High sales and high profit | Star products |
| ⚠️ High sales but lower profit | Discount-heavy or low-margin |
| 📉 Low sales and low profit | Underperformers |

> ✅ Therefore, evaluating **multiple metrics** provides better business understanding.

---

# ⚖️ PAGE 3 — Period Comparison

The **Period Comparison** page allows users to select two periods and compare their performance.

| Period | Description |
|--------|-------------|
| 🔵 **Period 1** | User-selected date range |
| 🟣 **Period 2** | User-selected date range |

### 📊 Comparison Metrics

| Metric | Icon | Description |
|--------|:----:|-------------|
| **Sales** | 💰 | Measures sales generated in each selected period |
| **Profit** | 📈 | Measures profit generated in each selected period |
| **Quantity Sold** | 📦 | Measures units sold during each selected period |

### 🔄 Period Comparison Framework

```text
                 PERIOD 1
                    │
           ┌────────┼────────┐
           ▼        ▼        ▼
         SALES    PROFIT   QUANTITY
           │        │        │
           └────────┼────────┘
                    │
                    ▼
              COMPARISON
                    ▲
                    │
           ┌────────┼────────┐
           ▼        ▼        ▼
         SALES    PROFIT   QUANTITY
           │        │        │
           └────────┼────────┘
                    │
                 PERIOD 2
```

### 🎯 Possible Comparisons

| Comparison Type | Icon |
|-----------------|:----:|
| Month vs Month | 🗓️ |
| Quarter vs Quarter | 📊 |
| Year vs Year | 📅 |
| Before vs After Promotion | 🔄 |
| Campaign vs Campaign | 📣 |
| Custom range vs Custom range | 🎛️ |

---

# 📋 PAGE 4 — Order-Level Analysis

The final page provides **detailed order-level information**. This allows users to move from summarized dashboard insights to individual transactions.

### 🎛️ Order-Level Filters

| Filter | Icon |
|--------|:----:|
| Date | 📅 |
| Product | 🛍️ |
| Customer ID | 👤 |
| Promotion Category | 🎯 |

### 📑 Order-Level Fields

The project requirements specify analysis of available order-level fields such as:

| # | Field | # | Field |
|---|-------|---|-------|
| 1 | Customer ID | 9 | Discount |
| 2 | Order ID | 10 | Discount Percentage |
| 3 | Date | 11 | Price Per Unit |
| 4 | Product | 12 | Units Sold |
| 5 | Product ID | 13 | Promotion ID |
| 6 | Sales | 14 | Promotion Category |
| 7 | Total Sales | 15 | City |
| 8 | Net Sales | 16 | Profit |

> ℹ️ *The exact fields shown depend on the available source dataset.*

### 🔎 Order-Level Analysis Flow

```text
    CUSTOMER
        ↓
      ORDER
        ↓
     PRODUCT
        ↓
      PRICE
        ↓
     DISCOUNT
        ↓
     NET SALES
        ↓
      PROFIT
        ↓
     QUANTITY
        ↓
    PROMOTION
```

This allows detailed investigation of individual sales transactions.

---

# 💡 Key Business Insights

### 🥇 Insight 1 — High-Value Products

The supplied dashboard shows several **electronics products** among the highest performers by sales and profit.

**Notable products:**

- 📱 Apple iPhone 14
- 💻 Apple MacBook Air
- 📺 Sony Bravia 55" TV
- 📱 Samsung Galaxy S21
- 💻 HP Pavilion Laptop

> These products are important contributors to the displayed business performance.

### 💰 Insight 2 — Sales and Profit Should Be Evaluated Together

The dashboard includes a **Sales vs Profit** relationship analysis. This prevents decisions from being based on revenue alone.

> ✅ A product with high sales should also be checked for its **contribution to profit**.

### 📦 Insight 3 — Quantity Gives a Different Perspective

Units sold can provide a **different view of product demand**.

> ⚠️ A product with a high quantity sold does **not necessarily** generate the highest sales value.

Therefore:

```text
Sales + Profit + Quantity = Stronger Product-Performance Perspective
```

### 📉 Insight 4 — Low Performers Require Investigation

Products appearing repeatedly in the bottom rankings should be reviewed before making decisions regarding:

| Area | Icon |
|------|:----:|
| Inventory | 📦 |
| Pricing | 🏷️ |
| Promotions | 🎯 |
| Product Positioning | 📊 |
| Marketing | 📣 |
| Availability | ✅ |

### 🎯 Insight 5 — Discount Size Alone Is Not Enough

A high discount may increase sales, but it can also **reduce profitability**.

Therefore, promotions should be evaluated based on:

```text
  Discount  →  Sales Increase  →  Profit Increase  →  ROI
```

### 🌍 Insight 6 — City-Level Analysis Supports Regional Strategy

Sales-by-city analysis helps identify **geographic differences** in business performance, supporting location-specific decisions.

### 📅 Insight 7 — Trend Analysis Supports Planning

Historical sales trends can help identify changes in business performance over time. This information can support:

- 🔮 Forecasting
- 📦 Inventory planning
- 📣 Marketing planning
- 🎯 Target setting

---

# 🚀 Business Recommendations

### 1️⃣ Strengthen High-Performing Products

Products consistently appearing in the top rankings should receive strategic attention.

**Recommended actions:**

- ✅ Maintain availability
- 👁️ Improve product visibility
- 🚫 Avoid unnecessary stock-outs
- 📊 Monitor demand
- 🎁 Support with targeted promotions

### 2️⃣ Investigate Low-Performing Products

For bottom-ranked products, investigate:

| Factor | Icon |
|--------|:----:|
| Customer demand | 👥 |
| Pricing | 🏷️ |
| Product visibility | 👁️ |
| Product availability | 📦 |
| Promotion effectiveness | 🎯 |
| Competition | ⚔️ |

> 🔍 **Low performance should be investigated before taking corrective action.**

### 3️⃣ Optimize Promotions

Promotions should be evaluated using **profitability** rather than discount alone.

**Recommended KPI:**

```text
             Incremental Profit
Promotion ROI = ──────────────────
               Promotion Cost
```

*(where appropriate data is available)*

### 4️⃣ Monitor Discount Impact

Track how changes in discount affect:

| Metric | Icon |
|--------|:----:|
| Sales | 💰 |
| Quantity | 📦 |
| Profit | 📈 |
| Net Sales | 📉 |

> This helps **avoid unnecessary discounting**.

### 5️⃣ Create City-Specific Strategies

Use sales-by-city performance to classify markets:

```text
   HIGH SALES
        ↓
  Maintain & Expand

   MEDIUM SALES
        ↓
   Growth Strategy

    LOW SALES
        ↓
 Investigate & Improve
```

### 6️⃣ Use Period Comparison for Regular Reviews

Management can use the comparison page for:

`Monthly Reviews` • `Quarterly Reviews` • `Annual Reviews` • `Campaign Evaluation` • `Promotion Evaluation`

### 7️⃣ Monitor Profit Alongside Revenue

A strong business dashboard should always consider:

```text
   SALES  +  PROFIT  +  QUANTITY
        (not sales alone)
```

---

# 📈 Recommended Additional KPIs

The project can be extended with:

| KPI | KPI | KPI |
|-----|-----|-----|
| `Profit Margin %` | `Average Order Value` | `Sales Growth %` |
| `Profit Growth %` | `Quantity Growth %` | `Average Discount %` |
| `Promotion ROI` | `City-wise Profit` | `Product Profit Margin` |
| `Year-over-Year Growth` | `Month-over-Month Growth` | `Customer Lifetime Value` |

---

# 🔮 Future Scope

<table>
<tr>
<td width="50%" valign="top">

### 🤖 Predictive Analytics
- Sales forecasting
- Demand forecasting
- Product demand prediction
- Trend prediction

### 👥 Customer Analytics
- Customer segmentation
- Customer lifetime value
- Repeat purchase rate
- Customer profitability
- Customer purchase behavior

</td>
<td width="50%" valign="top">

### 📦 Inventory Analytics
- Fast-moving products
- Slow-moving products
- Inventory turnover
- Stock-out analysis
- Reorder recommendations

### 🎯 Promotion Analytics
- Promotion ROI
- Campaign effectiveness
- Discount impact
- Promotion conversion
- Profit impact of promotions

### 🚨 Automated KPI Alerts
- Sales decline
- Profit decline
- Low-performing products
- High discount levels
- City-level decline
- Unusual transaction patterns

</td>
</tr>
</table>

---

# 🖼️ Dashboard Preview

### 📊 Sales Overview

<p align="center">
  <img src="Images/electrohub-overview.png" alt="Sales Overview Dashboard" width="850"/>
</p>

### 🏆 Product Performance

<p align="center">
  <img src="Images/electrohub-products.png" alt="Product Performance Dashboard" width="850"/>
</p>

### ⚖️ Period Comparison

<p align="center">
  <img src="Images/electrohub-comparison.png" alt="Period Comparison Dashboard" width="850"/>
</p>

### 📋 Order-Level Analysis

<p align="center">
  <img src="Images/electrohub-details.png" alt="Order Level Analysis Dashboard" width="850"/>
</p>

---

# 📁 Repository Structure

```text
ElectroHub_Sales_Analysis_PowerBI/
│
├── 📁 Dashboard/
│   └── ElectroHub_Sales_Analysis.pbix
│
├── 📁 Data/
│   └── ElectroHub_Sales_Data.xlsx
│
├── 📁 Images/
│   ├── electrohub-overview.png
│   ├── electrohub-products.png
│   ├── electrohub-comparison.png
│   └── electrohub-details.png
│
├── 📁 Documentation/
│   └── ElectroHub_Sales_Analysis_Report.pdf
│
├── 📄 README.md
└── 📄 LICENSE
```

---

# 📊 Project Features

| Feature | Status | | Feature | Status |
|---------|:------:|---|---------|:------:|
| 📊 Power BI Dashboard | ✅ | | 💸 Discount Analysis | ✅ |
| 💰 Sales Analysis | ✅ | | 🌍 City Analysis | ✅ |
| 📈 Profit Analysis | ✅ | | 📅 Time Trend Analysis | ✅ |
| 📦 Quantity Analysis | ✅ | | ⚖️ Sales vs Profit Analysis | ✅ |
| 🧾 Order Analysis | ✅ | | 🔄 Period Comparison | ✅ |
| 🏆 Top 5 Products | ✅ | | 🔎 Order-Level Details | ✅ |
| 📉 Bottom 5 Products | ✅ | | 🎛️ Interactive Filters | ✅ |
| 🎯 Promotion Analysis | ✅ | | 💡 Business Recommendations | ✅ |

---

# 🧠 Skills Demonstrated

<table>
<tr>
<td width="33%" valign="top">

### 📊 Data Analytics
- Data Cleaning
- Data Transformation
- Exploratory Data Analysis
- KPI Analysis
- Product Analysis
- Sales Analysis
- Profit Analysis
- Trend Analysis
- Comparative Analysis
- Business Insight Generation

</td>
<td width="33%" valign="top">

### 📈 Power BI
- Dashboard Development
- Power Query
- DAX
- Data Modeling
- KPI Cards
- Bar / Column Charts
- Line Charts
- Scatter Charts
- Maps & Tables
- Slicers & Filters
- Interactive Reporting

</td>
<td width="33%" valign="top">

### 💼 Business Intelligence
- Sales Performance Monitoring
- Profitability Analysis
- Product Performance
- Promotion Analysis
- Discount Analysis
- Geographic Analysis
- Time-Based Analysis
- Order-Level Analysis
- Period Comparison
- Decision Support

</td>
</tr>
</table>

---

# 📊 Analytical Metrics

The project focuses on:

```text
┌──────────────────────────┬──────────────────────────┐
│  Total Sales             │  Total Profit            │
│  Total Orders            │  Total Quantity Sold     │
│  Net Sales               │  Product Sales           │
│  Product Profit          │  Product Quantity        │
│  Discount                │  Discount Percentage     │
│  Average Discount        │  Promotion Category      │
│  City Sales              │  Sales Trend             │
│  Period Sales            │  Period Profit           │
│  Period Quantity         │  Order-Level Sales       │
│  Order-Level Profit      │  Order-Level Discount    │
└──────────────────────────┴──────────────────────────┘
```

---

# 🏆 Project Outcome

The project transforms transactional sales information into an **interactive Business Intelligence solution**.

Instead of manually reviewing individual transactions, users can quickly understand:

| Question | Meaning |
|:--------:|---------|
| **WHAT?** | Which products are performing? |
| **WHERE?** | Which cities generate sales? |
| **WHEN?** | How do sales change over time? |
| **HOW MUCH?** | What are the sales, profit and quantity levels? |
| **WHICH?** | Which products are top and bottom performers? |
| **HOW?** | How do discounts and promotions relate to performance? |
| **COMPARE?** | How does one selected period perform against another? |
| **DETAIL?** | What happened at the individual order level? |

---

# 🎯 Final Business Takeaway

The **ElectroHub Sales & Profit Performance Analysis** project demonstrates how Power BI can transform transactional data into an interactive analytical solution.

```text
     Data Cleaning
           +
  Data Transformation
           +
     Data Modeling
           +
          DAX
           +
  Data Visualization
           +
   Business Analysis
           ═══════════
  Business Intelligence Solution
```

The dashboard provides a structured way to analyze **sales, profitability, product performance, quantity, discounts, promotions, cities, time trends, period comparisons and individual orders**.

---

# 🌟 Portfolio Value

This project demonstrates practical **Data Analyst** and **Business Intelligence** skills including:

- ✅ Working with transactional datasets
- ✅ Preparing data for analysis
- ✅ Building Power BI dashboards
- ✅ Creating analytical measures
- ✅ Designing interactive visuals
- ✅ Performing product analysis
- ✅ Performing profitability analysis
- ✅ Analyzing sales trends
- ✅ Performing comparative analysis
- ✅ Creating business recommendations
- ✅ Communicating analytical findings

---

# 📄 Project Documentation

The repository can contain a complete project report:

```text
Documentation/
└── ElectroHub_Sales_Analysis_Report.pdf
```

### 📑 Report Contents

| # | Section | # | Section |
|---|---------|---|---------|
| 1 | Project Introduction | 11 | Promotion Analysis |
| 2 | Project Domain | 12 | Discount Analysis |
| 3 | Project Objectives | 13 | City Analysis |
| 4 | Analytical Procedure | 14 | Time-Series Analysis |
| 5 | Tools & Technologies | 15 | Period Comparison |
| 6 | Dashboard Overview | 16 | Order-Level Analysis |
| 7 | Sales Analysis | 17 | Key Insights |
| 8 | Product Analysis | 18 | Recommendations |
| 9 | Profit Analysis | 19 | Future Scope |
| 10 | Quantity Analysis | 20 | Conclusion |

---

# 🔗 Project Resources

| Resource | Link |
|----------|------|
| 📊 **Power BI Dashboard** | [`YOUR_POWER_BI_LINK`](YOUR_POWER_BI_LINK) |
| 💻 **GitHub Repository** | [`YOUR_GITHUB_REPOSITORY_LINK`](YOUR_GITHUB_REPOSITORY_LINK) |
| 📄 **Project Report** | `Documentation/ElectroHub_Sales_Analysis_Report.pdf` |

> 🔧 **Note:** Replace the placeholder links above with your actual published Power BI dashboard link and GitHub repository URL.

---

# ⭐ Project Highlights

```text
                    ⚡ ELECTROHUB
                          │
                          ▼
                 📊 POWER BI DASHBOARD
                          │
   ┌──────────┬───────────┼───────────┬──────────┐
   ▼          ▼           ▼           ▼          ▼
💰 Sales   📈 Profit   📦 Quantity  🏆 Product  🎯 Promotion
 Analysis   Analysis    Analysis    Ranking     Analysis
   │          │           │           │          │
   └──────────┴───────────┼───────────┴──────────┘
                          ▼
   ┌──────────┬───────────┼───────────┬──────────┐
   ▼          ▼           ▼           ▼          ▼
💸 Discount 🌍 City    📅 Trend    🔄 Period   🔎 Order
 Analysis   Analysis   Analysis   Comparison   Details
                          │
                          ▼
                  💡 BUSINESS INSIGHTS
                          │
                          ▼
                   🚀 RECOMMENDATIONS
```

---

# 👨‍💻 About the Author

<h3 align="center">Manish Kashyap</h3>

<p align="center">
  🎓 <b>B.Tech CSE — AI / ML / DL</b><br/>
  📊 <b>Aspiring Data Analyst</b>
</p>

### 🛠️ Technical Skills

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Statistics-4B8BBE?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Data%20Analytics-111827?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Data%20Visualization-7C3AED?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Machine%20Learning-FF6F00?style=for-the-badge"/>
</p>

### 🌐 Connect With Me

<p align="center">
  <a href="YOUR_LINKEDIN_URL">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="YOUR_GITHUB_URL">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="mailto:YOUR_EMAIL">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

---

# ⭐ Support

If you find this project useful:

<p align="center">
  ⭐ <b>Star the repository</b> &nbsp;•&nbsp;
  🍴 <b>Fork the repository</b> &nbsp;•&nbsp;
  💬 <b>Share your feedback</b>
</p>

---

<h2 align="center">🙏 Thank You</h2>

<p align="center">
  Thank you for taking the time to explore my<br/>
  <b>⚡ ElectroHub Sales & Profit Performance Analysis</b>
</p>

<p align="center">
  <i>This project demonstrates how transactional data can be transformed into meaningful insights using Power BI.</i>
</p>

<br/>

<p align="center">
  📊 <b>Analyze Data</b> &nbsp;•&nbsp;
  💡 <b>Discover Insights</b> &nbsp;•&nbsp;
  🚀 <b>Drive Better Decisions</b>
</p>

<br/>

<h3 align="center">
  ⚡ ElectroHub Sales & Profit Performance Analysis | Power BI ⚡
</h3>

<p align="center">
  <i>Turning Data into Insights • Insights into Decisions • Decisions into Growth</i>
</p>

<br/>

<p align="center">
  <a href="#-electrohub-sales--profit-performance-analysis">
    <img src="https://img.shields.io/badge/⬆%20Back%20to%20Top-111827?style=for-the-badge"/>
  </a>
</p>

---

<p align="center">
  <sub>© 2025 Manish Kashyap • Built with ❤️ using Power BI</sub>
</p>