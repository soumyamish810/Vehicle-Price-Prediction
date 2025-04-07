# 🚗 Vehicle Price Prediction using Machine Learning

## 📌 Overview
This project aims to build a machine learning model to predict the **selling price of vehicles** based on various features such as manufacturing year, mileage, fuel type, transmission, and brand. The goal is to assist buyers, sellers, and dealerships in making informed decisions with accurate price estimations.

---

## 📊 Problem Statement
In the rapidly growing automobile market, estimating the fair price of a vehicle is essential. Due to numerous influencing factors, price estimation can be challenging and subjective. This project solves that problem by applying data-driven techniques to build a predictive model.

---

## 🔍 Dataset
- The dataset contains information on used cars including:
  - **Year**, **Present Price**, **Kms Driven**
  - **Fuel Type**, **Seller Type**, **Transmission**
  - **Owner**, **Selling Price**, etc.
- Make sure `dataset.csv` is placed in the root directory before running the notebook.

---

## 🧠 Tools & Libraries
- **Python** (pandas, numpy, matplotlib, seaborn)
- **scikit-learn** (RandomForestRegressor, Pipeline, GridSearchCV)
- **Jupyter Notebook** for code execution and visualization

---

## ⚙️ Model Workflow
1. **Data Loading & Exploration**
2. **Data Preprocessing**
   - Handling categorical variables
   - Feature selection
3. **Model Building**
   - Random Forest Regressor
   - Pipeline & GridSearchCV for tuning
4. **Evaluation Metrics**
   - MAE, RMSE, R² Score
   - Scatter plot: Actual vs Predicted
   - Feature importance plot

---

## 📈 Results
- Achieved strong model performance with Random Forest.
- Top influencing factors identified using feature importance visualization.
- Helpful visual insights through EDA and evaluation plots.

---

## 🖼️ Visualizations
- **Actual vs Predicted Scatter Plot**
- **Top 15 Feature Importances**

