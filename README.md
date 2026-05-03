# 📊 Customer Churn Analysis & Power BI Dashboard

## 🔍 Project Overview

This project focuses on analyzing customer churn behavior using Python (EDA) and visualizing insights through an interactive Power BI dashboard. The goal is to identify key factors that contribute to customer churn and provide actionable business insights to improve customer retention.

---

## 🎯 Objectives

* Understand customer behavior and churn patterns
* Perform data cleaning and exploratory data analysis (EDA)
* Identify key drivers of churn
* Build an interactive Power BI dashboard for business insights
* Provide recommendations to reduce churn

---

## 📁 Dataset

* Dataset: Telco Customer Churn
* Records: 7,043 customers
* Features: 21 columns including demographics, services, and billing

---

## 🛠️ Tools & Technologies

* Python (Pandas, NumPy)
* Visualization: Matplotlib, Seaborn
* Power BI (Dashboard & Reporting)
* Jupyter Notebook

---

## 🔄 Data Processing Steps

### 1. Data Loading

* Loaded dataset using Pandas
* Reviewed structure using `.head()`, `.shape()`, `.info()`

### 2. Data Cleaning

* Converted `TotalCharges` to numeric
* Removed missing values (~0.15%)
* Dropped unnecessary columns (`customerID`, `tenure`)

### 3. Feature Engineering

* Created **tenure groups** (e.g., 1–12, 13–24 months)
* Converted target variable `Churn` into binary (Yes=1, No=0)
* Applied one-hot encoding for categorical variables

---

## 📊 Exploratory Data Analysis (EDA)

### 📌 Key Insights

#### 1. Churn Distribution

* 73% customers retained
* 27% customers churned
* Dataset is **imbalanced**

---

#### 2. Tenure Analysis

* Customers with **low tenure (1–12 months)** have the highest churn
* Long-term customers are more likely to stay

---

#### 3. Monthly Charges

* Higher monthly charges → higher churn probability

---

#### 4. Total Charges

* Customers with low total charges show higher churn
* Indicates churn happens early in customer lifecycle

---

#### 5. Contract Type

* **Month-to-month contracts** have highest churn
* Long-term contracts (1–2 years) reduce churn significantly

---

#### 6. Services Impact

High churn observed when:

* No Online Security
* No Tech Support

---

#### 7. Payment Method

* **Electronic check users** show highest churn rate

---

#### 8. Demographics

* Gender has little to no impact
* Non-senior citizens show slightly higher churn

---

## 📈 Correlation Analysis

* Strong churn drivers:

  * Month-to-month contracts
  * Fiber optic internet
  * Lack of support services

* Weak or no impact:

  * Gender
  * Phone service
  * Multiple lines

---

## 📊 Power BI Dashboard

### Dashboard Features:

* Churn Rate KPI
* Customer Segmentation
* Revenue Impact Analysis
* Tenure-based insights
* Interactive filters (Contract, Payment Method, Services)

### Key Business Insights:

* High churn occurs in early customer lifecycle
* Pricing and contract flexibility influence churn
* Service quality (support/security) is critical

---

## 💡 Business Recommendations

* Improve onboarding for new customers
* Encourage long-term contracts with incentives
* Target high-risk customers with retention campaigns
* Improve tech support and security services
* Review pricing strategy for high-charge customers

---
sample of powerBI dashboard

<img width="1420" height="790" alt="image" src="https://github.com/user-attachments/assets/1e11a8e5-3369-43d9-8629-9ead2a07eae0" />


---

## 📌 Author

**Yahya Ramadhan**
Data Science Student | Aspiring Data Analyst

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and feel free to fork or contribute!
