# 360-customer-dashboard
**Project Overview**

The Customer 360° Analytics Dashboard is an interactive, enterprise-grade analytics platform that provides a complete view of customer behavior. It integrates multiple datasets into a single master table, automates KPI reporting, and visualizes key metrics such as churn, retention, segmentation, and purchasing trends.

This project demonstrates the ability to combine data engineering, analytics, and visualization skills to deliver actionable insights for business decision-making.
**Features**
**Data Handling & ETL**
Upload multiple CSV files to merge into a master customer table.
ETL transformations: handle missing values, type conversions, and prepare data for analysis.
Persistent storage using SQLite to save master table changes.

**Interactive Dashboard**
Editable Master Table: Add, edit, and delete customer records.
Dynamic KPIs: Total customers, churn rate, average age.
Graphical Insights:
Churn Distribution Pie Chart
Customer Retention by Age Group
Segmentation by Age Group & Churn

**User Controls**
Upload CSV: Drag-and-drop or select CSV files.
Refresh KPIs & Graphs: Automatically updates metrics and visuals.
Real-Time Updates: Edits to the table immediately update the database and visuals.

**Tech Stack**
Python – Backend and ETL processing
Dash & Plotly – Interactive web dashboard and visualizations
Dash Bootstrap Components – Responsive layout and styling
Pandas – Data manipulation and processing
SQLite – Persistent storage for master table

**Future Enhancements**
Add additional visualizations: purchase trends, region-wise segmentation.
Integrate predictive analytics for churn forecasting.
Enable export of edited master table as CSV or Excel.
Implement user authentication for secure multi-user access.
