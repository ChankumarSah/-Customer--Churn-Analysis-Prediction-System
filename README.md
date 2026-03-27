# 📊 Customer Churn Analysis & Prediction System

## 🚀 Project Overview

This project is a complete **end-to-end data analytics + machine learning solution** designed to analyze customer churn and predict future churners.

It combines:

* 🗄️ SQL (Data Cleaning & Transformation)
* 📊 Power BI (Interactive Dashboard)
* 🤖 Python (Machine Learning - Random Forest)

The goal is to help businesses **identify churn patterns and take proactive actions to retain customers.**

---

## 📸 Project Preview

### 📊 Churn Analysis Dashboard (Summary)

![Churn Summary](churn_analysis.png)

### 🤖 Churn Prediction Dashboard

![Churn Prediction](churn_analysis_1.png)

---

## 🧠 Problem Statement

Customer churn is a major challenge for telecom and subscription-based businesses.

This project answers:

* Why are customers leaving?
* Which customers are likely to churn?
* How can businesses reduce churn?

---

## 🛠️ Tech Stack

* **SQL** → Data cleaning, transformation, feature engineering
* **Power BI** → Dashboard & visualization
* **Python (Scikit-learn)** → Machine Learning model
* **Jupyter Notebook** → Model development

---

## 📂 Project Structure

```
📁 Customer-Churn-Analysis-Prediction-System
│
├── 📁 datasets/
│
├── 📁 sql/
│
├── 📁 PowerBI and Python code and Inst/
│
├── 📄 churn_analysis.png
├── 📄 churn_analysis_1.png
│
└── 📄 README.md
```

---

## 🔍 Data Processing (SQL)

* Performed data exploration using GROUP BY and aggregations
* Handled null values using ISNULL
* Transformed raw data into structured production tables
* Created views:

  * `vw_ChurnData`
  * `vw_JoinData`

---

## 🔄 Data Transformation (Power Query)

* Created calculated columns:

  * Churn Status (0/1)
  * Monthly Charge Range

* Created mapping tables:

  * Age Group
  * Tenure Group

* Unpivoted service columns for better analysis

---

## 📊 Power BI Dashboard

### Key Metrics:

* Total Customers
* New Joiners
* Total Churn
* Churn Rate

### Features:

* Interactive filters
* Customer segmentation
* Revenue insights
* Churn trend analysis

---

## 🤖 Machine Learning Model

Model Used: **Random Forest Classifier**

### Steps:

* Data preprocessing
* Label encoding
* Train-test split
* Model training
* Model evaluation using:

  * Confusion Matrix
  * Classification Report

### Output:

* Predicts customers likely to churn
* Generates a list of high-risk customers

---

## 📈 Key Insights

* Customers with shorter tenure are more likely to churn
* Higher monthly charges increase churn probability
* Contract type significantly impacts retention
* Certain services help reduce churn

---

## 🎯 Business Impact

* Early identification of high-risk customers
* Improved retention strategies
* Increased revenue by reducing churn
* Data-driven decision making

---

## ⚡ How to Run

1. Execute SQL queries to prepare the dataset
2. Load data into Power BI
3. Apply Power Query transformations
4. Run the Python ML model in Jupyter Notebook
5. Analyze insights using dashboard

---

## 🏆 Future Improvements

* Deploy model using Flask or Streamlit
* Automate data pipeline
* Use advanced models like XGBoost
* Enable real-time churn prediction

---

## 👨‍💻 Author

**Chandan Sah**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
