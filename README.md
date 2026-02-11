# Customer Churn Analysis 

## Project Overview

This project provides a comprehensive analysis of customer churn for a telecommunications company. By leveraging **SQL** for data processing and **Power BI** for visualization, the project identifies key factors contributing to customer attrition and provides actionable insights to improve retention rates.

## Dataset

The analysis is based on a telecom customer database containing **6,000 customers**, covering:

* **Demographics:** Gender, age groups, and marital status.
* **Account Info:** Payment methods, contract types, and tenure.
* **Services:** Internet types (Fiber Optic, Cable, DSL) and additional services like streaming and security.
* **Churn Data:** Churn categories (Competitor, Attitude, Dissatisfaction, Price) and specific churn reasons.

## Key Insights from Dashboard

* **Churn Rate:** The overall churn rate stands at **26.99%**, with 1,732 customers leaving.
* **High-Risk Demographics:** Customers aged **>50** show a significantly higher churn rate compared to younger demographics.
* **Service Impact:** **Fiber Optic** users have the highest churn rate compared to Cable or DSL users, suggesting potential service quality or pricing issues in that segment.
* **Contract Types:** Month-to-month contracts have a drastically higher churn rate than one or two-year contracts.
* **Top Churn Reason:** The "Competitor" category is the leading driver of churn, followed by "Attitude" and "Dissatisfaction."

## Tech Stack

* **Data Processing:** SQL (Data cleaning, joining tables, and aggregating metrics)
* **Visualization:** Power BI (DAX for measures, interactive filtering, and dashboard design)

## Project Structure

* `Analysis_Queries.sql`: Contains the SQL scripts used to extract and transform data.
* `Churn_Dashboard.pbix`: The Power BI file containing the interactive report.
* `Screenshots/`: Visual representation of the final dashboard.

## How to Use

1. **SQL:** Run the scripts in the `Analysis_Queries.sql` file on your SQL environment to see how the metrics were calculated.
2. **Power BI:** Open the `.pbix` file to interact with the dashboard. Use the filters for **Monthly Charge Range** and **Married** status to deep-dive into specific segments.

---

### Dashboard Preview

---
