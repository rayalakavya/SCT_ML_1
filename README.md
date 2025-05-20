# SCT_ML_1
Linear Regression model to predict house prices (Skill Craft Task 1)
# 🏠 House Price Prediction - SkillCraft ML Track Task 1

This repository contains my submission for **Task 1** of the **SkillCraft Technology Machine Learning Track**. The task was to implement a **Linear Regression** model to predict house prices based on features like square footage, number of bedrooms, and bathrooms.

## 📁 Dataset
The dataset is from the [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) competition on Kaggle. It contains information such as:
- `GrLivArea`: Above ground living area (in square feet)
- `BedroomAbvGr`: Number of bedrooms
- `FullBath` & `HalfBath`: Number of bathrooms

## 📊 Features Used
- **GrLivArea**
- **BedroomAbvGr**
- **TotalBath** (calculated as `FullBath + 0.5 * HalfBath`)

## ⚙️ Libraries Used
- pandas
- matplotlib
- scikit-learn

## 🧠 Model
- **Linear Regression**
- Evaluated using **Mean Squared Error** and **R² Score**

## 📈 Results
- **R² Score**: ~0.63
- Mean Squared Error: ~2.85 Billion

## 📌 Improvements
The current model can be improved by including more infrastructure-related features such as:
- Neighborhood
- Proximity to transit
- Year built / renovation year

## 📷 Plot
The repository includes a visualization comparing actual vs predicted sale prices.

## ✅ How to Run
```bash
pip install -r requirements.txt
python house_price_model.py
