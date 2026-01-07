# -House_Price_Prediction-
Housing price dataset with features like area, bedrooms, bathrooms, amenities and furnishing status. Clean CSV for EDA, visualization, and ML regression to predict home prices and study value drivers.
# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project is divided into two parts:

- **Project 1:** Implemented a baseline **Linear Regression** model to understand the basic machine learning workflow.
- **Project 2:** Implemented an advanced **Random Forest Regressor** to improve prediction performance and compare results.

The goal is to predict **house prices** based on features such as area, bedrooms, bathrooms, furnishing status, parking, and more.

---

## 🛠️ Tools & Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- GitHub

---

## 📂 Project Structure


---

## 🔄 Machine Learning Workflow

1. Data Loading
2. Data Cleaning & Preprocessing
3. Feature Engineering
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Model Comparison
8. Visualization & Interpretation

---

## 📊 Model Performance Comparison

| Model             | RMSE        | R² Score |
|-------------------|-------------|-----------|
| Linear Regression | (Your value) | (Your value) |
| Random Forest     | (Your value) | (Your value) |

> 📌 Random Forest achieved **better accuracy and lower error** compared to Linear Regression.

---

## 📈 Visual Results

### 🔹 Linear Regression: Actual vs Predicted
![Linear Regression](model_images/linear_regression_actual_vs_predicted.png)

### 🔹 Random Forest: Actual vs Predicted
![Random Forest](model_images/random_forest_actual_vs_predicted.png)

---

### 🔹 Linear Regression Residuals
![LR Residuals](model_images/linear_regression_residuals.png)

### 🔹 Random Forest Residuals
![RF Residuals](model_images/random_forest_residuals.png)

---

### 🔹 RMSE Comparison
![RMSE](model_images/rmse_comparison.png)

### 🔹 R² Score Comparison
![R2](model_images/r2_comparison.png)

---

### 🔹 Feature Importance (Random Forest)
![Feature Importance](model_images/feature_importance_random_forest.png)

---

## 🧠 Interpretation & Insights

- **Random Forest performed better** than Linear Regression.
- It achieved **higher R² score** and **lower RMSE**.
- This is because Random Forest can:
  - Capture **non-linear relationships**
  - Learn **feature interactions**
  - Reduce overfitting by averaging many trees

---

## ⚖️ Trade-offs

| Linear Regression | Random Forest |
|------------------|---------------|
| Simple & fast | Slower & complex |
| Easy to interpret | Hard to interpret |
| Less accurate | More accurate |

---

## 📝 Reflection

### 1. What changes did you observe using a stronger model?
- Accuracy improved significantly when using Random Forest.

### 2. What was the most challenging part?
- Data preprocessing and feature encoding.

### 3. How many hours did you spend?
- Approximately 6–10 hours.

---

## ✅ Final Conclusion

> The **Random Forest Regressor** is the best model for this dataset because it provides more accurate and reliable predictions than Linear Regression.

---

## 🚀 Author

Project by: **Tharun**
