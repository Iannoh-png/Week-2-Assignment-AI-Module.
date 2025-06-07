# Week-2-Assignment-AI-Module
# 🌍 Sustainable Energy Access Prediction

This project applies machine learning techniques to predict **Access to Electricity (% of population)** using structured data on sustainable energy and socioeconomic factors. It supports **Sustainable Development Goal 7 (Affordable and Clean Energy)** by leveraging data-driven insights to highlight key drivers of electricity access globally.

---

## 📊 Dataset

The dataset, `sustainable energy.csv`, contains global indicators such as:

- Population density  
- Renewable energy consumption  
- Socio-environmental metrics  

### Preprocessing Steps:

- Dropped irrelevant columns (e.g., Entity, Latitude, Longitude)
- Cleaned column names (removed newline characters)
- Converted formatted numeric fields to proper float format
- Removed rows with missing target values
- Imputed remaining missing values with the median

---

## 🧠 Model Overview

A **Gradient Boosting Regressor** from Scikit-learn was trained to predict the target variable — `Access to electricity (% of population)` — based on other input features.

### ML Workflow:

1. **Data Cleaning & Feature Engineering**
2. **Train-Test Split**
3. **Model Training with GradientBoostingRegressor**
   - `n_estimators=100`
   - `max_depth=3`
   - `random_state=42`
4. **Prediction & Evaluation**
5. **Feature Importance Visualization**

---

## 📈 Evaluation Metrics

- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

These metrics assess how accurately the model can predict electricity access levels.

---

## 🔍 Feature Importance

Top 15 most influential features are visualized using Seaborn bar plots to interpret which factors most significantly affect electricity access.

---

## 🛠️ Tools & Technologies

- Python 3.x
- Google Colab
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Scikit-learn](https://scikit-learn.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

---

## 🎯 Project Objective

This assignment contributes to understanding global energy disparities and aims to:

- Provide predictive insights into electricity access
- Inform policy decisions and infrastructure planning
- Align with **SDG 7: Affordable and Clean Energy**

---

