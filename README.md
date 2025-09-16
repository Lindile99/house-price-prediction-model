# 🏠 house price prediction model

This project applies a **multiple linear regression model** to predict the sales prices based on features like above-ground living area and garage area

---
## 🔑 Objective

The objective of this project is to analyze the relationship between house features and sale prices, and to build a multiple linear regression model that predicts house prices based on above-ground living area (Gr_Liv_Area) and garage area (Garage_Area).

---

## Dataset
- Source: [Kaggle – Ames Housing Dataset(https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset)

---

## 🔧Tools and Technologies
-**Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)  
- **Jupyter Notebook** for analysis and visualization  
-**Evaluations:** MSE, RMSE
---

## 🔍 Key Steps
1. **Data Cleaning** – handled missing values and outliers.  
2. **Exploratory Data Analysis (EDA)** – identified key features affecting housing prices.  
3. **Modeling** – applied multiple linear regression with predictors such as:
   - Gr_Liv_Area`l (above ground living area)  
   - Garage_Area (garage size)  
4. **Model Evaluation** – assessed accuracy using MSE, RMSE and residual analysis.  
---
## 📊 Insights
- Strong positive correlation between Gr_Liv_Area and house price.  
- Garage size also showed moderate influence on pricing.  
- Regression line fits the trend well but revealed a few outliers.  

--- 

## ✅️Results
-The model achieved **reasonable accuracy** with interpretable coefficients.  
- Demonstrates how linear regression can be used in real estate pricing strategies.  
---

## 📌 Next Steps
- Add more features (e.g., location, year built).  
- Compare linear regression with other models (Random Forest, Gradient Boosting).

---

## 📁 Repository Structure
Images/         #Visualizations

ames.csv        #Raw data

README.md       # Project description

house-price-prediction.ipynb #Full analysis notebook





