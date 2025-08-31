# 🍽️ Food Demand Forecasting Project  

## 📌 Project Overview  
This project focuses on forecasting **weekly food demand** for a food delivery service.  
The main goal is to build a **predictive model** that helps the business optimize inventory, reduce wastage, and ensure timely supply based on customer demand patterns.  

The project leverages **machine learning (XGBoost)** to capture demand trends from historical data and generate accurate forecasts.  

---

## 🚀 Problem Statement  
Food delivery businesses often face challenges like:  
- Overstocking leading to wastage.  
- Understocking leading to lost sales and dissatisfied customers.  
- Inability to predict seasonal demand variations.  

A reliable **demand forecasting system** helps improve decision-making and profitability.  

---

## 🎯 Objectives  
- Forecast **weekly demand** at the product and center level.  
- Analyze factors influencing demand such as **center attributes, meal features, and historical demand**.  
- Build a robust ML model (XGBoost) for accurate predictions.  
- Provide business insights for inventory and supply chain optimization.  

---

## 🔎 Dataset  
The dataset consists of multiple files:  
- **train.csv** – Historical weekly demand for products.  
- **test.csv** – Data for which predictions need to be made.  
- **meal_info.csv** – Contains information about meal categories and cuisines.  
- **center_info.csv** – Contains attributes of centers (location, city tier, etc.).  

Key features include:  
- `id` → Unique ID  
- `week` → Week number  
- `center_id` → Distribution center identifier  
- `meal_id` → Meal identifier  
- `checkout_price` → Price of the meal  
- `num_orders` → Number of orders (target variable)  

---

## ⚙️ Methodology  
1. **Data Preprocessing**  
   - Handling missing values.  
   - Feature engineering (e.g., meal category, center tier, price ranges).  
   - Encoding categorical variables.  

2. **Exploratory Data Analysis (EDA)**  
   - Demand patterns over weeks.  
   - Distribution across centers and meal categories.  
   - Price vs demand correlation.  

3. **Modeling**  
   - Baseline models (Linear Regression, Decision Tree).  
   - Advanced model: **XGBoost Regressor** for demand forecasting.    

4. **Evaluation**  
   - Metrics: **RMSE (Root Mean Square Error)**, **MAE**.  
   - Comparison of model performances.  

---

## 💻 Tech Stack  
- **Programming**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost  
- **Platform**: Google Colab / Jupyter Notebook  

---

## 📊 Insights & Business Impact  
- Helps in **optimizing supply chain operations**.  
- Reduces **food wastage** by forecasting accurate demand.  
- Improves **customer satisfaction** with timely availability of meals.  
- Supports **strategic pricing decisions**.  

---

## ✅ Conclusion  
The **XGBoost-based forecasting model** proved effective in predicting weekly food demand with high accuracy.  
The solution can be deployed as part of a decision-support system for inventory planning and demand management in the food delivery industry.  

---

## 👨‍💻 Author  
**Aravind Udiyana**  
*Food Demand Forecasting Project*  
