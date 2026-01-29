# 🏠 House Price Prediction using Linear Regression

This project implements a machine learning regression model to predict house prices based on various housing features such as area, number of bedrooms, stories, and furnishing status.  
The model is trained using Linear Regression and evaluated using the R² score.

---

## 📌 Problem Statement
Predicting house prices is a common real-world problem in the real estate domain.  
The aim of this project is to build a baseline regression model that can estimate house prices from structured housing data.

---

## 🧠 Machine Learning Model
- Problem Type: Regression
- Algorithm Used: Linear Regression
- Evaluation Metric: R² Score

---

## 📂 Dataset
- File Name: Housing.csv
- Target Variable: price

### Features Used:
- area  
- bedrooms  
- bathrooms  
- stories  
- guestroom  
- basement  
- parking  
- furnishingstatus  

Categorical features were converted into numerical format using Label Encoding.

---

## ⚙️ Project Workflow
1. Importing required libraries  
2. Loading the dataset  
3. Data cleaning and preprocessing  
4. Label encoding categorical variables  
5. Exploratory Data Analysis (EDA)  
6. Train-test split  
7. Model training using Linear Regression  
8. Model evaluation using R² score  

---

## 📊 Model Performance
- R² Score: 0.67  

The model explains approximately 67% of the variance in house prices.  
This serves as a strong baseline model with scope for further improvements.

---

## 📈 Exploratory Data Analysis
- Relationship between area and price  
- Effect of bedrooms and stories on house price  
- Visualized using Seaborn

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

