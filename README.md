# 📊 📊 Vendor Performance & Inventory Analysis | SQL + Python + PowerBI

## 📌 Project Overview

This project focuses on analyzing vendor performance, purchasing patterns, sales revenue, profitability, and inventory management using SQL and Python.

The objective is to transform raw inventory and transaction data into meaningful business insights that can help organizations evaluate vendor performance, optimize procurement strategies, identify slow-moving inventory, and improve profitability.

The project follows a structured analytical approach, starting with database exploration and SQL-based data aggregation, followed by Python-based exploratory data analysis, statistical analysis, and data visualization.

## 🎯 Business Objectives

- Evaluate vendor and brand sales performance.
- Identify vendors contributing the most to total procurement.
- Analyze gross profit and profit margins.
- Investigate the impact of bulk purchasing on unit prices.
- Identify slow-moving inventory and excess stock.
- Calculate capital locked in unsold inventory.
- Compare profitability between high-performing and low-performing vendors.

## 🛠️ Technologies & Tools

- **Python:** Data analysis and statistical analysis.
- **SQL:** Data extraction, aggregation, joins, CTEs, and database querying.
- **SQLite:** Relational database management.
- **Pandas & NumPy:** Data manipulation and numerical calculations.
- **Matplotlib & Seaborn:** Data visualization.
- **SciPy:** Statistical hypothesis testing and confidence intervals.
- **Jupyter Notebook:** Interactive analysis and documentation.

## 📂 Project Workflow

### 1. Database Exploration & SQL Analysis

- Connected Python to SQLite database.
- Explored relational tables containing purchase, sales, vendor invoice, and pricing information.
- Performed SQL joins and aggregations to combine information from multiple tables.
- Used GROUP BY, SUM(), LEFT JOIN, INNER JOIN, and Common Table Expressions (CTEs).
- Created a consolidated `vendor_sales_summary` table.

### 2. Data Cleaning & Feature Engineering

- Checked missing values and data types.
- Corrected numerical data types.
- Removed unnecessary leading and trailing whitespaces.
- Handled missing values.
- Created additional business metrics:
  - Gross Profit
  - Profit Margin
  - Stock Turnover
  - Sales-to-Purchase Ratio

### 3. Exploratory Data Analysis (EDA)

- Analyzed descriptive statistics.
- Studied numerical data distributions using histograms.
- Identified potential outliers using boxplots.
- Analyzed categorical variables.
- Examined relationships between numerical variables using correlation analysis and heatmaps.

### 4. Vendor & Brand Performance Analysis

- Identified top 10 vendors and brands based on sales revenue.
- Identified brands with low sales but high profit margins.
- Evaluated vendor contribution to total procurement.
- Analyzed cumulative vendor contribution using Pareto analysis.

### 5. Inventory & Procurement Analysis

- Investigated the relationship between bulk purchasing and unit purchase prices.
- Identified vendors with low inventory turnover.
- Calculated unsold inventory value to identify capital locked in inventory.

### 6. Statistical Analysis

- Calculated confidence intervals to compare vendor profitability.
- Formulated null and alternative hypotheses.
- Applied an independent two-sample t-test to investigate differences in profit margins between high-performing and low-performing vendors.

## 📈 Key Business Questions

1. Which vendors and brands generate the highest sales revenue?
2. Which brands have lower sales but higher profit margins?
3. Which vendors contribute the most to total purchase expenditure?
4. How much does the business depend on its top 10 vendors?
5. Does bulk purchasing reduce the unit purchase price?
6. Which vendors have slow-moving inventory?
7. How much capital is locked in unsold inventory?
8. Is there a statistically significant difference in profit margins between high-performing and low-performing vendors?

## 💡 Business Value

The analysis provides a foundation for data-driven business decisions, including:

- Improving vendor selection and procurement strategies.
- Identifying opportunities for pricing adjustments and promotional activities.
- Optimizing inventory management.
- Reducing excess inventory and working capital blockage.
- Understanding vendor concentration and procurement dependency.
- Evaluating profitability beyond sales revenue alone.

## 📁 Project Files

- `Exploratory Data Analysis.ipynb` – Database exploration, SQL queries, data aggregation, and feature engineering.
- `Vendor Performance Analysis.ipynb` – Exploratory analysis, vendor performance evaluation, statistical analysis, and visualizations.

## ▶️ How to Run the Project

1. Clone this repository.
2. Install the required Python libraries.
3. Make the required inventory database available.
4. Open the notebooks using Jupyter Notebook or JupyterLab.
5. Execute the notebooks to explore the analysis.

### Install Dependencies

```
pip install pandas numpy matplotlib seaborn scipy jupyter
```

## 👨‍💻 Author

**Kalpesh Kale**

Aspiring Data Analyst | SQL | Python | Power BI | Excel

I enjoy transforming raw data into meaningful insights and solving real-world business problems through data analysis.



## 📌 Project Overview

This project focuses on analyzing vendor performance, purchasing patterns, sales revenue, profitability, and inventory management using SQL and Python.

The objective is to transform raw inventory and transaction data into meaningful business insights that can help organizations evaluate vendor performance, optimize procurement strategies, identify slow-moving inventory, and improve profitability.

The project follows a structured analytical approach, starting with database exploration and SQL-based data aggregation, followed by Python-based exploratory data analysis, statistical analysis, and data visualization.

## 🎯 Business Objectives

- Evaluate vendor and brand sales performance.
- Identify vendors contributing the most to total procurement.
- Analyze gross profit and profit margins.
- Investigate the impact of bulk purchasing on unit prices.
- Identify slow-moving inventory and excess stock.
- Calculate capital locked in unsold inventory.
- Compare profitability between high-performing and low-performing vendors.

## 🛠️ Technologies & Tools

- **Python:** Data analysis and statistical analysis.
- **SQL:** Data extraction, aggregation, joins, CTEs, and database querying.
- **SQLite:** Relational database management.
- **Pandas & NumPy:** Data manipulation and numerical calculations.
- **Matplotlib & Seaborn:** Data visualization.
- **SciPy:** Statistical hypothesis testing and confidence intervals.
- **Jupyter Notebook:** Interactive analysis and documentation.

## 📂 Project Workflow

### 1. Database Exploration & SQL Analysis

- Connected Python to SQLite database.
- Explored relational tables containing purchase, sales, vendor invoice, and pricing information.
- Performed SQL joins and aggregations to combine information from multiple tables.
- Used GROUP BY, SUM(), LEFT JOIN, INNER JOIN, and Common Table Expressions (CTEs).
- Created a consolidated `vendor_sales_summary` table.

### 2. Data Cleaning & Feature Engineering

- Checked missing values and data types.
- Corrected numerical data types.
- Removed unnecessary leading and trailing whitespaces.
- Handled missing values.
- Created additional business metrics:
  - Gross Profit
  - Profit Margin
  - Stock Turnover
  - Sales-to-Purchase Ratio

### 3. Exploratory Data Analysis (EDA)

- Analyzed descriptive statistics.
- Studied numerical data distributions using histograms.
- Identified potential outliers using boxplots.
- Analyzed categorical variables.
- Examined relationships between numerical variables using correlation analysis and heatmaps.

### 4. Vendor & Brand Performance Analysis

- Identified top 10 vendors and brands based on sales revenue.
- Identified brands with low sales but high profit margins.
- Evaluated vendor contribution to total procurement.
- Analyzed cumulative vendor contribution using Pareto analysis.

### 5. Inventory & Procurement Analysis

- Investigated the relationship between bulk purchasing and unit purchase prices.
- Identified vendors with low inventory turnover.
- Calculated unsold inventory value to identify capital locked in inventory.

### 6. Statistical Analysis

- Calculated confidence intervals to compare vendor profitability.
- Formulated null and alternative hypotheses.
- Applied an independent two-sample t-test to investigate differences in profit margins between high-performing and low-performing vendors.

## 📈 Key Business Questions

1. Which vendors and brands generate the highest sales revenue?
2. Which brands have lower sales but higher profit margins?
3. Which vendors contribute the most to total purchase expenditure?
4. How much does the business depend on its top 10 vendors?
5. Does bulk purchasing reduce the unit purchase price?
6. Which vendors have slow-moving inventory?
7. How much capital is locked in unsold inventory?
8. Is there a statistically significant difference in profit margins between high-performing and low-performing vendors?

## 💡 Business Value

The analysis provides a foundation for data-driven business decisions, including:

- Improving vendor selection and procurement strategies.
- Identifying opportunities for pricing adjustments and promotional activities.
- Optimizing inventory management.
- Reducing excess inventory and working capital blockage.
- Understanding vendor concentration and procurement dependency.
- Evaluating profitability beyond sales revenue alone.

## 📁 Project Files

- `Exploratory Data Analysis.ipynb` – Database exploration, SQL queries, data aggregation, and feature engineering.
- `Vendor Performance Analysis.ipynb` – Exploratory analysis, vendor performance evaluation, statistical analysis, and visualizations.

## ▶️ How to Run the Project

1. Clone this repository.
2. Install the required Python libraries.
3. Make the required inventory database available.
4. Open the notebooks using Jupyter Notebook or JupyterLab.
5. Execute the notebooks to explore the analysis.

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

## 👨‍💻 Author

**Kalpesh Kale**

Aspiring Data Analyst | SQL | Python | Power BI | Excel

I enjoy transforming raw data into meaningful insights and solving real-world business problems through data analysis.

