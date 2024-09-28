
# Telecom Customer Churn

## Project Overview

This project aims to analyze customer churn in the telecom industry. The objective is to identify key factors that contribute to customer churn and develop strategies to reduce churn rates.

### Key Objectives:
- Understand the factors that influence customer churn.
- Develop models to predict churn.
- Provide actionable insights to reduce churn and improve customer retention.

---

## Folder Structure

- **/data/**: Contains all the datasets used in this analysis.
- **/notebooks/**: Jupyter notebooks where the analysis is done.
- **/models/**: Includes the saved models used for churn prediction.
- **/reports/**: Detailed reports on the findings and results of the analysis.
- **/src/**: Python scripts for data preprocessing, model training, and evaluation.
- **/visualizations/**: Visual representations of churn patterns and insights.

---

## Data

The dataset contains customer information and includes the following key columns:
- **CustomerID**: Unique ID for each customer.
- **Contract Type**: Type of contract (month-to-month, yearly, or bi-annual).
- **Payment Method**: Method used for payment (credit card, bank transfer, electronic checks, etc.).
- **Tenure**: Number of months a customer has stayed with the company.
- **Churn**: Whether the customer has churned (Yes/No).

---

## Key Findings

### 1. Contract Type:
- Customers on month-to-month contracts are 42% more likely to churn compared to those on yearly (11%) and bi-annual contracts (3%).
- **Implication**: Long-term contracts improve customer retention.

### 2. Payment Methods:
- Customers using electronic checks have the highest churn rate of 45%, while those using other payment methods such as credit cards or bank transfers have a churn rate between 15-18%.
- **Implication**: Issues related to convenience and trust with electronic payments may contribute to higher churn. Encouraging customers to switch to more stable payment methods could reduce churn.

### 3. Tenure and Churn:
- Customers with less than one year of tenure are the most likely to churn, with a 50% churn rate. This rate decreases to 35% for 1-3 years of tenure and drops to 15% for customers who have been with the company for more than three years.
- **Implication**: Engaging customers early is essential to reduce churn, especially within the first year.

### 4. Internet Service Type:
- Fiber Optic customers have a higher churn rate (30%) compared to DSL customers (20%).
- **Implication**: Service quality issues or competition may contribute to this difference. Improving customer satisfaction with service speed and reliability could help retain Fiber Optic customers.

### 5. Senior Citizens:
- Senior citizens (aged 65+) have a churn rate of 41%, compared to 26% for non-senior citizens.
- **Implication**: Tailored retention programs for senior customers may help reduce churn in this demographic.

---

## Visualizations & Data Insights

- **Bar Charts and Line Graphs**: These visualizations illustrate the disparity in churn rates based on contract types, payment methods, and customer tenure. 
- **Churn by Payment Methods**: Customers using electronic checks have a churn rate nearly three times higher than those using more secure payment methods like credit cards.
- **Churn by Tenure**: Churn decreases as customer tenure increases, highlighting the importance of early customer engagement.



## Recommendations

1. **Promote Long-Term Contracts**: Offer incentives for customers to commit to longer contracts to reduce churn.
2. **Address Payment Method Concerns**: Implement campaigns encouraging customers to switch from electronic checks to more reliable payment methods.
3. **Early Engagement**: Focus on improving customer experience within the first year, as churn is highest during this period.
4. **Special Retention Programs for Senior Citizens**: Create personalized offers or assistance programs to retain senior customers.



