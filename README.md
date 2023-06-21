# Customer Churn Prediction & Market Basket Analysis

## Project Description

This repository contains a data mining project conducted on a retail dataset. The project mainly focused on predicting customer churn and conducting market basket analysis. These are crucial components of customer analytics in the retail industry and provide critical insights for making data-driven business decisions.

## Dataset

The dataset used in this project is sourced from the UCI Machine Learning Repository. It contains purchase records of around 4000 customers over a one-year period (from 2022 to 2023). Each record includes attributes such as the invoice number, stock code, description, quantity, invoice date, price, customer ID, and country.

## Methodology

### Data Cleaning

The initial step involved cleaning the dataset which included handling missing data, removing cancellations, and transforming data types where required.

### Customer Churn Prediction

For customer churn prediction, Recency, Frequency, and Monetary value (RFM) were calculated for each customer. A churn label was then assigned based on recency. The data was split into a training and test set. Logistic Regression was used to predict whether a customer will churn or not. The model's performance was evaluated using accuracy, precision, recall, and F1 score.

### Market Basket Analysis

For the market basket analysis, the dataset was preprocessed into a suitable format, and the Apriori algorithm was used to find frequent itemsets. From these itemsets, association rules were then generated.

## Findings

### Customer Churn Prediction

The logistic regression model performed exceptionally well in predicting customer churn. The model achieved an accuracy of 99.53%, a precision of 100%, a recall of 98.62%, and an F1 score of 99.31%. These results indicate a high ability of the model to predict both the churning and non-churning customers accurately.

### Market Basket Analysis

The market basket analysis revealed several interesting association rules among the products. For example, customers who buy 'CHILDS GARDEN TROWEL BLUE' are highly likely to also buy 'CHILDS GARDEN TROWEL PINK'. Similarly, customers who purchase items from the 'POPPY'S PLAYHOUSE' series often buy others in the series.

These insights can be used to develop strategies for product placement, recommendations, and targeted marketing to enhance sales.

## Conclusion

The analysis conducted in this project offers valuable insights that can help the retail business in its marketing and customer retention strategies. Predicting customer churn enables businesses to take proactive actions to retain customers, which is often more cost-effective than acquiring new customers. Moreover, understanding which products are frequently bought together can aid in optimizing marketing strategies and boosting sales.
