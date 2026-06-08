# CreditWise-Loan-Approval-System
End-to-end machine learning project for loan approval prediction using Logistic Regression, KNN, and Naive Bayes, with comprehensive data analysis and model comparison.


# Loan Approval Classification System Using Machine Learning

## Project Overview

This project uses Machine Learning techniques to determine whether a loan application should be approved or rejected based on applicant information. The system analyzes various applicant attributes and builds classification models to support loan approval decisions.

## Problem Statement

Financial institutions receive a large number of loan applications and must evaluate applicant eligibility efficiently. Manual evaluation can be time-consuming and inconsistent. This project develops a machine learning-based classification system that predicts whether a loan application should be approved or not using historical loan data.

## Dataset

The dataset contains information about loan applicants, including demographic and financial details such as:

* Applicant_ID 
* Applicant_Income 
* Coapplicant_Income
* Employment_Status
* Age
* Marital_Status
* Dependents
* Credit_Score
* Existing_Loans 
* DTI_Ratio
* Savings 
* Collateral_Value
* Loan_Amount
* Loan_Term
* Loan_Purpose
* Property_Area
* Education_Level
* Gender
* Employer_Category
* Loan_Approved   

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Handling Missing Values
4. Exploratory Data Analysis (EDA)
5. Feature Encoding
6. Correlation Analysis
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Model Comparison
11. Feature Engineering

## Exploratory Data Analysis

The following analyses were performed:

1. Loan Approval Distribution - A pie chart was used to visualize the proportion of approved and rejected loan applications. This helped understand the class distribution within the dataset.

2. Applicant Income Analysis - A histogram was created to analyze the distribution of applicant income and examine its relationship with loan approval status.

3. Correlation Analysis - A correlation heatmap was generated to identify relationships between numerical features and understand feature dependencies.

## Machine Learning Models Used

### 1. Logistic Regression

A linear classification algorithm used as a baseline model.

### 2. K-Nearest Neighbors (KNN)

A distance-based classification algorithm.

### 3. Naive Bayes

A probabilistic classification algorithm based on Bayes' theorem.

## Evaluation Metrics

The models were evaluated using:

* Accuracy Score
* Precision Score
* Recall Score
* F1-Score
* Confusion Matrix

## Results

The performance of all models was compared using classification metrics.

**Best Performing Model:** Naive Bayes

Naive Bayes achieved the highest Precision and Recall scores among the tested models, making it the most effective model for this dataset.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## Project Structure

```text
Loan-Approval-Classification/
│
├── dataset/
│   └── loan_data.csv
│
├── images/
│   ├── correlation_heatmap.png
│   ├── loan_distribution.png
│   ├── confusion_matrix.png
│   └── model_comparison.png
│
├── Loan_Approval_Classification.ipynb
├── README.md
├── requirements.txt
└── .gitignore

```
## Results

Three machine learning classification models were trained and evaluated:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Naive Bayes

The models were compared using Accuracy, Precision, Recall, and F1-Score.

Initially, Naive Bayes achieved the best Precision and Recall scores among the evaluated models.

After model comparison, feature engineering techniques were applied to improve model performance. The engineered features increased the Precision score, indicating fewer false positive predictions. However, this improvement resulted in a decrease in Recall, meaning that some approved loan cases were missed.

This highlights the trade-off between Precision and Recall and demonstrates the impact of feature engineering on classification performance.


## Author
Priyanka Damodar
B.Tech (Artificial Intelligence and Data Science)
