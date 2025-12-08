# 🚘 OBD (On-Board Diagnostics) Machine Learning Project

## 📖 What is OBD?
**OBD (On-Board Diagnostics)** is a built-in system in modern vehicles that continuously monitors data from sensors across various components like the **engine**, **fuel system**, and **emission controls**.  
It provides real-time data and **Diagnostic Trouble Codes (DTCs)** that help detect and identify issues in vehicle performance.

In this project, we leverage **OBD sensor data** to perform **data-driven vehicle health prediction** using **Machine Learning models**.  
By analyzing key OBD parameters, our models can estimate overall **vehicle condition**, detect potential anomalies, and predict maintenance needs.

---

## 📊 Project Overview
This project demonstrates how **machine learning regression techniques** can be applied to **OBD vehicle data** to predict vehicle health and performance trends.  
We go through data cleaning, feature engineering, model building, optimization, and comparison to identify the best model for accurate predictions.

---

## 🧠 Key Objectives
- Import and clean OBD data  
- Perform **Exploratory Data Analysis (EDA)** and **visualization**  
- Handle missing values and outliers  
- Build **Linear Regression** and **Polynomial Regression** models  
- Apply **Regularization (Ridge, Lasso, Elastic Net)** for optimization  
- Predict **vehicle health status** using regression models  
- Compare models **before and after feature engineering**

---

## ⚙️ Project Workflow

### 1. Data Import & Cleaning
- Load raw OBD dataset  
- Check for null values and duplicates  
- Remove or impute missing data  
- Clean irrelevant records  

### 2. Exploratory Data Analysis (EDA)
- Visualize feature distributions and relationships  
- Analyze correlations among OBD parameters  
- Identify patterns linked to vehicle performance and health  

### 3. Data Preprocessing
- Handle missing values  
- Detect and remove outliers  
- Normalize and scale numerical data  

### 4. Model Development
Implemented models for predictive analysis:
- **Linear Regression**  
- **Polynomial Regression**

### 5. Model Optimization (Regularization)
Applied regularization to avoid overfitting and improve generalization:
- **Ridge Regression**  
- **Lasso Regression**  
- **Elastic Net**

### 6. Model Evaluation
Evaluated model performance using:
- **Mean Squared Error (MSE)**  
- **R² Score**  
- Visualization of predicted vs actual vehicle health metrics  

### 7. Feature Engineering & Re-Evaluation
- Added derived and interaction features  
- Retrained models with new features  
- Compared results **before and after feature engineering**  
- Improved vehicle health prediction accuracy  

---

## 📈 Results & Insights
- Regularized models (especially **Ridge** and **Elastic Net**) provided better generalization.  
- Feature engineering significantly boosted vehicle health prediction accuracy.  
- Machine Learning proved effective in modeling OBD data for **predictive vehicle diagnostics**.  
- Demonstrated how regression models can forecast **vehicle health status** and potential maintenance requirements.

---

## 🧰 Technologies Used
| Category | Tools & Libraries |
|-----------|------------------|
| Programming | Python |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Environment | Google Colab / Jupyter Notebook |

---

## 🚀 Future Enhancements
- Integrate **live OBD-II sensor data** using devices like ELM327  
- Build a **real-time dashboard** for vehicle health monitoring  
- Use **deep learning** for more accurate predictions  
- Implement **fault detection and preventive maintenance alerts**

---
## 📂 Dataset Information
- **Dataset Source:** [Kaggle - OBD-II Dataset (obdii-ds3)](https://www.kaggle.com/datasets/cephasax/obdii-ds3)  
- After downloading the dataset as a **ZIP file**, you will find **3 CSV files** inside.  
- For this project, we use the file: **`exp1_14drivers_14cars_dailyRoutes.csv`**.  
- This file contains OBD sensor readings, vehicle details, and time-based features for multiple drivers and cars.
---
---
---
