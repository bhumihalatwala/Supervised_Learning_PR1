# 🏠 House Price Prediction Using Regression Models

## 📌 Project Overview

This project focuses on predicting house prices using various Regression and Optimization techniques in Machine Learning.

The complete workflow includes:

* Dataset understanding and preprocessing
* Simple Linear Regression
* Multiple Linear Regression
* Polynomial Regression
* Gradient Descent Optimization
* Bias-Variance Analysis
* Model Evaluation and Comparison

The objective is to identify the most effective model for predicting house prices and understand how model complexity impacts performance.

---

# 📊 Dataset Information

The housing dataset contains approximately **4200 records** with the following attributes:

| Feature              | Description               |
| -------------------- | ------------------------- |
| house_id             | Unique house identifier   |
| area_sqft            | House area in square feet |
| bedrooms             | Number of bedrooms        |
| bathrooms            | Number of bathrooms       |
| location_score       | Overall location rating   |
| age_years            | Age of property           |
| distance_city_km     | Distance from city center |
| lot_size_sqft        | Land area                 |
| has_garage           | Garage availability       |
| has_pool             | Pool availability         |
| renovation_years_ago | Years since renovation    |
| house_price_inr      | Target variable           |

---

# 🎯 Project Objectives

✔ Explore relationships between housing features and price

✔ Build regression models for house price prediction

✔ Evaluate model performance using standard metrics

✔ Study Gradient Descent optimization techniques

✔ Analyze Bias-Variance trade-offs

✔ Identify the most suitable model for business use

---

# 🛠 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn

---

# 🤖 Machine Learning Models Implemented

## 1️⃣ Simple Linear Regression

Uses only:

* Area (sqft)

to predict house prices.

---

## 2️⃣ Multiple Linear Regression

Uses all available features for prediction:

* Area
* Bedrooms
* Bathrooms
* Location Score
* Age
* Distance from City
* Lot Size
* Garage Availability
* Pool Availability
* Renovation Information

---

## 3️⃣ Polynomial Regression

Introduces polynomial terms to capture non-linear relationships between features and target values.

It is a extension of simple linear regression and uses only 1 fetaure i.e. Area (sqft)

Degree Used:

* Degree 3

---

# 📈 Evaluation Metrics

The following metrics were used to evaluate model performance:

### Mean Squared Error (MSE)

Measures average squared prediction error.

### Mean Absolute Error (MAE)

Measures average absolute prediction error.

### Root Mean Squared Error (RMSE)

Provides prediction error in original units.

### R² Score

Measures the proportion of variance explained by the model.

### Adjusted R² Score

Accounts for the number of predictors used.

---

# 🧠 Gradient Descent Optimization

The project implements and compares:

### Batch Gradient Descent (BGD)

Uses the entire dataset for parameter updates.

### Stochastic Gradient Descent (SGD)

Updates parameters using one training sample at a time.

### Mini-Batch Gradient Descent

Updates parameters using small batches of data.

---

# 📊 Model Performance Summary

| Model                      | R² Score |
| -------------------------- | -------- |
| Simple Linear Regression   | 0.5625   |
| Multiple Linear Regression | 0.9178   |
| Polynomial Regression      | 0.5629   |

### 🏆 Best Model

**Multiple Linear Regression**

Reason:

* Highest R² Score
* Lowest prediction error
* Best balance between bias and variance
* Utilizes all relevant housing features

---

# 📉 Bias-Variance Analysis

### Simple Linear Regression

* High Bias
* Low Variance
* Underfits complex relationships

### Polynomial Regression

* Increased complexity
* Slight reduction in bias
* No significant performance improvement

### Multiple Linear Regression

* Balanced Bias and Variance
* Best overall generalization

---

# 📊 Visualizations Included

* Feature vs Target Scatter Plots
* Correlation Heatmap
* Simple Linear Regression Plot
* Residual Analysis
* Residual Distribution
* Linear vs Polynomial Comparison
* Bias-Variance Analysis Charts
* Model Performance Comparison

---

# 🔍 Key Findings

* House price depends on multiple factors rather than area alone.
* Multiple Linear Regression significantly outperformed Simple Linear Regression.
* Polynomial Regression provided only marginal improvement over Simple Linear Regression.
* Batch Gradient Descent achieved the lowest cost value.
* No major overfitting was observed in the implemented models.

---

# 📁 Project Structure

```text
House-Price-Prediction/
│
├── housing_dataset.csv
├── House_Price_Prediction.ipynb
├── Theory_Concepts.pdf
├── README.md
│
└── Generated Visualizations
```

---

# ✅ Conclusion

This project demonstrates the complete workflow of supervised machine learning for house price prediction.

After comparing multiple regression techniques and optimization methods, **Multiple Linear Regression emerged as the most effective model**, achieving an R² Score of **0.9178** and providing the most reliable predictions for real-world housing valuation scenarios.
