# Multiple Linear Regression – House Price Analysis

## 📌 Overview
This project uses **Multiple Linear Regression** to predict house prices using housing data from King County, Seattle.

## 🎯 Objectives
* Load and explore training, testing, and full datasets.
* Create new features using feature engineering.
* Build and compare 3 Linear Regression models.
* Analyze model coefficients and predictions.
* Evaluate models using **Mean Squared Error (MSE)**.

## 📂 Datasets
* `kc_house_train_data.csv`
* `kc_house_test_data.csv`
* `kc_house_data.csv`

## 🛠️ Libraries
* Pandas
* NumPy
* Scikit-Learn

## 🔧 Feature Engineering
Created features:
* `bedrooms_squared`
* `bed_bath_rooms`
* `log_sqft_living`
* `lat_plus_long`

## 🤖 Models
Three models were created using different combinations of the original and engineered features.

## 📊 Evaluation
Model performance is evaluated using **Mean Squared Error (MSE)** to measure prediction errors.
