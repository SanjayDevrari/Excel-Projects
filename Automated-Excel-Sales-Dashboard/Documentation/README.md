# 📊 Automated Excel Dashboard — Retail Sales Performance

## 📌 Project Overview

The **Automated Excel Dashboard** is a business-oriented data analysis project designed to transform raw retail sales data into an **interactive and automated Excel dashboard**.

The project uses **Excel Tables, formulas, Pivot Tables, Pivot Charts, Slicers, Timeline, and data visualization techniques** to help business users monitor sales performance and make data-driven decisions.

The main objective is to create a dashboard where users can filter the data and instantly see updated **KPIs, charts, trends, and business insights** without manually modifying the report.

---

# 🎯 Project Goal

The primary goal of this project is to build a **professional and interactive Retail Sales Dashboard in Excel** that can help management understand the company's sales performance.

The dashboard should allow users to:

* Monitor overall sales performance
* Track total sales and profit
* Analyze monthly sales trends
* Identify top-performing products
* Compare category performance
* Compare regional performance
* Evaluate salesperson performance
* Analyze order and quantity trends
* Understand the impact of discounts on profit
* Filter the entire dashboard using Slicers and Timeline
* Automatically update KPIs and charts when filters are applied

### Final Objective

> **Convert raw retail transaction data into an interactive business intelligence dashboard using Excel.**

---

# ❗ Problem Statement

A retail company collects a large amount of sales transaction data containing information about orders, customers, products, categories, regions, salespeople, sales amounts, quantities, discounts, and profits.

However, the company currently relies on **raw Excel data and manually prepared reports**.

This creates several problems:

### 1. Difficult to understand raw data

The raw dataset contains hundreds or thousands of transactions, making it difficult for management to quickly understand overall performance.

### 2. Time-consuming manual reporting

Creating monthly sales reports, category reports, regional reports, and salesperson reports manually requires significant time and effort.

### 3. No interactive analysis

Users cannot easily filter the report by:

* Region
* Category
* Product
* Salesperson
* Payment Method
* Date

### 4. Important KPIs are not easily visible

Management needs quick access to important metrics such as:

* Total Sales
* Total Profit
* Total Orders
* Total Quantity
* Average Order Value
* Profit Margin

But these metrics are not available in one centralized report.

### 5. Difficult to identify trends and problems

Without proper visualization, it is difficult to identify:

* Sales growth or decline
* Best-performing categories
* Poor-performing regions
* Top products
* Low-performing salespeople
* Seasonal sales patterns
* High-discount transactions

### 6. Lack of data-driven decision making

Because the information is not presented in a clear and interactive format, management may find it difficult to make quick and informed business decisions.

---

# 💡 Proposed Solution

To solve these problems, this project will create an **Automated Retail Sales Dashboard using Excel**.

The solution will follow this workflow:

```text
Raw Sales Data
      ↓
Data Validation & Cleaning
      ↓
Excel Table
      ↓
Calculated Columns
      ↓
Pivot Tables
      ↓
Pivot Charts
      ↓
Slicers & Timeline
      ↓
Interactive Dashboard
      ↓
Business Insights
```

The final dashboard will provide management with a single place to monitor and analyze sales performance.

---

# 🏢 Business Scenario

Imagine a retail company that sells products across multiple regions.

The company records every transaction in an Excel dataset.

Each transaction contains information such as:

* Order ID
* Order Date
* Customer
* Region
* State
* Category
* Product
* Quantity
* Sales
* Discount
* Profit
* Payment Method
* Salesperson

Management wants to understand:

> **"How is our retail business performing, where are we making the most money, and which areas need improvement?"**

This dashboard will answer these questions.

---

# 🔎 Key Business Questions

The dashboard should answer the following questions:

### Overall Performance

1. What are the total sales?
2. What is the total profit?
3. How many orders were received?
4. What is the total quantity sold?
5. What is the average order value?
6. What is the overall profit margin?

### Time Analysis

7. How are sales changing month by month?
8. Which month generated the highest sales?
9. Which month generated the highest profit?
10. Are there any noticeable seasonal trends?

### Product Analysis

11. Which products generate the highest sales?
12. Which products generate the highest profit?
13. Which products are underperforming?

### Category Analysis

14. Which category generates the highest revenue?
15. Which category generates the highest profit?
16. Which categories have low profit margins?

### Regional Analysis

17. Which region generates the highest sales?
18. Which region generates the highest profit?
19. Which region has the best profit margin?

### Salesperson Analysis

20. Which salesperson generates the highest sales?
21. Which salesperson generates the highest profit?
22. Which salespeople are underperforming?

### Discount Analysis

23. How does discounting affect profit?
24. Are highly discounted products generating lower profits?

---

# 📂 Dataset Structure

The raw dataset should contain fields similar to:

| Column         | Description                       |
| -------------- | --------------------------------- |
| Order ID       | Unique identifier for each order  |
| Order Date     | Date of the transaction           |
| Customer       | Customer name/ID                  |
| Region         | Sales region                      |
| State          | Customer state                    |
| Category       | Product category                  |
| Product        | Product name                      |
| Quantity       | Number of units sold              |
| Sales          | Total sales amount                |
| Discount       | Discount applied to the order     |
| Profit         | Profit generated                  |
| Payment Method | Payment method used               |
| Salesperson    | Employee responsible for the sale |

---

# 🧹 Data Cleaning Requirements

Before creating the dashboard, the raw data should be checked for:

* Missing values
* Duplicate Order IDs
* Incorrect dates
* Incorrect data types
* Invalid quantities
* Invalid sales values
* Invalid profit values
* Inconsistent category names
* Inconsistent region names
* Extra spaces
* Incorrect formatting

The original **Raw Data** should remain unchanged.

A separate **Clean Data** sheet should be created for analysis.

---

# 🧮 Calculated Fields

Additional columns may be created where required.

### Profit Margin

```excel
=Profit/Sales
```

### Year

```excel
=YEAR(Order_Date)
```

### Month

```excel
=TEXT(Order_Date,"mmm")
```

### Year-Month

```excel
=TEXT(Order_Date,"yyyy-mm")
```

### Average Order Value

```text
Total Sales / Total Orders
```

Additional calculated fields can be created if they provide meaningful business insights.

---

# 📊 Key Performance Indicators (KPIs)

The dashboard should contain the following main KPIs:

| KPI                 | Purpose                                  |
| ------------------- | ---------------------------------------- |
| Total Sales         | Measures total revenue generated         |
| Total Profit        | Measures overall profitability           |
| Total Orders        | Measures number of orders                |
| Total Quantity      | Measures units sold                      |
| Average Order Value | Measures average revenue per order       |
| Profit Margin       | Measures profitability relative to sales |

Example:

```text
┌──────────────┬──────────────┬──────────────┐
│ TOTAL SALES  │ TOTAL PROFIT │ TOTAL ORDERS │
│ ₹XX,XX,XXX   │ ₹X,XX,XXX    │ XXXX         │
├──────────────┼──────────────┼──────────────┤
│ QUANTITY     │ AVG ORDER    │ PROFIT MARGIN │
│ XXXX         │ ₹X,XXX       │ XX.X%        │
└──────────────┴──────────────┴──────────────┘
```

---

# 📈 Dashboard Visualizations

The dashboard should contain a limited number of meaningful visuals.

### 1. Monthly Sales Trend

**Chart:** Line Chart

Purpose:

> Identify sales growth, decline, and seasonal patterns.

---

### 2. Sales by Category

**Chart:** Column/Bar Chart

Purpose:

> Identify the highest and lowest-performing product categories.

---

### 3. Profit by Region

**Chart:** Bar Chart

Purpose:

> Compare profitability across regions.

---

### 4. Top 10 Products

**Chart:** Horizontal Bar Chart

Purpose:

> Identify products generating the highest sales.

---

### 5. Salesperson Performance

**Chart:** Column/Bar Chart

Purpose:

> Compare sales and profit generated by salespeople.

---

### 6. Payment Method Analysis

**Chart:** Column/Donut Chart

Purpose:

> Understand how customers are paying for purchases.

---

# 🎛️ Dashboard Interactivity

The dashboard should contain interactive **Slicers**.

Recommended slicers:

* Region
* Category
* Salesperson
* Payment Method
* Product

A **Timeline** should also be added for:

* Order Date

Example:

```text
Region
[North] [South] [East] [West]

Category
[Electronics] [Furniture] [Clothing]

Salesperson
[A] [B] [C] [D]

Year / Month
[Timeline]
```

When the user changes a filter:

> **KPIs + Pivot Tables + Pivot Charts should update automatically.**

---

# ⚙️ Automation Requirement

The dashboard should minimize manual work.

After new data is added to the source table:

1. The Excel Table should expand automatically.
2. Calculated columns should extend automatically where applicable.
3. Pivot Tables should be refreshable.
4. Pivot Charts should reflect updated data.
5. Slicers should continue to work.
6. Dashboard KPIs should update after refresh.

The goal is to create a **reusable reporting system**, not just a static dashboard.

---

# 📑 Recommended Workbook Structure

The final Excel workbook should contain:

```text
Retail_Sales_Dashboard.xlsx

│
├── README
│
├── Raw Data
│
├── Clean Data
│
├── Calculations
│
├── Pivot Tables
│
└── Dashboard
```

### Raw Data

Original dataset.

### Clean Data

Cleaned and analysis-ready dataset.

### Calculations

Additional calculations and supporting metrics.

### Pivot Tables

All Pivot Tables used to generate dashboard visuals.

### Dashboard

Final interactive report for the business user.

### README

Project documentation and instructions.

---

# 🎨 Dashboard Design Requirements

The dashboard should be:

* Clean
* Professional
* Easy to understand
* Interactive
* Consistent
* Not overcrowded

The dashboard should follow a clear hierarchy:

```text
Title
  ↓
KPI Cards
  ↓
Main Trend
  ↓
Category / Region Analysis
  ↓
Product / Salesperson Analysis
  ↓
Filters
```

Avoid adding charts just for decoration.

Every visual should answer a specific business question.

---

# 💼 Expected Business Insights

After completing the dashboard, the analysis should identify insights such as:

* Highest revenue-generating category
* Most profitable region
* Top-selling product
* Highest-performing salesperson
* Lowest-performing category
* Best sales month
* Best profit month
* Relationship between discounts and profit
* Important sales trends
* Areas requiring business attention

The exact insights will depend on the dataset.

---

# 🛠️ Tools & Excel Features

### Primary Tool

**Microsoft Excel**

### Features Used

* Excel Tables
* Data Validation
* Conditional Formatting
* Excel Formulas
* Pivot Tables
* Pivot Charts
* Slicers
* Timeline
* Dashboard Design
* Data Visualization

### Optional Advanced Features

* Power Query
* Dynamic Arrays
* Advanced Excel formulas

> VBA is intentionally not the primary focus of this project because VBA will be demonstrated separately in the **VBA Report Automation** project.

---

# 📌 Project Deliverables

The final project should contain:

### 1. Excel Dashboard

A fully interactive `.xlsx` workbook.

### 2. Clean Dataset

Analysis-ready data.

### 3. Pivot Analysis

Supporting Pivot Tables.

### 4. Business Dashboard

Interactive KPI and visualization dashboard.

### 5. Business Insights

A summary of important findings.

### 6. Documentation

README explaining:

* Problem
* Solution
* Methodology
* KPIs
* Dashboard
* Insights
* Tools

---

# ✅ Success Criteria

The project will be considered successful if:

* [ ] Raw data is preserved
* [ ] Data is cleaned properly
* [ ] Excel Table is used
* [ ] Required calculations are correct
* [ ] KPIs are accurate
* [ ] Pivot Tables are created
* [ ] Pivot Charts are created
* [ ] Slicers work correctly
* [ ] Timeline works correctly
* [ ] Dashboard updates after filtering
* [ ] Dashboard is visually professional
* [ ] Business questions are answered
* [ ] Key insights are documented
* [ ] Workbook is easy for another user to operate

---

# 🎯 Final Outcome

The final product should not look like a simple Excel report.

It should look and behave like a **small Business Intelligence reporting system built completely in Excel**.

The user should be able to open the workbook, select filters, and immediately understand:

> **How much the company is selling, how much it is earning, which products and categories are performing well, which regions are profitable, and where management should focus its attention.**

---

# 🚀 Project Workflow

```text
                    BUSINESS PROBLEM
                           ↓
                    RAW SALES DATA
                           ↓
                   DATA CLEANING
                           ↓
                   DATA VALIDATION
                           ↓
                   CALCULATED FIELDS
                           ↓
                    KPI CALCULATIONS
                           ↓
                     PIVOT TABLES
                           ↓
                     PIVOT CHARTS
                           ↓
                    SLICERS + TIMELINE
                           ↓
                 INTERACTIVE DASHBOARD
                           ↓
                  BUSINESS INSIGHTS
                           ↓
                 FINAL RECOMMENDATIONS
```

---

# 📚 Skills Demonstrated

This project demonstrates practical knowledge of:

* Microsoft Excel
* Data Cleaning
* Data Analysis
* Excel Tables
* Excel Formulas
* Pivot Tables
* Pivot Charts
* Slicers
* Timeline
* KPI Development
* Data Visualization
* Dashboard Development
* Business Intelligence
* Business Problem Solving
* Data-Driven Decision Making

---

# 👨‍💻 Portfolio Purpose

This project is part of a broader **Data Analytics Freelancing Portfolio**.

It is specifically designed to demonstrate that advanced Excel can be used to create:

> **Interactive + Automated + Business-focused dashboards without relying on Power BI.**

This project complements the Power BI projects in the portfolio by demonstrating strong Excel-based analytical and reporting capabilities.
