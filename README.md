# 🏦 Customer Loan Approval Prediction (ML Classification)

## 📌 Overview

This project demonstrates an end-to-end Machine Learning pipeline to predict whether a customer's loan will be **Approved (1)** or **Rejected (0)** based on demographic and financial data.

It covers the complete ML workflow from data preprocessing to model evaluation.

---

## 🎯 Business Problem

Banks and financial institutions need to decide whether to approve a loan application.

This model helps in:

* Reducing risk
* Automating decision-making
* Improving approval efficiency

---

## 📂 Dataset

* Dataset: `loan_approval_1000.csv`
* Total records: **1000**
* Contains:

  * Numerical features (e.g., Income)
  * Categorical features (e.g., Employment_Type)
  * Target column: **Loan_Approved (0 or 1)**

---

## ⚙️ Steps Performed

### 1. Data Loading

* Loaded dataset using Pandas

### 2. Null Value Analysis

* Identified missing values using `.isnull().sum()`

### 3. Data Cleaning (Imputation)

* Numerical columns → filled with **Median**
* Categorical columns → filled with **Mode**

### 4. Encoding

* Converted categorical data using **Label Encoding**

### 5. Train-Test Split

* Split data into:

  * **80% Training**
  * **20% Testing**

### 6. Model Training

* Algorithm used: **Logistic Regression**

### 7. Model Evaluation

* Accuracy Score
* Classification Report
* Confusion Matrix (visualized using Seaborn)

---

## 📊 Results

* **Accuracy:** 79%

### Classification Performance:

* Good performance on class **0 (Not Approved)**
* Moderate performance on class **1 (Approved)**

---

## 📈 Confusion Matrix

* Visualized using heatmap for better understanding of predictions

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## ▶️ How to Run

1. Open the notebook in Google Colab
2. Upload the dataset `loan_approval_1000.csv`
3. Run all cells step by step

---

## 💡 Key Learnings

* Handling missing data effectively
* Encoding categorical variables
* Building a classification model
* Evaluating model performance

---

## 👩‍💻 Author

Priyadharshini R
