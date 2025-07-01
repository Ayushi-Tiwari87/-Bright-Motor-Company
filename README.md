# -Bright-Motor-Company
# Bright Automotive Customer Insights Project

This project analyzes customer demographics, financial profiles, and car preferences to uncover patterns in purchasing behavior. The goal is to help **Bright Automotive** make data-driven decisions in marketing, product alignment, and customer targeting.

---

## 📌 Problem Statement

Bright Automotive wants to analyze customer demographics, financial profiles, and car preferences to understand buying patterns.  
The goal is to uncover insights that can drive better marketing, pricing, and product alignment strategies.

---

## 🎯 Objective

To discover patterns in customer behavior and identify the key features that influence the selection of a car (e.g., SUV vs. Sedan).  
The insights will help in:

- Optimizing marketing campaigns  
- Designing targeted offers  
- Planning inventory and sales tactics  

---

## 📊 Dataset Description

- Customer attributes like Age, Gender, Marital Status, Education, Profession
- Financial indicators like Salary, Partner Salary, Loan status
- Car preference: Make (SUV or Sedan)
- No missing or duplicate values after cleaning

---

## 🧪 Project Workflow

1. **Data Loading and Cleaning**
   - Removed null values in critical columns
   - Converted datatypes and ensured categorical consistency

2. **Exploratory Data Analysis (EDA)**
   - Univariate and bivariate analysis using plots
   - Correlation heatmaps and distribution checks

3. **Feature Engineering**
   - Created `Total_salary` and `Has_Partner_Income` as new features

4. **Data Preparation**
   - Label Encoding for categorical columns
   - Train/Test split for modeling

5. **Model Building**
   - Used `DecisionTreeClassifier` to predict car type
   - Evaluated using accuracy, precision, recall, and F1-score

---

## 🧠 Final Model Performance

- **Model**: Decision Tree Classifier  
- **Accuracy**: 83.4%  
- **Interpretability**: High  
- **Balanced prediction across SUV and Sedan classes**

---

## 🔍 Key Insights

- Higher income groups (with or without partners) prefer SUVs
- Education level influences car price and make preferences
- Partner’s income status and marital status help identify high-value buyers
- Personal and house loans do not always discourage SUV buyers

---

## 📈 Business Impact

- Helps Bright Automotive segment customers based on income, education, and profession
- Enables personalized marketing strategies
- Supports sales forecasting and inventory planning

---

## 🛠 Tech Stack

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- scikit-learn for modeling
- Jupyter Notebook
- Git & GitHub

---
