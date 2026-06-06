# 📺 Advertising Sales Prediction using Machine Learning

## 📖 Project Overview

This project aims to predict product sales based on advertising expenditure across different marketing channels such as TV, Radio, and Newspaper.

By analyzing advertising budgets and their impact on sales, machine learning models were trained and evaluated to identify the most effective advertising medium and accurately predict future sales.

---

## 🎯 Objective

To build a machine learning model that can predict product sales based on advertising spending and identify which advertising channel contributes the most to sales growth.

---

## 📊 Dataset Information

The dataset contains advertising expenditure data for:

- TV Advertising Budget
- Radio Advertising Budget
- Newspaper Advertising Budget

Target Variable:

- Sales

Dataset Size:

- 200 Records
- 4 Features

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Project Workflow

### 1. Data Preprocessing

- Removed unnecessary columns
- Checked missing values
- Checked duplicate records
- Prepared data for model training

### 2. Exploratory Data Analysis (EDA)

Performed:

- Sales Distribution Analysis
- TV vs Sales Analysis
- Radio vs Sales Analysis
- Newspaper vs Sales Analysis
- Pairplot Visualization
- Correlation Heatmap

### 3. Model Building

The following regression models were trained and evaluated:

- Linear Regression
- Ridge Regression
- Random Forest Regression

### 4. Model Evaluation

Evaluation Metrics:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📈 Model Performance

| Model | R² Score |
|---------|---------|
| Linear Regression | 0.899 |
| Ridge Regression | 0.899 |
| Random Forest Regression | 0.981 |

🏆 **Best Model: Random Forest Regression**

---

## 📊 Feature Importance Analysis

| Feature | Importance |
|---------|-----------|
| TV | 0.625 |
| Radio | 0.362 |
| Newspaper | 0.013 |

### Key Insights

- TV advertising was the most influential factor affecting sales.
- Radio advertising also contributed significantly to sales growth.
- Newspaper advertising had very little impact on sales performance.

---

## 🚨 Overfitting Analysis

Training R² Score: **0.996**

Testing R² Score: **0.981**

The small difference between training and testing performance indicates that the model generalizes well and does not suffer from significant overfitting.

---

## 📈 Visualizations Included

- Sales Distribution Plot
- Scatter Plots
- Pairplot
- Correlation Heatmap
- Actual vs Predicted Plot
- Feature Importance Plot

---

## 💡 Business Insights

- Businesses should prioritize TV advertising for maximum sales impact.
- Radio advertising can effectively support marketing campaigns.
- Newspaper advertising contributes minimally compared to TV and Radio.

---

## 🚀 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Model Deployment using Streamlit
- Testing Advanced Ensemble Models

---

## 👩‍💻 Author

Nayani

Machine Learning Internship Project – OIBSIP

---

⭐ If you found this project useful, consider giving it a star!
