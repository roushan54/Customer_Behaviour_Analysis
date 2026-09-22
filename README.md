# Customer_Behaviour_Analysis
Data Analytics project showcasing customer behavior analysis using Python, SQL, and Power Bi.

# Data Analytics Project

## Overview

This project demonstrates an end-to-end **Data Analytics workflow**, starting from raw dataset loading and data cleaning to exploratory analysis, SQL-based analysis, dashboard creation, and business reporting.

The project combines **Python, SQL, Power BI, and presentation/reporting tools** to transform raw data into meaningful business insights.

---

## Dataset

The project uses a structured dataset containing business-related records and attributes.

The dataset is:

* Loaded and explored using Python
* Checked for missing and duplicate values
* Cleaned and transformed for analysis
* Used for SQL-based analysis
* Connected to Power BI for dashboard creation

> **Dataset:** Add your dataset name and source here.

---

## Tools & Technologies

| Tool                                | Purpose                                 |
| ----------------------------------- | --------------------------------------- |
| **Python**                          | Data loading, cleaning, and analysis    |
| **Pandas**                          | Data manipulation and transformation    |
| **NumPy**                           | Numerical operations                    |
| **Matplotlib / Seaborn**            | Data visualization and EDA              |
| **PostgreSQL / MySQL / SQL Server** | SQL analysis and querying               |
| **Power BI**                        | Interactive dashboard and visualization |
| **Gamma**                           | Presentation creation                   |
| **MS Excel / CSV**                  | Dataset and supporting analysis         |

---

## Project Workflow

### 1. Load Dataset

The dataset is imported into Python using Pandas.

Initial checks are performed to understand:

* Number of rows and columns
* Data types
* Missing values
* Duplicate records
* Basic statistical information

### 2. Exploratory Data Analysis (EDA)

EDA is performed to understand the structure and patterns within the data.

Key activities include:

* Univariate analysis
* Bivariate analysis
* Distribution analysis
* Correlation analysis
* Outlier detection
* Trend analysis
* Identification of important variables

Visualizations are created using Matplotlib and Seaborn.

### 3. Data Cleaning

The raw dataset is prepared for further analysis by:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Standardizing column values
* Handling inconsistent data
* Identifying and treating outliers where required
* Creating derived columns when necessary

### 4. SQL Analysis

The cleaned data is loaded into a relational database and analyzed using SQL.

SQL queries are performed using **PostgreSQL / MySQL / SQL Server**.

Examples of analysis include:

* Aggregations using `SUM`, `AVG`, `COUNT`, `MIN`, and `MAX`
* Filtering using `WHERE`
* Grouping using `GROUP BY`
* Sorting using `ORDER BY`
* Conditional analysis using `CASE`
* Joining multiple tables
* Subqueries
* Common Table Expressions (CTEs)
* Window functions
* Ranking and trend analysis

The SQL analysis is used to identify important business trends and patterns.

### 5. Power BI Dashboard

The cleaned and analyzed data is used to create an interactive Power BI dashboard.

The dashboard includes relevant:

* KPI cards
* Bar charts
* Line charts
* Tables
* Filters and slicers
* Trend visualizations
* Category-wise analysis

The dashboard allows users to interact with the data and explore important business metrics.

### 6. Report

A detailed analytical report is created to document:

* Business problem
* Data understanding
* Data cleaning process
* EDA findings
* SQL analysis
* Dashboard insights
* Key observations
* Business recommendations

### 7. Presentation

A PowerPoint presentation is created using **Gamma** to summarize the project.

The presentation covers:

* Project objective
* Dataset overview
* Methodology
* EDA findings
* SQL analysis
* Power BI dashboard
* Key insights
* Business recommendations
* Conclusion

---

## Dashboard

The Power BI dashboard provides an interactive view of the major metrics and trends identified during the analysis.

### Dashboard Preview

> Add your Power BI dashboard screenshot here.

```text
![Power BI Dashboard](images/dashboard.png)
```

---

## Key Results

The analysis helps identify important patterns and trends within the dataset.

Key outcomes include:

* Identification of major trends and performance indicators
* Detection of data quality issues
* Analysis of category and segment performance
* Identification of important business patterns
* SQL-based extraction of actionable information
* Interactive visualization of KPIs through Power BI
* Data-driven insights to support business decisions

> Add your actual project findings here instead of keeping these generic points.

---

## Project Structure

```text
Data-Analytics-Project/
│
├── dataset/
│   └── dataset.csv
│
├── python/
│   └── data_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── report/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pptx
│
├── images/
│   └── dashboard.png
│
└── README.md
```

---

## How to Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

### Step 2: Install Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3: Run the Python Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook from the `python` folder and run the cells sequentially.

### Step 4: Set Up the Database

Import the cleaned dataset into your preferred database:

* PostgreSQL
* MySQL
* SQL Server

Then execute the SQL queries available in:

```text
sql/analysis_queries.sql
```

### Step 5: Open the Power BI Dashboard

Open the `.pbix` file from the `powerbi` folder using Power BI Desktop.

If required, update the database connection details before refreshing the data.

### Step 6: Review the Report and Presentation

The final analytical report and Gamma-generated presentation are available in their respective folders.

---

## Skills Demonstrated

This project demonstrates practical experience in:

* Python for Data Analytics
* Pandas and NumPy
* Exploratory Data Analysis
* Data Cleaning & Transformation
* SQL
* PostgreSQL / MySQL / SQL Server
* Data Visualization
* Power BI
* KPI Development
* Business Insights
* Data Storytelling
* Analytical Reporting
* Presentation Development

---

## Conclusion

This project demonstrates a complete **end-to-end data analytics workflow**, transforming raw data into meaningful insights through Python, SQL, and Power BI.

It showcases the ability to work with data from **collection and preparation through analysis, visualization, reporting, and business presentation**.

