# 🏦 Loan Approval Prediction

A Machine Learning project that predicts whether a loan application is likely to be approved or rejected based on applicant information.

This project was developed as part of my **InternSpark Data Science Internship – Task 2**.

---

## 📌 Project Overview

Loan approval is an important decision in the banking and financial sector. Banks consider different factors such as applicant income, credit history, loan amount, employment status and property area before making a decision.

In this project, Machine Learning classification techniques are used to predict loan approval status.

Two Machine Learning models were developed and compared:

- Logistic Regression
- Random Forest Classifier

The models were evaluated using:

- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- Threshold Analysis

---

## 🎯 Project Objective

The main objectives of this project are:

- Analyze the loan application dataset
- Clean and preprocess the data
- Handle missing values
- Encode categorical variables
- Scale numerical features
- Handle class imbalance
- Train classification models
- Compare model performance
- Analyze prediction thresholds
- Identify important features
- Interpret the results from a business perspective

---

## 📂 Dataset

The dataset contains **614 loan application records** and **13 columns**.

### Main Features

| Feature | Description |
|---|---|
| Loan_ID | Unique loan application ID |
| Gender | Applicant gender |
| Married | Marital status |
| Dependents | Number of dependents |
| Education | Education level |
| Self_Employed | Self-employment status |
| ApplicantIncome | Applicant income |
| CoapplicantIncome | Co-applicant income |
| LoanAmount | Requested loan amount |
| Loan_Amount_Term | Loan repayment term |
| Credit_History | Credit history |
| Property_Area | Property location |
| Loan_Status | Loan approval status |

### Target Variable

```text
Y → Approved
N → Rejected
