# AtliQ Hotels Data Analysis | Power BI Project

## Business Problem Statement

AtliQ Hotels operates across multiple cities and booking platforms, generating large volumes of transactional data. The business requires a consolidated analytical view to understand **occupancy trends, revenue performance, and booking platform effectiveness** to support strategic decision-making. This project addresses that need by transforming raw booking data into actionable insights.

---

## Project Overview (ATS & Recruiter Optimized)

This project demonstrates an end-to-end **data analytics workflow** using structured hospitality data. It covers data ingestion, cleaning, transformation, KPI creation, and insight generation using industry-standard practices. The analysis emphasizes business interpretation and stakeholder-ready outputs rather than isolated technical steps.

Key focus areas:

* Revenue and occupancy analysis across cities and room categories
* Booking platform performance comparison
* Data quality validation and metric standardization
* Dashboard-ready analytical modeling

---

## Datasets Used

* `dim_date.csv` – Date and calendar attributes
* `dim_hotels.csv` – Hotel and property details
* `dim_rooms.csv` – Room category information
* `fact_bookings.csv` – Transaction-level booking data
* `fact_aggregated_bookings.csv` – Aggregated booking metrics

---

## Analysis Workflow

### 1. Data Import and Exploration

* Imported multiple CSV files into Power BI.
* Analyzed schema, data types, and table relationships.
* Explored booking distribution across platforms, cities, and properties.

### 2. Data Cleaning and Validation

* Removed records with invalid guest counts (≤ 0).
* Identified and removed revenue outliers using statistical thresholds.
* Handled missing values and corrected inconsistencies in aggregated datasets.
* Ensured data integrity across fact and dimension tables.

### 3. Data Transformation & KPI Engineering

* Calculated **Occupancy Percentage** at property and room-category levels.
* Standardized occupancy metrics into percentage-based KPIs.
* Integrated hotel, room, and booking data for multi-dimensional analysis.
* Enabled time-based analysis using date dimensions.

### 4. Insight Generation

* Analyzed **revenue by city and booking platform**.
* Evaluated **average revenue realized** by room category.
* Compared **occupancy rates across cities and room types**.
* Identified performance differences between booking platforms.

---

## Key Insights (Interview-Ready)

* Revenue and occupancy vary significantly by city and room category.
* Certain booking platforms consistently deliver higher realized revenue.
* Premium room categories generate higher revenue but show fluctuating occupancy.
* City-level performance highlights demand concentration and seasonal patterns.

---

## Relevance to HR / People Analytics Roles

Although based on hospitality data, the analytical framework directly applies to HR and People Analytics use cases:

* **Data Integration**: Merging employee, performance, and engagement datasets.
* **Data Quality Management**: Identifying invalid records and enforcing validation rules.
* **Metric Design**: Translating business KPIs into HR metrics such as utilization, productivity, and attrition.
* **Decision Support**: Enabling leadership decisions through data-driven insights.
* **Stakeholder Communication**: Presenting insights in a clear, dashboard-driven format.

---

## Tools & Skills Demonstrated

* Power BI (Data Modeling, DAX, Visualization)
* Data Cleaning and Validation Techniques
* KPI and Metric Engineering
* Business-Oriented Data Analysis
* Dashboard Design for Stakeholders

---

## Repository Structure

```
AtliQ-Hotels-Analysis/
│
├── data/                  # Raw CSV datasets
├── dashboards/            # Power BI screenshots (PNG)
├── powerbi/               # Power BI files (.pbix)
├── README.md
└── LICENSE
```

---

## Notes on Files

* Dashboard screenshots are provided for public viewing.
* The Power BI (.pbix) file may be shared on request or kept private to protect intellectual work.

---

## Conclusion

This project reflects a structured, industry-aligned approach to data analytics. The skills demonstrated are transferable to **Power BI Analyst, Business Analyst, and People Analytics roles**, with a strong emphasis on data quality, insight generation, and stakeholder communication.
