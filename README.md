# 📊 Power BI – Complete Concepts (Theory + Examples)

This repository provides **end-to-end Power BI knowledge**, covering **theory, concepts, and practical examples**. It is ideal for **beginners, students, and data analyst interview preparation**.

---

## 🔹 What is Power BI?

Power BI is a **Business Intelligence (BI) tool by Microsoft** used to **collect, transform, analyze, and visualize data** to generate interactive reports and dashboards.

**Main Uses:**

* Data Analysis
* Business Reporting
* Decision Making
* KPI Tracking

---

## 🔹 Components of Power BI

### 1️⃣ Power BI Desktop

* Used to create reports and data models
* Free desktop application

### 2️⃣ Power BI Service (Cloud)

* Used to publish, share, and collaborate
* Web-based platform

### 3️⃣ Power BI Mobile App

* View dashboards on mobile devices

### 4️⃣ Power BI Gateway

* Connect on‑premise data to cloud

---

## 🔹 Power BI Workflow

1. Connect to Data Source
2. Transform Data (Power Query)
3. Data Modeling
4. Create Visualizations
5. Publish to Power BI Service
6. Share Dashboard

---

## 🔹 Data Sources in Power BI

### Common Data Sources

* Excel
* CSV
* SQL Server
* MySQL
* PostgreSQL
* SharePoint
* Web APIs
* Azure Services

**Example:**

> Import sales data from Excel to analyze monthly revenue

---

## 🔹 Power Query (ETL Process)

Power Query is used for **Extract, Transform, Load (ETL)** operations.

### Common Transformations

* Remove duplicates
* Filter rows
* Change data types
* Merge queries
* Append queries
* Split columns

**Example:**

> Cleaning raw sales data by removing null values and formatting dates

---

## 🔹 Data Modeling

Data modeling defines relationships between tables.

### Relationship Types

* One-to-One
* One-to-Many (Most common)
* Many-to-Many

### Cardinality & Cross Filter Direction

* Single
* Both

**Example:**

> Orders table linked to Customers table using CustomerID

---

## 🔹 Star Schema vs Snowflake Schema

### ⭐ Star Schema

* Fact table in center
* Dimension tables around
* Faster performance

### ❄ Snowflake Schema

* Normalized dimension tables
* More complex

---

## 🔹 DAX (Data Analysis Expressions)

DAX is used for **calculations, measures, and KPIs**.

### Types of DAX

* Calculated Columns
* Measures
* Calculated Tables

---

## 🔹 Common DAX Functions

### Aggregation

* SUM()
* AVERAGE()
* COUNT()

### Logical

* IF()
* SWITCH()

### Filter

* CALCULATE()
* FILTER()
* ALL()

### Time Intelligence

* TOTALYTD()
* SAMEPERIODLASTYEAR()
* DATEADD()

**Example:**

> Total Sales = SUM(Orders[SalesAmount])

---

## 🔹 Measures vs Calculated Columns

| Feature     | Measure            | Calculated Column |
| ----------- | ------------------ | ----------------- |
| Computation | On the fly         | Stored in table   |
| Use Case    | KPIs, Aggregations | Row-level logic   |

---

## 🔹 Visualizations in Power BI

### Common Visuals

* Table
* Matrix
* Bar Chart
* Column Chart
* Line Chart
* Pie Chart
* Card
* KPI
* Slicer
* Map

**Example:**

> Card visual showing Total Revenue

---

## 🔹 KPIs & Cards

### KPI Components

* Indicator
* Target
* Trend

**Example:**

> Sales Target vs Actual Sales

---

## 🔹 Filters & Slicers

### Filter Levels

* Visual Level
* Page Level
* Report Level

### Slicers

* Date slicer
* Dropdown slicer

---

## 🔹 Drill Down & Drill Through

* Drill Down: Navigate within hierarchy
* Drill Through: Navigate to detailed report page

---

## 🔹 Tooltips

Custom tooltips show extra details when hovering over visuals.

**Example:**

> Hover over bar chart to view profit margin

---

## 🔹 Power BI Dashboard vs Report

| Feature       | Report   | Dashboard   |
| ------------- | -------- | ----------- |
| Pages         | Multiple | Single Page |
| Interactivity | High     | Limited     |
| Creation      | Desktop  | Service     |

---

## 🔹 Row Level Security (RLS)

Restricts data access for users.

**Example:**

> Salesperson sees only their region data

---

## 🔹 Refresh Types

* Manual Refresh
* Scheduled Refresh
* Incremental Refresh

---

## 🔹 Performance Optimization

* Use Star Schema
* Reduce columns
* Use measures instead of columns
* Avoid unnecessary visuals

---

## 🔹 Power BI Service

### Features

* Publish reports
* Create dashboards
* Share with users
* Set refresh schedule

---

## 🔹 Power BI Interview Questions Topics

* DAX vs SQL
* Measures vs Calculated Columns
* CALCULATE function
* Star Schema
* RLS
* Performance tuning

---

## 🔹 Real-Time Use Case Examples

* Sales Dashboard
* HR Analytics
* Finance Reporting
* Marketing Campaign Analysis
* Supply Chain Dashboard

---

## 🔹 Tools Used

* Power BI Desktop
* SQL
* Excel
* DAX

---

## 🔹 Who Should Use This Repository?

* Data Analyst Freshers
* Students
* Interview Preparation
* Power BI Learners

---


---

⭐ If you find this repository useful, give it a **star** and share it!
