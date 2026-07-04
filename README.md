# 📊 Customer Segmentation Analysis (RFM + KMeans)

## 📌 Project Overview
This project focuses on **customer segmentation using behavioral data** from an online retail dataset. The goal is to identify different types of customers (high-value, regular, and inactive) using RFM analysis and KMeans clustering to support data-driven marketing decisions.

---

## 📁 Dataset Information
- Dataset: Online Retail Dataset  
- Contains transaction-level details such as:
  - Invoice number
  - Product description
  - Quantity
  - Invoice date
  - Customer ID
  - Unit price

---

## 🎯 Objective
- Understand customer purchasing behavior
- Segment customers based on RFM (Recency, Frequency, Monetary)
- Identify high-value and at-risk customers
- Provide insights for business decision-making

---

## ⚙️ Workflow

### 1. Data Cleaning
- Removed missing values and duplicates
- Handled incorrect or null customer IDs
- Created total transaction amount

### 2. Exploratory Data Analysis (EDA)
- Monthly revenue trends
- Monthly active users
- Monthly order trends
- Customer spending distribution

### 3. RFM Analysis
- **Recency** → How recently a customer purchased
- **Frequency** → How often a customer purchases
- **Monetary** → How much a customer spends

### 4. Customer Segmentation
- Applied **KMeans Clustering**
- Grouped customers into segments:
  - High-Value Customers
  - Regular Customers
  - At-Risk Customers
  - Lost Customers

---

## 📊 Key Insights
- A small percentage of customers contribute to a large portion of revenue
- Many customers are inactive and need re-engagement
- High-value customers show consistent purchasing behavior
- Segmentation helps in targeted marketing campaigns

---

## 📈 Visualizations
- Customer Monetary Distribution  
- Customer Segmentation Distribution  
- Monthly Active Users Trend  
- Monthly Order Trend  
- Monthly Revenue Trend  
- Monthly Unique Orders  

---

## 🛠 Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure
