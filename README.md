# 📊 Digital Marketing Campaign Conversion Prediction

## 🔍 Project Overview

This project aims to predict whether a customer will convert (respond to a marketing campaign) based on demographic and engagement data. The goal is to help businesses improve targeting, increase conversion rates, and optimize marketing spend.

## 🎯 Objective

* Predict customer conversion using machine learning
* Identify key factors influencing conversions
* Support data-driven marketing decisions

## 📁 Dataset Features

* Age
* Income
* Gender
* Website Visits
* Email Opens
* Email Clicks
* Social Shares
* Previous Purchases


## ⚙️ Technologies Used

* Python (Pandas, NumPy, Scikit-learn)
* XGBoost
* Power BI
* Matplotlib & Seaborn


## 🔄 Project Workflow

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Training & Evaluation
5. Model Selection (Best: XGBoost)
6. Dashboard Visualization
7. Model Saving using Pickle


## 🤖 Models Implemented

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost (Best Performer)


## 📈 Results

* XGBoost achieved the best performance
* F1-score: **96%**
* High recall indicating strong ability to identify potential converters


## 📊 Dashboard Insights

* Higher website visits increase conversion probability
* Email clicks are stronger indicators than email opens
* Social sharing positively impacts conversions


## 💾 Model Deployment

The trained model is saved as `model.pkl` using Pickle, allowing reuse without retraining.


## 🚀 How to Run

1. Clone the repository
2. Open Jupyter Notebook
3. Run all cells
4. Load model using pickle if needed


## 👩‍💻 Author
Sakshi Davkhar
