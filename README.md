# Customer Shopping Analysis

## Overview

This project is an end-to-end Data Analytics solution focused on analyzing customer shopping behavior. The workflow includes data cleaning, exploratory data analysis (EDA), database integration, SQL-based business analysis, dashboard development, and reporting.

The objective is to extract meaningful insights from customer purchase data and present them through an interactive Power BI dashboard for data-driven decision-making.

---

## Dataset

The dataset contains customer shopping information, including:

* Customer demographics
* Product categories
* Purchase amounts
* Review ratings
* Subscription status
* Discount usage
* Shipping methods
* Previous purchases
* Seasonal shopping trends

The dataset was initially loaded and analyzed using Python before being stored in a relational database for SQL analysis.

---

## Tools & Technologies

### Programming & Analysis

* Python
* Pandas
* NumPy
* Jupyter Notebook / VS Code

### Database

* PostgreSQL / MySQL / SQL Server
* SQL

### Visualization

* Power BI

### Reporting

* Gamma (Presentation Creation)
* Microsoft PowerPoint

### Version Control

* Git
* GitHub

---

## Project Workflow

### 1. Data Loading

* Imported CSV dataset into Python.
* Performed initial inspection and validation.

### 2. Data Cleaning

* Handled missing values.
* Removed inconsistencies.
* Standardized column formats.
* Prepared data for analysis.

### 3. Exploratory Data Analysis (EDA)

* Analyzed customer demographics.
* Evaluated purchasing behavior.
* Studied product category performance.
* Identified trends and patterns.

### 4. Database Integration

* Created a relational database.
* Loaded cleaned data into PostgreSQL.
* Structured data for SQL querying and analysis.

### 5. SQL Analysis

Performed business-focused SQL queries such as:

* Revenue analysis by gender
* Product performance analysis
* Customer segmentation
* Subscription behavior analysis
* Discount impact analysis
* Revenue contribution by age groups
* Top-performing products

### 6. Dashboard Development

Built an interactive Power BI dashboard featuring:

* KPI Cards
* Revenue Analysis
* Customer Analysis
* Product Analysis
* Age Group Analysis
* Interactive Filters and Slicers

### 7. Reporting

* Generated business insights.
* Created presentation-ready reports using Gamma and PowerPoint.

---

## Dashboard Features

### KPIs

* Total Revenue
* Total Customers
* Average Review Rating
* Average Purchase Amount

### Visualizations

* Revenue by Category
* Revenue by Age Group
* Purchase Distribution
* Customer Segmentation
* Product Performance Analysis

### Interactive Filters

* Gender
* Category
* Subscription Status
* Shipping Type

---

## Key Insights

* Clothing category generated the highest revenue.
* Young adults contributed the largest share of revenue.
* Subscription behavior influenced customer spending patterns.
* Certain products showed significantly higher discount utilization.
* Customer purchasing trends varied across categories and demographics.

---

## Results

The project successfully transformed raw customer data into actionable business insights through:

* Data Cleaning
* Exploratory Data Analysis
* SQL-Based Analysis
* Interactive Dashboard Development
* Business Reporting

The final solution demonstrates the complete analytics lifecycle from raw data to business intelligence reporting.

---

## Project Structure

```text
Customer-Shopping-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── Jupyter/
│   └── analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── Customer_Shopping_Analysis.pbix
│
├── images/
│   ├── dashboard.png
│   ├── python_analysis.png
│   └── sql_analysis.png
│
└── README.md
```

## How to Run

### Python Analysis

1. Install required libraries:

   * pandas
   * numpy
   * matplotlib

2. Open the notebook:

```bash
jupyter notebook analysis.ipynb
```

3. Run all cells to perform EDA and data cleaning.

### Database Setup

1. Create a database in PostgreSQL/MySQL/SQL Server.
2. Import the cleaned dataset.
3. Execute SQL queries from:

```text
sql/analysis_queries.sql
```

### Power BI Dashboard

1. Open:

```text
Customer_Shopping_Analysis.pbix
```

2. Refresh the data connection.
3. Interact with filters and dashboard visuals.

---

## Author

**Mehul Chavan**

Data Analytics | SQL | Python | Power BI | Business Intelligence

