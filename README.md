# End-to-End Data Analytics Project: Python, SQL & Power BI

## Project Overview

This project demonstrates an end-to-end data analytics workflow, starting with raw data stored in a CSV file and transforming it into meaningful insights through Python, SQL, and Power BI.

The project covers data loading, data cleaning, handling missing values, feature creation, SQL-based data analysis, and interactive dashboard development.

## Tools & Technologies

- **Python:** Data processing and cleaning
- **JupyterLab:** Interactive Python development
- **Pandas:** Data manipulation and analysis
- **CSV:** Source data format
- **SQL:** Data storage, querying, and analysis
- **Power BI:** Data visualization and interactive dashboards
- **Git & GitHub:** Version control and project documentation

## Project Workflow

### 1. Data Import Using Python

- Imported raw data from a CSV file into Python using Pandas.
- Loaded the dataset into a Jupyter notebook for exploration and processing.
- Examined the dataset's structure, columns, data types, and basic statistics.

### 2. Data Cleaning and Transformation

Cleaned and prepared the dataset to improve data quality and make it suitable for analysis.

Tasks included:

- Identifying and handling missing values.
- Checking for duplicate records.
- Reviewing and correcting data types where required.
- Renaming columns for clarity and consistency.
- Creating new columns to support further analysis.
- Preparing the cleaned dataset for database loading.

### 3. Data Loading into SQL

Transferred the cleaned dataset into a SQL database to perform structured querying and analysis.

- Created or used a database table to store the processed data.
- Validated the loaded data.
- Wrote SQL queries to explore the dataset and extract useful insights.
- Used filtering, sorting, aggregation, and grouping to analyze the data.
- Applied joins and other SQL operations where relevant to the dataset.

### 4. SQL Data Analysis

Performed data analysis directly in SQL to answer questions based on the available data.

The analysis involved relevant SQL techniques such as:

- `SELECT`, `WHERE`, and `ORDER BY`
- Aggregate functions such as `SUM`, `COUNT`, and `AVG`
- `GROUP BY` and `HAVING`
- Joins, where applicable
- Subqueries and Common Table Expressions (CTEs), where applicable

### 5. Power BI Dashboard Development

Connected Power BI to the prepared data and developed an interactive dashboard to present analytical findings.

Dashboard development included:

- Importing data from the SQL database.
- Designing visualizations to communicate key metrics and trends.
- Adding slicers for interactive filtering.
- Enabling users to explore data across relevant categories and dimensions.
- Organizing dashboard visuals for clear and accessible reporting.

## End-to-End Data Flow


Raw CSV File
     |
     v
Python + Pandas
     |
     v
Data Cleaning & Transformation
     |
     v
SQL Database
     |
     v
SQL Queries & Analysis
     |
     v
Power BI Dashboard
     |
     v
Interactive Data Exploration

## Key Skills Demonstrated

- Data ingestion and preprocessing
- Missing-value handling and data quality checks
- Data transformation and feature creation
- SQL querying and analytical problem-solving
- Database integration
- Interactive dashboard development
- Data visualization and reporting
- End-to-end data analytics workflow

## How to Reproduce the Project

1. Clone or download this repository.
2. Install Python and JupyterLab.
3. Install the required Python libraries, including Pandas.
4. Place the source CSV file in the appropriate project directory.
5. Run the Jupyter notebook to clean and transform the data.
6. Load the processed data into your SQL database.
7. Execute the SQL scripts to perform the analysis.
8. Open the Power BI report and configure the database connection if required.


## Conclusion

This project demonstrates how Python, SQL, and Power BI can work together in a complete data analytics pipeline. Python was used to clean and transform raw CSV data, SQL was used to store and analyze the processed data, and Power BI was used to build an interactive dashboard with slicers for data exploration.

The project provides practical experience in data preparation, database querying, and visualization—skills relevant to Data Analyst and Business Intelligence roles.
