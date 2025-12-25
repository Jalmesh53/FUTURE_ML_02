# 📉 Customer Churn Prediction System (Task 2)

## 📌 Project Overview

This project is part of the **Future Interns Machine Learning Internship (Task 2)**.  
The objective is to build a **machine learning model** that predicts whether a customer is likely to stop using a service (churn) based on their usage behavior and demographics.

By analyzing customer data, the system identifies **high-risk customers**, enabling businesses to take **proactive retention measures**.

---

## 🛠️ Tech Stack

- **Python** – Core programming language
- **Pandas & NumPy** – Data cleaning and manipulation
- **XGBoost** – Gradient boosting classifier for churn prediction
- **Scikit-learn** – Data preprocessing, model evaluation, and metrics
- **Seaborn / Matplotlib** – Visualizations (confusion matrix, feature importance)
- **Power BI** – Interactive dashboard for business insights

---

## 📊 Key Features

- **Data Preprocessing**:

  - Handled missing values (e.g., `TotalCharges`)
  - Encoded categorical variables (Contract Type, Payment Method, etc.)

- **Predictive Modeling**:

  - Trained an **XGBoost Classifier** to predict customer churn probability

- **Model Evaluation**:

  - Accuracy analysis and performance evaluation using a **Confusion Matrix**

- **Visualization & Insights**:
  - Power BI dashboard showing churn trends by demographics and service type

---

## 🔍 Key Insights

- **Top Churn Driver**: Contract type and monthly charges strongly influence churn behavior
- **High-Risk Segment**: Customers with **month-to-month contracts** and **fiber optic internet** show higher churn rates

---

## 📂 Project Structure

- `churn_model.ipynb` – Complete ML workflow (data loading → training → evaluation)
- `churn_data.csv` – Cleaned dataset used for training
- `churn_predictions.csv` – Model predictions with churn probabilities
- `Churn_Dashboard.pbix` – Power BI dashboard file

---

## 🚀 How to Run

Install required dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```
