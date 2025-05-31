# Insurance Company Data Analysis and Model Evaluation

## Project Statement

The Sure Tomorrow insurance company wants to leverage machine learning to improve its business operations. This project aims to assist them in several key tasks related to customer data analysis and predictive modeling.

## Project Description

This project focuses on using machine learning to address the following tasks for the "Sure Tomorrow" insurance company:

1.  **Customer Similarity:** Developing a method to identify customers similar to a given customer, enabling targeted marketing campaigns.
2.  **Benefit Prediction:** Building a predictive model to determine whether a new customer is likely to receive insurance benefits.
3.  **Benefit Count Prediction:** Training a linear regression model to predict the number of insurance benefits a customer is likely to receive.
4.  **Data Obfuscation:** Implementing a data transformation algorithm to protect sensitive customer information while preserving the predictive power of the linear regression model.

## Analysis Goals

* **Customer Similarity:** Implement a K-Nearest Neighbors (KNN) algorithm to find similar customers.
* **Benefit Prediction:** Train and evaluate a classification model (e.g., Logistic Regression, Decision Tree) to predict whether a customer will receive benefits. Compare its performance against a dummy regressor.
* **Benefit Count Prediction:** Train and evaluate a linear regression model to predict the number of benefits.
* **Data Obfuscation:** Develop and apply a data masking technique to protect customer data and assess its impact on the linear regression model's performance.

## Technologies Used

* **Python**
* **Pandas:** For data loading, manipulation, and analysis.
* **NumPy:** For numerical operations.
* **Scikit-learn:** For machine learning models (KNN, Linear Regression, and potentially others), data preprocessing, and evaluation metrics.
* **Matplotlib / Seaborn:** For data visualization.

## Dataset

The project uses a dataset containing customer information relevant to insurance benefits.

* **File Name:** `insurance_us.csv`
* **Content:** Includes features such as customer ID, gender, age, income, number of family members, and the number of insurance benefits received over the past five years (target variable).
