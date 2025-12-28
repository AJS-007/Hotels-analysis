
# AtliQ Hotels Data Analysis Project

## Project Overview

This project focuses on a comprehensive analysis of booking and revenue data for **AtliQ Hotels** with the objective of deriving actionable business insights. The analysis covers the complete data lifecycle — from raw data ingestion to insight generation — using structured datasets that reflect real-world hotel operations.

The project is designed to demonstrate **industry-standard data analysis practices**, including data cleaning, transformation, metric engineering, and analytical reasoning. While the domain is hospitality, the techniques applied are equally relevant to **People Analytics, HR Analytics, and enterprise reporting**.

---

## Datasets Used

The analysis is based on five CSV files:

* `dim_date.csv` – Calendar and date-related attributes
* `dim_hotels.csv` – Hotel and property-level details
* `dim_rooms.csv` – Room category information
* `fact_bookings.csv` – Transaction-level booking data
* `fact_aggregated_bookings.csv` – Pre-aggregated booking metrics

These datasets were integrated to create a unified analytical model.

---

## Analysis Workflow

### 1. Data Import and Exploration

* Imported all datasets into the analysis environment.
* Reviewed schema, data types, and relationships between tables.
* Identified key dimensions and measures relevant to hotel performance.
* Explored booking platform distribution and booking patterns across properties and cities.

---

### 2. Data Cleaning and Validation

* Removed records with **invalid guest counts** (zero or negative values).
* Detected and eliminated **revenue outliers** using statistical boundaries to avoid skewed insights.
* Addressed missing values and corrected inconsistencies in aggregated booking data.
* Ensured referential integrity between fact and dimension tables.

---

### 3. Data Transformation and Feature Engineering

* Calculated **occupancy percentage** for each property based on room capacity and bookings.
* Standardized occupancy metrics by converting them into percentage values.
* Merged room, hotel, and booking datasets to enable multi-level analysis.
* Enabled analysis by **room category, city, hotel, booking platform, and date**.

---

### 4. Insight Generation and Analysis

* Analyzed **revenue performance** by city and booking platform.
* Evaluated **average revenue realized** across different room types.
* Compared **occupancy rates** across cities and room categories.
* Identified trends and performance differences between booking platforms.
* Highlighted high-performing and underperforming segments to support data-driven decision-making.

---

## Key Business Insights

* Clear variation in revenue and occupancy across cities and room categories.
* Certain booking platforms consistently outperform others in revenue realization.
* Premium room categories generate higher revenue but show differing occupancy patterns.
* City-level analysis reveals demand concentration and seasonality effects.

---

## Relevance to People Analytics and HR Analytics

Although the project is based on hotel data, the analytical approach directly maps to HR and People Analytics use cases:

* **Data Integration**: Combining multiple HR data sources (employee, performance, attendance) to build unified employee profiles.
* **Data Quality Management**: Applying validation rules to ensure accuracy in HR systems.
* **Metric Analysis**: Translating business KPIs into HR metrics such as productivity, engagement, and attrition.
* **Decision Support**: Using analytical insights to support workforce planning and strategic HR decisions.
* **Visualization and Reporting**: Presenting insights clearly for leadership and stakeholders.

---

## Tools and Skills Demonstrated

* Data Cleaning and Validation
* Data Modeling and Joins
* KPI and Metric Engineering
* Business-Oriented Insight Generation
* Analytical Thinking and Structured Problem Solving

---

## Conclusion

This project demonstrates the ability to handle complex datasets, apply disciplined analytical methods, and translate raw data into meaningful insights. The skills showcased are transferable across domains such as **hospitality analytics, sales analytics, and people analytics**, making this project suitable for real-world, industry-facing applications.
