# customer_behavior_analysis
data analytics project of customer behavior analysis using python, sql and powerbi

The project focuses on performing data cleaning, exploratory data analysis (EDA), and visualization to generate actionable business insights that help organizations improve decision-making and customer strategies

OBJECTIVE
Analyze customer demographics and purchasing habits
Identify patterns in customer spending behavior
Perform data cleaning and transformation
Conduct Exploratory Data Analysis (EDA)
Create interactive dashboards for business insights
Support data-driven decision making

Project Workflow
1️⃣ Data Collection
Dataset imported from CSV and PostgreSQL database.
Data loaded into Python using Pandas.
2️⃣ Data Cleaning
Handling missing values
Removing duplicates
Data type conversion
Feature engineering
3️⃣ Exploratory Data Analysis (EDA)

Performed analysis to understand:

Customer age distribution
Purchase frequency
Spending behavior
Product preferences
Customer segmentation trends

Techniques used:

Statistical summaries
Correlation analysis
Distribution plots
Outlier detection
4️⃣ SQL Analysis

SQL queries were used to:

Aggregate customer purchase data
Calculate average spending
Identify high-value customers
Perform joins and filtering

Example:

SELECT customer_id,
       AVG(purchase_amount) AS avg_spending
FROM customer_behavior
GROUP BY customer_id;
5️⃣ Data Visualization (Power BI)

Interactive dashboards were built to display:

Sales trends
Customer segmentation
Purchase frequency analysis
Revenue insights
