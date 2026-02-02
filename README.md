# Hospitality Revenue Analysis using Power BI

## Project Overview

This project demonstrates an end-to-end **industry-standard data analytics workflow** focused on the **hospitality domain**, using **Power BI** as the primary analytics and visualization tool.

The objective of this project is to analyze hotel performance data and generate actionable insights related to:

* Revenue performance
* Occupancy trends
* Pricing strategy
* Customer behavior
* Operational efficiency

This project closely simulates how **real-world data analysts** work with hospitality chains, revenue managers, and business stakeholders by transforming raw booking data into **interactive dashboards and business insights**.

---

## Business Problem

The hospitality chain operates multiple hotels across different cities and room categories. Management faces challenges in:

* Tracking overall revenue and key performance metrics
* Identifying underperforming hotels and room categories
* Understanding weekday vs weekend performance
* Evaluating pricing effectiveness (ADR, RevPAR)
* Monitoring realization and cancellation behavior

Due to data being spread across multiple tables, decision-making becomes difficult without a consolidated analytical view.

---

## Solution Approach

### Step 1: Data Understanding & Modeling

* Analyzed raw booking, hotel, room, and date data
* Designed a **star schema data model**
* Created proper relationships between fact and dimension tables
* Ensured one-to-many relationships for accurate aggregations

---

### Step 2: Data Cleaning & Transformation (Power Query)

Performed essential data preparation steps:

* Removed unnecessary columns
* Standardized column names
* Fixed data types
* Handled missing and invalid values

This ensured clean and reliable data for analysis.

---

### Step 3: Feature Engineering & DAX Measures

Created calculated columns and measures using **DAX**.

#### Calculated Columns

* Week Number
* Day Type (Weekday / Weekend)

  * Friday and Saturday treated as weekends based on business logic

#### Key Measures

* Total Revenue
* Total Bookings
* Total Capacity
* Successful Bookings
* Occupancy %
* ADR (Average Daily Rate)
* RevPAR (Revenue per Available Room)
* Realization %
* Cancellation %
* Week-on-Week Change Metrics

All measures were validated for correctness and business relevance.

---

### Step 4: Dashboard Development (Power BI)

Built a fully interactive Power BI dashboard designed for business stakeholders.

#### Dashboard KPIs

* Revenue
* Occupancy %
* ADR
* RevPAR
* Realization %
* Cancellation %

#### Visualizations Included

* KPI cards with week-on-week trends
* Property-level performance table
* Line charts for revenue and ADR trends
* Donut charts for room category and booking platform distribution
* Conditional formatting for performance comparison
* Custom tooltips for weekly analysis

---

## Key Business Questions Answered

1. Which hotels are underperforming in terms of revenue and occupancy?
2. How does weekday vs weekend performance differ?
3. Is ADR changing dynamically or remaining flat?
4. Which properties have low realization or high cancellation rates?
5. How do ratings correlate with occupancy and revenue?
6. Which cities and room categories drive maximum revenue?

---

## Key Insights

* Several properties show **low occupancy despite competitive ADR**, indicating demand-side issues
* ADR remains relatively flat, highlighting **lack of dynamic pricing strategy**
* Higher-rated hotels consistently achieve better occupancy
* Certain properties have **high cancellation rates**, impacting realization
* Weekends outperform weekdays across most cities

---

## Tech Stack Used

| Tool        | Purpose                          |
| ----------- | -------------------------------- |
| Power BI    | Data modeling, DAX, dashboards   |
| Power Query | Data cleaning and transformation |
| DAX         | Measures and calculated columns  |
| CSV Files   | Raw data sources                 |

---

## Project Workflow

1. Understand business requirements
2. Load and clean raw data
3. Build star schema data model
4. Create DAX measures and calculated columns
5. Design interactive dashboard
6. Generate business insights and recommendations

---

## Files in This Repository

* **`Hospitality_Analysis.pbix`** *(Power BI Dashboard)*
* **`fact_bookings.csv`**
* **`fact_aggregated_bookings.csv`**
* **`dim_hotels.csv`**
* **`dim_rooms.csv`**
* **`dim_date.csv`**

---

## Power BI Dashboard (Published)

**Power BI Service Link:**
*https://app.powerbi.com/groups/me/reports/962947d8-56e2-455c-9a60-458caea3eaee/87ec79525eb381d99c55?experience=power-bi*

> Note: Use this link to access the interactive dashboard online via Power BI Service.

---

---

## Business Recommendations

* Introduce dynamic pricing strategies for weekdays
* Improve service quality for low-rated properties
* Focus marketing efforts on high-potential cities
* Reduce cancellations through better booking policies
* Optimize room category pricing based on demand

---

## What This Project Demonstrates

This project reflects **real company-level hospitality analytics work**, including:

* Business requirement translation
* Data modeling and DAX
* KPI-driven dashboard design
* Stakeholder-focused insights
* Revenue and occupancy optimization analysis

---

## Author

**Prashant Gautam**

B.Tech, Electronics and Communication Engineering
IIT (ISM) Dhanbad

Aspiring Data Analyst | Power BI | SQL | Python | Excel | Business Analytics

---

