# House Price Prediction Using Regression Algorithms from Scratch

A machine learning project that implements multiple regression algorithms from scratch to predict housing prices using a synthetic real estate dataset. This project focuses on understanding the mathematical foundations of machine learning by building models without relying on Scikit-Learn's built-in regression implementations.

---

## 📖 Project Overview

This project analyzes a real estate dataset containing 10,000 properties and predicts housing prices using different regression techniques. The dataset includes several real-world challenges such as missing values, outliers, non-linear relationships, and multicollinearity, making it an excellent case study for applied machine learning.

The primary objective is to compare the performance of different regression models and understand their strengths, weaknesses, and practical applications in predictive analytics.

---

## 🎯 Objectives

- Implement Simple Linear Regression using Gradient Descent.
- Implement Multiple Linear Regression using Normal Equation and Gradient Descent.
- Apply Ridge (L2) and Lasso (L1) Regularization.
- Build Polynomial Regression models up to Degree 5.
- Perform Feature Engineering and Feature Selection.
- Handle missing values and outliers effectively.
- Compare model performance using statistical evaluation metrics.
- Analyze bias-variance trade-offs and model generalization.

---

## 📊 Dataset Features

The dataset contains the following features:

| Feature | Description |
|----------|-------------|
| Area | Living area in square feet |
| Bedrooms | Number of bedrooms |
| Bathrooms | Number of bathrooms |
| Age | Property age in years |
| Distance City | Distance from city center |
| Crime Rate | Local crime rate |
| School Rating | School district rating |
| Garage | Number of garage spaces |
| Basement | Basement area in square feet |
| Price | Target variable (House Price) |

### Dataset Challenges

- 5% Missing Values
- 2% Price Outliers
- Non-Linear Relationships
- Feature Multicollinearity

---

## 🚀 Implemented Models

### 1. Simple Linear Regression
- Gradient Descent Optimization
- Learning Rate Scheduling
- Convergence Criteria
- Cost Function Visualization
- Confidence Intervals
- Residual Analysis

### 2. Multiple Linear Regression
- Normal Equation Method
- Gradient Descent Implementation
- Ridge Regularization (L2)
- Lasso Regularization (L1)
- Feature Scaling
- Cross Validation

### 3. Polynomial Regression
- Polynomial Features (Degree 1–5)
- Validation Curves
- Learning Curves
- Early Stopping
- Bias-Variance Analysis

---

## ⚙️ Feature Engineering

The project includes:

- Missing Value Imputation
- Outlier Detection using IQR
- Feature Scaling and Normalization
- Interaction Features
- Forward Selection
- Backward Elimination
- Statistical Significance Testing
- Variance Inflation Factor (VIF) Analysis

---

## 📈 Model Evaluation Metrics

The following metrics are used to evaluate model performance:

- R² Score
- Adjusted R² Score
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- MAPE (Mean Absolute Percentage Error)
- Confidence Intervals
- Statistical Significance Tests

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib

> Note: Core machine learning algorithms are implemented from scratch without using Scikit-Learn's regression models.

---

## 📂 Project Structure

```text
House-Price-Prediction-From-Scratch/
│
├── data/
│   └── housing_dataset.csv
│
├── src/
│   ├── simple_linear_regression.py
│   ├── multiple_linear_regression.py
│   ├── polynomial_regression.py
│   ├── feature_engineering.py
│   └── evaluation_metrics.py
│
├── tests/
│   └── unit_tests.py
│
├── notebooks/
│   └── analysis.ipynb
│
├── plots/
│   └── visualizations/
│
├── requirements.txt
├── README.md
└── main.py
```

---

## 📌 Key Features

✅ Regression Algorithms Implemented From Scratch

✅ Data Cleaning and Preprocessing

✅ Missing Value Handling

✅ Outlier Detection and Removal

✅ Regularization Techniques

✅ Feature Selection Methods

✅ Cross Validation

✅ Learning Curves and Validation Curves

✅ Statistical Analysis

✅ Model Comparison and Evaluation

---

## 📉 Results

The project compares different regression techniques and identifies the most effective model for housing price prediction. Various visualizations such as regression plots, residual plots, validation curves, learning curves, and feature importance analyses are included to provide deeper insights into model performance.

The final model is selected based on predictive accuracy, generalization capability, and statistical significance.

---

## 🎓 Learning Outcomes

Through this project, the following concepts were explored:

- Machine Learning Fundamentals
- Optimization Techniques
- Gradient Descent
- Statistical Modeling
- Feature Engineering
- Model Evaluation
- Regularization
- Bias-Variance Tradeoff
- Cross Validation
- Predictive Analytics

---

## 👨‍💻 Author

**Ansh Salaria**

Bachelor in Information Technology (Application Development)

---

## 📜 License

This project is developed for educational and academic purposes.

---

⭐ If you found this project useful, consider giving it a star on GitHub.
