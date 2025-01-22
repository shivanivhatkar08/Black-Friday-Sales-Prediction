# Black Friday Sales Prediction

## 🛒 Project Overview
This project uses machine learning models to predict customer purchase amounts during Black Friday sales based on historical sales data. The goal is to uncover insights into customer spending behavior and provide accurate sales predictions to optimize revenue and marketing strategies.

## 🧰 Features
- Analyze customer demographics (e.g., Age, Gender, City Category).
- Predicting purchase amounts using 3 machine learning models.
- Evaluating and comparing model performance.
- Identifying key factors influencing customer spending behavior.
- Feature engineering for advanced insights (e.g., Average Purchase, Product Popularity).

## 📊 Dataset
- **Source**: [Walmart Sales Dataset on Kaggle](https://www.kaggle.com/datasets/devarajv88/walmart-sales-dataset)
- **Contents**:
  - Customer demographics (Age, Gender, Occupation).
  - Product details (Product_ID, Product_Category).
  - Purchase amounts.

## ⚙️ Tools & Technologies
- **Programming Language**: Python
- **Libraries**:
  - Data Analysis: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `sklearn`, `xgboost`

## 🧑‍💻 Models Used
1. **Linear Regression**:
   - Baseline model for understanding basic patterns in the data.
2. **Random Forest Regressor**:
   - Captures non-linear relationships and improves accuracy.
3. **XGBoost**:
   - Advanced gradient boosting model for high accuracy.

### **Model Results Achieved**
| Model              | Mean Absolute Error (MAE) | R² Score |
|---------------------|---------------------------|----------|
| Linear Regression   | 0.0877                   | 0.7392   |
| Random Forest       | 0.0857                   | 0.7469   |
| XGBoost             | 0.0840                   | 0.7525   |

## 🔑 Key Insights
- **Top Features**:
  - Product Popularity and Average Spent Per Product are the most significant predictors of purchase behavior.
- **Customer Segmentation**:
  - High-value customers and top-selling products were identified for targeted marketing.

## 🚀 How to Use This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/shivanivhatkar08/black-friday-sales-prediction.git
   cd black-friday-sales-prediction
