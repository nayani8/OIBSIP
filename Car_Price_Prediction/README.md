# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict the selling price of used cars using Machine Learning techniques. The model analyzes various factors such as present price, car age, fuel type, transmission type, ownership history, and kilometers driven to estimate the resale value of a car.

The project follows a complete Machine Learning workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and model comparison.

---

## 🎯 Objective

To build a regression model capable of predicting the selling price of a used car based on its characteristics.

---

## 📊 Dataset Information

The dataset contains information about used cars, including:

* Car Name
* Year
* Selling Price (Target Variable)
* Present Price
* Driven Kilometers
* Fuel Type
* Selling Type
* Transmission
* Number of Previous Owners

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 🔍 Project Workflow

### 1. Data Cleaning

* Checked for missing values
* Removed duplicate records
* Dropped unnecessary features

### 2. Feature Engineering

Created a new feature:

**Car_Age = Current Year - Manufacturing Year**

### 3. Exploratory Data Analysis (EDA)

Performed various visualizations including:

* Selling Price Distribution
* Car Age vs Selling Price
* Present Price vs Selling Price
* Fuel Type Analysis
* Transmission Analysis
* Owner Analysis
* Correlation Heatmap

### 4. Data Preprocessing

* Label Encoding for categorical features
* Train-Test Split (80:20)

### 5. Model Building

The following regression models were trained and evaluated:

* Linear Regression
* Ridge Regression
* Random Forest Regression

---

## 📈 Model Performance

| Model                    | R² Score |
| ------------------------ | -------- |
| Linear Regression        | 0.741    |
| Ridge Regression         | 0.744    |
| Random Forest Regression | 0.576    |

🏆 **Best Model: Ridge Regression**

---

## 🚨 Overfitting Analysis

During experimentation, Random Forest achieved:

* Training R² Score = 0.952
* Testing R² Score = 0.576

This significant performance gap indicated overfitting, meaning the model learned the training data too well but failed to generalize to unseen data.

To address this issue:

* Multiple models were compared.
* Generalization performance was prioritized over training accuracy.
* Ridge Regression was selected as the final model because it achieved the highest test performance and demonstrated better stability.

---

## 📊 Evaluation Metrics

The following metrics were used:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

Final Ridge Regression Performance:

* R² Score: 0.744

---

## 📷 Visualizations

Project visualizations include:

* Correlation Heatmap
* Feature Importance Analysis
* Actual vs Predicted Plot
* Distribution Plots
* Boxplots
* Scatter Plots

---

## 📚 Key Learnings

* Data preprocessing and feature engineering significantly impact model performance.
* Model comparison is essential for selecting the best-performing algorithm.
* High training accuracy does not always indicate a good model.
* Understanding and handling overfitting is critical in machine learning projects.

---

## 🚀 Future Improvements

* Collect larger datasets for better generalization.
* Perform hyperparameter tuning.
* Experiment with advanced boosting algorithms such as XGBoost.
* Deploy the model using Streamlit or Flask.

---

## 👩‍💻 Author

Nayani

Machine Learning & Data Science Enthusiast

---

⭐ If you found this project useful, consider giving it a star!
