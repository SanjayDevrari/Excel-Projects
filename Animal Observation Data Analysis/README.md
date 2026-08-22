# 🐾 Animal Observation Data Analysis

An Excel-based **Data Analytics project** focused on cleaning, transforming, analyzing, and visualizing animal observation data.

This project demonstrates an end-to-end Excel workflow:

**Raw Data → Data Cleaning → Data Transformation → Pivot Table Analysis → Data Visualization → Dashboard**

---

## 📌 Project Overview

The dataset contains **1,011 animal observation records** with information such as animal type, country, weight, body length, gender, location, observation date, and data compiler.

The main objective of this project was to take the raw dataset, clean and transform it using Excel, extract meaningful information, analyze it using formulas and Pivot Tables, and finally present the insights through an interactive dashboard.

---

## 📂 Dataset Columns

The original dataset contains 11 columns:

1. **Animal Type**
2. **Country**
3. **Weight (kg)**
4. **Body Length (cm)**
5. **Gender**
6. **Animal Code**
7. **Latitude**
8. **Longitude**
9. **Animal Name**
10. **Observation Date**
11. **Data Compiled By**

---

# 📑 Workbook Structure

The Excel workbook contains **4 sheets**:

```text
Animal Observation Data Analysis.xlsx
│
├── Raw Animal Data
├── Clean Animal Data
├── Pivot Table
└── Dashboard
```

---

## 1️⃣ Raw Animal Data

This sheet contains the original dataset.

### Purpose

* Preserve the original data
* Keep the raw dataset unchanged
* Use it as the source for the cleaning process

The raw data contains **1,011 observations** across 11 columns.

---

## 2️⃣ Clean Animal Data

This sheet contains the cleaned and analysis-ready dataset.

### 🧹 Data Cleaning Performed

Several data-cleaning techniques were applied, including:

* Identifying missing values
* Checking duplicate records
* Removing unnecessary spaces
* Standardizing text values
* Checking numerical data
* Checking date values
* Validating latitude and longitude
* Standardizing categorical values such as gender
* Checking inconsistent or invalid records

### 🛠️ Excel Functions Used

Some of the Excel functions used during the cleaning and transformation process include:

```text
TRIM()
CLEAN()
PROPER()
VALUE()
IF()
IFS()
AND()
OR()
IFERROR()
```

---

# ➕ New Columns Created

To make the dataset more useful for analysis, additional columns were created from the existing data.

### 📅 Observation Year

Extracted the year from the observation date.

```excel
=YEAR([@[Observation date]])
```

### 📅 Observation Month

Extracted the month from the observation date.

```excel
=TEXT([@[Observation date]],"mmmm")
```

### 📊 Observation Quarter

Created quarterly categories such as:

```text
Q1
Q2
Q3
Q4
```

### ⚖️ Weight Category

Animals were grouped into weight categories based on their recorded weight.

### 📏 Body Length Category

Animals were grouped into different body-length categories.

### 📍 Location Status

Latitude and longitude values were checked to identify valid and invalid geographic records.

### ✅ Data Quality Status

A status column was created to help identify records that required further review.

These additional columns made the dataset more suitable for analysis and visualization.

---

# 3️⃣ Pivot Table

After cleaning and transforming the data, Pivot Tables were created to summarize the dataset and identify meaningful patterns.

### 📊 Analysis Performed

The Pivot Table sheet includes analysis such as:

* Country-wise observations
* Animal-wise observations
* Gender-wise observations
* Average animal weight
* Average body length
* Observation trends
* Country and animal comparisons

Pivot Tables were used to quickly summarize large amounts of data and prepare it for visualization.

---

# 4️⃣ 📊 Dashboard

The final dashboard presents the important findings from the dataset in a visual and easy-to-understand format.

### Dashboard Components

The dashboard includes:

* **Total Observations**
* **Total Countries**
* **Total Animal Types**
* **Average Weight**
* **Average Body Length**
* Country-wise observation visualization
* Animal-wise observation visualization
* Gender distribution
* Observation trends
* Weight vs Body Length analysis

### 📈 Visualization Techniques

Different charts were used depending on the type of analysis, including:

* Bar Charts
* Column Charts
* Line Charts
* Pie/Donut Charts
* Scatter Charts

The purpose of the dashboard is to turn the cleaned data and analytical results into meaningful visual insights.

---

# 🧠 Key Excel Skills Demonstrated

This project helped me practice and apply:

### Data Cleaning

* Removing inconsistencies
* Handling missing values
* Standardizing text
* Checking duplicates
* Validating numerical and date data

### Excel Formulas

```text
SUM
AVERAGE
MIN
MAX
COUNT
COUNTA
COUNTIF
COUNTIFS
SUMIF
SUMIFS
AVERAGEIF
AVERAGEIFS
IF
IFS
TRIM
CLEAN
PROPER
VALUE
YEAR
MONTH
TEXT
```

### Data Analysis

* Formula-based analysis
* Conditional analysis
* Category-based analysis
* Date-based analysis
* Numerical analysis

### Data Visualization

* Pivot Tables
* Charts
* Dashboard design
* KPI cards
* Data storytelling

---

# 🔄 Data Analytics Workflow

The complete workflow used in this project:

```text
Raw Animal Data
       ↓
Data Cleaning
       ↓
Data Transformation
       ↓
New Analytical Columns
       ↓
Formula-Based Analysis
       ↓
Pivot Table Analysis
       ↓
Data Visualization
       ↓
Dashboard
```

---

# 🎯 Project Objective

The main goal of this project was not just to create an Excel dashboard.

It was to practice the complete process of turning **raw data into meaningful insights** using Excel.

Through this project, I practiced how to:

> **Clean → Transform → Analyze → Visualize → Communicate**

---

# 🚀 Future Improvements

This project can be further improved by adding:

* Interactive slicers
* More advanced dashboard filters
* Additional KPIs
* More detailed geographic analysis
* Advanced statistical analysis
* Automated reports
* Additional visualizations

---

# 🛠️ Tools Used

* **Microsoft Excel**
* Excel Formulas
* Pivot Tables
* Excel Charts
* Data Visualization
* Dashboard Design


## 👨‍💻 Project Status

**Completed:** Data Cleaning, Data Transformation, Pivot Table Analysis & Dashboard Visualization

This project was created as part of my journey to learn **Excel for Data Analytics** and build practical data-analysis projects.

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.
