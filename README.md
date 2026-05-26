# Loan-Approval-Prediction-Model-SPSS

# Loan Approval Prediction using IBM SPSS Modeler

## 📌 Project Overview

This project focuses on predicting whether a loan application will be approved or rejected using Machine Learning techniques in IBM SPSS Modeler. The system analyzes applicant information such as income, education, credit history, loan amount, and property area to generate predictions.

The project compares multiple classification algorithms and evaluates their performance using accuracy metrics.

---

## 🎯 Objectives

* Predict loan approval status using machine learning
* Perform data preprocessing and transformation
* Compare Logistic Regression and C5.0 Decision Tree models
* Identify the most influential factors affecting loan approval
* Build a user-input based prediction workflow

---

## 🛠️ Technologies Used

* IBM SPSS Modeler
* Machine Learning
* Data Preprocessing
* Classification Algorithms
* CSV Dataset

---

## 📂 Dataset Information

Dataset Source: Kaggle Loan Prediction Dataset

### Dataset Features

* Gender
* Married
* Dependents
* Education
* Self_Employed
* ApplicantIncome
* CoapplicantIncome
* LoanAmount
* Loan_Amount_Term
* Credit_History
* Property_Area
* Loan_Status

---

## 🔄 Project Workflow

Dataset → Data Cleaning → Auto Data Preparation → Missing Value Handling → Partitioning → Logistic Regression & C5.0 Decision Tree → Model Evaluation → Loan Prediction

---

## 🤖 Machine Learning Models Used

### 1. Logistic Regression

* Used for binary classification
* Training Accuracy: 80.75%
* Testing Accuracy: 82.45%

### 2. C5.0 Decision Tree

* Rule-based classification model
* Training Accuracy: 80.05%
* Testing Accuracy: 82.98%

✅ C5.0 Decision Tree performed best.

---

## 📊 Results and Findings

* Both models achieved more than 80% accuracy
* Credit_History was the most influential feature
* No major overfitting was observed
* Decision Tree slightly outperformed Logistic Regression

---

## 👤 User Input Prediction

A User Input node was integrated into the SPSS workflow to allow real-time prediction for manually entered applicant data.

---

## 🚀 Future Scope

* Web application integration
* Real-time banking systems
* Advanced ML algorithms
* Cloud deployment

---

## 📷 Project Screenshot

Add the SPSS stream screenshot inside the `asset` folder.

---

## ✅ Conclusion

The project successfully developed a machine learning-based loan approval prediction system using IBM SPSS Modeler. Among the tested models, the C5.0 Decision Tree achieved the highest prediction accuracy and provided interpretable decision-making logic.

---

## 📎 Repository Structure

```text
loan-approval-prediction-spss/
│
├── asset/
│   └── screenshot.png
├── loan_approval_prediction.pdf
├── PROBLEM STATEMENT.pdf
├── dataset.csv
├── stream/
│   └── loan_prediction.str
└── README.md
```
