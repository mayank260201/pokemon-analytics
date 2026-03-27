# Pokémon Analytics: From Data Exploration to Prediction

## 📊 Project Overview

This project analyzes a dataset of 898 Pokémon to understand what differentiates "special" Pokémon (Legendary, Mythical, and Pseudo-Legendary) from regular ones.

The analysis combines data cleaning, exploratory data analysis (EDA), feature engineering, and machine learning to uncover patterns and build predictive models.

---

## 🛠️ Tools & Technologies

- Python (pandas, numpy)
- Data Visualization (matplotlib, seaborn)
- Machine Learning (scikit-learn)
- SQL (PgAdmin4)
- Power BI
- Excel
- VS Code / Jupyter Notebook

---

## 🔍 Key Steps

### 1. Data Cleaning
- Removed irrelevant columns
- Handled missing values
- Standardized column names

### 2. Exploratory Data Analysis
- Compared stats across Pokémon types
- Analyzed distribution of power levels
- Identified patterns in special vs non-special Pokémon

### 3. Feature Engineering
- Created `Total_Power` as a combined stat metric
- Created `Is_Special` target variable

### 4. Machine Learning
- Logistic Regression and Random Forest models
- Evaluated using precision, recall, and F1-score
- Explored threshold tuning for recall improvement

---

## 📈 Key Insights

- Special Pokémon are significantly stronger on average, but not always
- Total Power is the strongest predictor of special status
- Some non-special Pokémon are strong enough to resemble special ones
- Some special Pokémon have low stats, making them hard to detect

---

## ⚠️ Limitations

- Overlap between classes prevents perfect classification
- Some special Pokémon do not follow general patterns
- Model performance is limited by available features

---

## 📌 Conclusion

The project demonstrates how data patterns can guide prediction, but also highlights the limitations of relying solely on statistical features when real-world exceptions exist.
