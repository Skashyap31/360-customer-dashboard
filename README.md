# Customer 360° Analytics Dashboard

**Python | Dash | Plotly | SQLite | Interactive Customer Analytics**

---

## Project Overview
The **Customer 360° Analytics Dashboard** is an interactive web application built with **Python Dash** that provides a **complete view of customer behavior**. It allows users to **upload, edit, and analyze customer data** dynamically. The dashboard calculates **KPIs**, visualizes customer **churn, retention, and segmentation**, and stores data persistently using **SQLite**.

This project demonstrates **end-to-end data handling**, from CSV ingestion and ETL transformations to interactive visualizations and editable tables.

---

## Features

### Data Handling & ETL
- Upload multiple CSV files to **merge into a master customer table**.  
- ETL transformations: handle missing values, type conversions, and prepare data for analysis.  
- Persistent storage using **SQLite** to save master table changes.  

### Interactive Dashboard
- **Editable Master Table**: Add, edit, and delete customer records.  
- **Dynamic KPIs**: Total customers, churn rate, average age.  
- **Graphical Insights**:
  - **Churn Distribution Pie Chart**  
  - **Customer Retention by Age Group**  
  - **Segmentation by Age Group & Churn**  

### User Controls
- **Upload CSV**: Drag-and-drop or select CSV files.  
- **Refresh KPIs & Graphs**: Automatically updates metrics and visuals.  
- **Real-Time Updates**: Edits to the table immediately update the database and visuals.

---

## Tech Stack
- **Python** – Backend and ETL processing  
- **Dash & Plotly** – Interactive web dashboard and visualizations  
- **Dash Bootstrap Components** – Responsive layout and styling  
- **Pandas** – Data manipulation and processing  
- **SQLite** – Persistent storage for master table  

---

## Installation & Setup
1. Clone the repository:
```bash
git clone https://github.com/your-username/customer360-dash.git
cd customer360-dash

2. Install required packages:
    pip install dash dash-bootstrap-components pandas plotly sqlalchemy
3. Run the application:
    python app.py

---
## Usage Instructions

Upload CSV – Drag-and-drop or select one or multiple CSV files containing customer data.

Edit Table – Modify customer information or delete rows directly in the editable table.

Refresh KPIs & Graphs – Click the refresh button to update metrics and visualizations.

Analyze Graphs – Explore churn distribution, retention trends, and segmentation.

Persistent Changes – All edits are saved automatically in the SQLite database (customer360.db).

---

Future Enhancements

Add additional visualizations: purchase trends, region-wise segmentation.

Integrate predictive analytics for churn forecasting.

Enable export of edited master table as CSV or Excel.

Implement user authentication for secure multi-user access.
