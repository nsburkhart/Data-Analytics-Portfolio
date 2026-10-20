# Data Analytics Portfolio

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

---

Welcome to my Data Analytics Portfolio! This repository brings together projects I've completed using Python, SQL, PostgreSQL, Power BI, and Tableau. My work focuses on analyzing data, identifying patterns, and turning findings into useful business insights.

Each project includes an overview of the problem, the tools used, and the results of the analysis. You can also explore the individual GitHub repositories to see the code and supporting work.

## Table of Contents

1. [Online Retail Sales Performance Analysis](#project-1-online-retail-sales-performance-analysis)
2. [Sales Analytics SQL Project](#project-2-sales-analytics-sql-project)
3. [Basketball Shot Probability Modeling](#project-3-basketball-shot-probability-modeling)
4. [Customer Churn Prediction & Retention Analytics](#project-4-customer-churn-prediction--retention-analytics)

---

## Project 1: Online Retail Sales Performance Analysis

**Tools:** PostgreSQL, SQL, Tableau

[View Project Repository](https://github.com/nsburkhart/online-retail-sales-performance)

In this project, I analyzed an online retail transaction dataset to better understand sales performance, customer behavior, and product revenue. I used PostgreSQL to clean and analyze the data, investigating returns, missing customer information, and unusual transactions before creating business-focused KPIs.

I then built a Tableau dashboard to visualize revenue trends, customer purchasing behavior, international markets, and top-performing products.

### Key Results

- **Total Revenue:** £20,334,157
- **Total Orders:** 39,259
- **Average Order Value:** £517.95
- **Repeat Customer Rate:** 72.39%

### Dashboard Preview

![Online Retail Sales Performance Dashboard](Dashboard%20Screenshot.png)

*Tableau dashboard showing sales KPIs, monthly revenue trends, international markets, and top-performing products.*

---

## Project 2: Sales Analytics SQL Project

**Tools:** PostgreSQL, SQL, pgAdmin 4

[View Project Repository](https://github.com/nsburkhart/sales-analytics-sql)

In this project, I built a relational sales database from scratch using PostgreSQL. I created a synthetic dataset containing 100 customers, 30 products, 400 orders, and 1,200 order-item records across four connected tables.

I wrote SQL queries to answer business questions about sales performance, customer purchasing behavior, and product demand. The analysis involved multi-table joins, aggregations, filtering, grouping, and date-based calculations.

### Key Analysis

- Identified top-performing products and categories by revenue.
- Ranked customers by total spending and order frequency.
- Calculated average order value and units sold.
- Analyzed monthly revenue trends and geographic sales performance.

---

## Project 3: Basketball Shot Probability Modeling

**Tools:** Python, pandas, NumPy, scikit-learn

[View Project Repository](https://github.com/nsburkhart/basketball-shot-probability-model)

This project focused on predicting the probability of a basketball shot being made using machine learning. I developed a modeling approach that considers shot location, defender positioning, shooter tendencies, and game situations to better evaluate shot quality.

I started with logistic regression and experimented with histogram-based gradient boosting to capture more complex relationships in the data. I also engineered basketball-specific features to improve the model's ability to distinguish between different shot situations.

### Key Techniques

- **Feature Engineering:** Created shot-zone categories, shooter-zone combinations, and defender movement features.
- **Machine Learning:** Compared logistic regression with histogram-based gradient boosting.
- **Categorical Encoding:** Used one-hot encoding and target encoding to incorporate categorical information.
- **Model Evaluation:** Evaluated probability predictions using log-loss and explored cross-validation and feature importance.

### Project Outcome

Developed a complete machine learning workflow covering feature engineering, model training, and probability prediction.

The public GitHub repository includes a runnable demonstration using synthetic basketball data, allowing others to explore the modeling approach without access to the original internship assessment dataset.

---

## Project 4: Customer Churn Prediction & Retention Analytics

**Tools:** Python, pandas, NumPy, scikit-learn, Power BI, DAX

[View Project Repository](https://github.com/nsburkhart/customer-churn-prediction)

In this project, I analyzed 7,043 customer records from the IBM Telco dataset to understand why customers leave and identify opportunities to improve retention. I used Python to clean and explore the data, investigate customer behavior, and develop machine learning models to predict churn.

I compared Logistic Regression and Random Forest models, evaluating their ability to identify customers at risk of leaving. Beyond model performance, I focused on translating the findings into practical business recommendations.

I also built an interactive Power BI dashboard to visualize churn patterns and make the results easier to explore.

### Key Findings

- **High-Risk Segment:** Identified 2,680 month-to-month customers without technical support who accounted for 72.23% of observed churn.
- **Churn Rate:** This segment had a 50.37% churn rate, compared with 26.54% across all customers.
- **Model Performance:** Logistic Regression achieved 66.8% recall and a 0.614 F1-score at a 40% prediction threshold.
- **Revenue Opportunity:** Estimated that a hypothetical 10% relative reduction in churn within this segment could retain approximately 135 customers, representing $122,859 in annualized gross revenue.

### Power BI Dashboard Preview

![Customer Churn & Retention Analytics Dashboard](Customer%20Churn%20Dashboard.png)

*Interactive Power BI dashboard showing churn KPIs, customer retention patterns, contract and payment method comparisons, and a high-risk customer segment.*

The dashboard includes interactive slicers for contract type and payment method, allowing users to explore how churn rates vary across customer groups.

[View Full Dashboard Project](https://github.com/nsburkhart/customer-churn-prediction)

### Business Recommendation

Recommended testing proactive technical support and longer-term contract incentives for high-risk customers. A controlled retention campaign could help determine whether these interventions reduce churn and provide a positive financial return.

*Revenue estimates are illustrative and do not account for campaign costs or future customer churn.*

---
