## Optimizing Telemarketing Term Deposit Conversion Using Predictive Analytics

## 1. Project Overview

This capstone project uses predictive analytics and Binary Logistic Regression to identify customers who are more likely to subscribe to bank term deposits. The analysis uses the Bank Marketing dataset containing 41,188 customer records.

## 2. Business Problem

Traditional telemarketing campaigns involve calling large numbers of customers, which can lead to inefficient resource utilization and unnecessary calls.

This project explores how predictive modelling can help banks identify potential customers and improve campaign targeting.

## 3. Project Objectives

- Predict customer subscription to term deposits.
- Identify important factors influencing customer decisions.
- Develop and compare multiple logistic regression models.
- Evaluate model performance.
- Provide data-driven recommendations for improving telemarketing efficiency.

## 4. Dataset Description

- Dataset: Bank Marketing Dataset
- Total observations: 41,188
- Target variable: Term deposit subscription (Yes/No)

## 5. Tools and Technologies

- R / RStudio
- Binary Logistic Regression
- Data Preprocessing
- Dummy Variable Encoding
- Correlation Analysis
- AIC and Residual Deviance
- Variance Inflation Factor (VIF)
- Confusion Matrix

## 6. Methodology

1. Data preparation and preprocessing.
2. Variable encoding and exploratory analysis.
3. Training and testing data split (70:30).
4. Development of 14 sequential logistic regression models.
5. Model comparison using AIC and Residual Deviance.
6. Multicollinearity assessment using VIF.
7. Model evaluation using confusion matrices and probability thresholds.

## 7. Model Results

- Final selected model: Model 14
- AIC: 16,548
- Residual Deviance: 16,518
- VIF values: Below 5
- Classification accuracy: 89.83% at a 0.60 probability threshold.

## 8. Key Business Insights

The analysis identified customer, campaign and macroeconomic variables associated with term deposit subscription behaviour.

The findings support the use of predictive customer targeting to improve telemarketing campaign efficiency.

## 9. Business Recommendations

- Prioritize customers with higher predicted subscription probabilities.
- Improve telemarketing resource allocation.
- Use customer interaction history for campaign planning.
- Reduce unnecessary calls through data-driven targeting.

## 10. Project Deliverables

- `logistic-regression-06.html` – RStudio analysis and code report.
- `telemarketing-predictive-analytics-capstone.pdf` – Complete capstone project report.

## 11. Project Information

**Programme:** IIM Sirmaur EDGE – Essentials of Data, GenAI & Execution

**Project Type:** Team Capstone Project

**Team Member:** Ruchi Kumari

## 12. Author

**Ruchi Kumari**

MBA – Finance & Business Analytics

- GitHub: https://github.com/ruckumari2003-dev
- LinkedIn: https://www.linkedin.com/in/ruchi-kumari-2b8928286
