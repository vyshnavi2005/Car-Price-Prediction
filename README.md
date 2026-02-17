# 🚗 Used Car Price Prediction

## 📌 Project Overview

This project focuses on analyzing and predicting used car prices using Machine Learning techniques. A real-world dataset collected from an online car marketplace is used to understand the factors influencing resale prices and to build predictive models based on historical data.

The project demonstrates a complete end-to-end ML workflow including data cleaning, feature engineering, model building, and evaluation.

---

## 📂 Dataset

**Dataset Used:** Quikr Used Car Price Dataset  

### Features:
- Car Name
- Company (Brand)
- Manufacturing Year
- Kilometers Driven
- Fuel Type
- Selling Price

After cleaning and preprocessing, the dataset contains **819 records** used for training and evaluation.

---

## 🔄 Project Workflow

### 1️⃣ Exploratory Data Analysis (EDA)
- Analyzed price distribution
- Studied impact of car age
- Examined mileage trends
- Compared fuel types
- Identified brand influence
- Handled missing values and inconsistencies

### 2️⃣ Data Cleaning & Preprocessing
- Converted textual price and mileage into numeric format
- Removed invalid and missing entries
- Created a new feature **Age** to represent vehicle depreciation

### 3️⃣ Feature Engineering

**Numerical Features:**
- Year
- Kilometers Driven
- Age

**Categorical Features:**
- Company
- Fuel Type
- Car Name

### 4️⃣ Preprocessing Pipeline
- Missing value imputation
- Feature scaling (StandardScaler)
- One-Hot Encoding for categorical features

---

## 🤖 Machine Learning Models

### ✔ Linear Regression
- Baseline model
- Simple and interpretable
- Achieved strong performance on structured data

### ✔ Random Forest Regressor
- Ensemble learning method
- Captures non-linear relationships
- Used for feature importance analysis

---

## 📊 Model Evaluation

Models were evaluated using:

- **R² Score**
- **Root Mean Squared Error (RMSE)**

### 🏆 Results

- Linear Regression achieved an **R² score ≈ 0.72**
- Linear Regression performed better than Random Forest on this dataset
- Car age, mileage, brand, and model significantly affect resale prices

---

## 📈 Feature Importance

Random Forest analysis showed the most important features:

- Car Age
- Manufacturing Year
- Kilometers Driven
- Brand
- Specific Car Models

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---
## Conclusion

This project successfully combines data analysis, preprocessing, and machine learning to predict used car prices and extract meaningful insights about price-driving factors.
