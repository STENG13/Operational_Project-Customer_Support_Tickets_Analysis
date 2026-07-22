Customer Support Operational Dashboard | Power BI

Overview

This project demonstrates an end-to-end Business Intelligence workflow using Power BI, Power Query, Excel, and DAX. Starting from a raw customer support dataset, the project covers data cleaning, transformation, modelling, analysis, and interactive dashboard development to provide operational insights for management.

The objective is to help stakeholders monitor service performance, identify operational bottlenecks, and support data-driven decision making.

⸻

Project Objectives

* Clean and prepare raw operational data for analysis.
* Build a reusable data model for reporting.
* Measure key customer support KPIs.
* Develop interactive Power BI dashboards.
* Generate business insights from operational trends.

⸻

Workflow

```text
Raw Kaggle Dataset
        ↓
Power Query (ETL)
        ↓
Cleaned Dataset
        ↓
Validation in R
        ↓
Power BI Data Model
        ↓
Interactive Dashboard
        ↓
Business Insights
```

⸻

Dataset

Source: Kaggle (Customer Support Dataset)

The dataset contains approximately 80,000 customer support tickets, including information such as:

* Ticket ID
* Issue reported date
* Response date
* Resolution date
* Agent
* Manager
* Department
* Category & Sub-category
* Priority
* Customer Satisfaction (CSAT)
* Customer demographics

⸻

Tools Used

* Power BI
* Power Query
* DAX
* Microsoft Excel
* GitHub

⸻

Data Preparation

The raw dataset was cleaned using Power Query.

Cleaning included:

* Standardising date and time formats
* Handling missing values
* Correcting inconsistent data types
* Creating reporting periods
* Creating calculated duration fields
* Removing duplicate and unnecessary columns

Additional calculated fields include:

* Response Time (Minutes)
* Resolution Time (Minutes)
* Month
* Week of Year
* Reporting Date
* Tenure Groups (if applicable)

⸻

Data Model

The Power BI model includes:

* Fact table containing customer support tickets
* Calendar table
* Relationships for time-based analysis
* DAX measures for KPI calculations

Key DAX measures include:

* Total Tickets
* Average Response Time
* Average Resolution Time
* Average CSAT Score
* Resolved Tickets
* Open Tickets
* Resolution Rate

⸻

Dashboard Pages

1. Executive Overview

Provides a high-level summary of operational performance.

KPIs:

* Total Tickets
* Average Response Time
* Average Resolution Time
* Average CSAT
* Resolution Rate

Visuals:

* Ticket Trend
* Monthly Performance
* Ticket Status Breakdown
* Category Distribution

⸻

2. Operational Performance

Focuses on service efficiency.

Visuals include:

* Response Time Trends
* Resolution Time Trends
* Ticket Volume by Week
* Ticket Volume by Month
* Department Performance

⸻

3. Agent Performance

Measures individual and team performance.

Includes:

* Tickets handled
* Average response time
* Average resolution time
* Average CSAT
* Agent ranking
* Manager comparison

⸻

4. Customer & Issue Analysis

Explores customer behaviour and support demand.

Visuals include:

* Category distribution
* Sub-category analysis
* Priority breakdown
* Customer demographics
* Geographic analysis (where available)

⸻

Key Business Insights

The dashboard enables stakeholders to:

* Identify peak ticket periods
* Compare agent performance
* Monitor customer satisfaction
* Detect operational bottlenecks
* Discover high-volume issue categories
* Track service performance over time

⸻

Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Modelling
* Power Query
* DAX
* KPI Development
* Dashboard Design
* Business Intelligence
* Data Visualisation
* Operational Reporting
* Analytical Thinking

⸻

Future Improvements

* Add forecasting for ticket volumes.
* Implement drill-through reporting for individual agents.
* Build row-level security for different management teams.
* Publish the report to the Power BI Service.
* Connect the dashboard to a live SQL database instead of static CSV files.

⸻

Author

Seavchhun Teng

Bachelor of Data Science
University of Canterbury

LinkedIn: https://www.linkedin.com/in/seavchhun-teng/
