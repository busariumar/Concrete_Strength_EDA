# 🏗️ Concrete Compressive Strength — Exploratory Data Analysis

This repository contains an exploratory data analysis (EDA) of the Concrete Compressive Strength dataset.  
The project focuses on understanding feature distributions, detecting and handling outliers, and examining relationships between material components and concrete strength.

---

## 📌 Project Objectives

The objectives of this project are to:

- Explore the distribution of individual features
- Identify skewness and outliers using statistical methods
- Analyze relationships between material components and compressive strength
- Examine correlations and potential multicollinearity
- Prepare the dataset for future predictive modeling

---

## 📊 Dataset Overview

- **Observations:** 1030 rows  
- **Features:** 9 numerical variables  
- **Target Variable:** Concrete compressive strength (MPa)

### Features include:
- Cement
- Blast furnace slag
- Fly ash
- Water
- Superplasticizer
- Coarse aggregate
- Fine aggregate
- Age
- Compressive strength

---

## 🔍 Exploratory Data Analysis

The EDA process includes:

### Univariate Analysis
- Distribution plots to examine data shape and skewness
- Boxplots for identifying potential outliers
- Quartile and IQR-based statistical summaries

### Outlier Detection & Handling
- Outliers identified using the Interquartile Range (IQR) method  
- Extreme values were capped using the median to preserve dataset size

### Bivariate Analysis
- Pairplots to visualize relationships between features
- Correlation heatmap to identify linear relationships and multicollinearity

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ✅ Key Insights

- Cement and age show strong positive relationships with compressive strength
- Water content exhibits a negative relationship with strength
- Several features are right-skewed and contain outliers
- Correlation analysis highlights important feature interactions

---

## 🚀 Next Steps

- Feature scaling and transformation
- Predictive modeling using regression techniques
- Model evaluation and performance comparison

---

## 📁 Project Structure

Concrete-Strength-EDA/
│
├── Concrete_Strength_EDA.ipynb
├── README.md


---

## 📎 Notes

This project focuses solely on exploratory data analysis.  
Modeling and prediction will be addressed in future work.

