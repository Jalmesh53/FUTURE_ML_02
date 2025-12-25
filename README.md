# 📉 Customer Churn Prediction System (Task 2)

## 📌 Project Overview

This project is part of the **Future Interns Machine Learning Internship**. The goal was to build a machine learning model to predict whether a customer will stop using a service (churn) based on their usage behavior and demographics.

By analyzing customer data, this system identifies high-risk customers, allowing businesses to take proactive measures to retain them.

## 🛠️ Tech Stack

- **Python**: Core programming language.
- **Pandas & NumPy**: Data cleaning and manipulation.
- **XGBoost**: High-performance gradient boosting classifier for prediction.
- **Scikit-learn**: For label encoding, data splitting, and evaluation metrics.
- **Seaborn/Matplotlib**: Feature importance and confusion matrix visualizations.
- **Power BI**: Interactive dashboard for business insights.

## 📊 Key Features

- **Data Preprocessing**: Handled missing values (`TotalCharges`) and encoded categorical variables (e.g., Contract Type, Payment Method).
- **Predictive Modeling**: Trained an **XGBoost Classifier** to predict churn probability.
- **Evaluation**: Achieved high accuracy and analyzed performance using a Confusion Matrix.
- **Insights Dashboard**: Built a Power BI dashboard to visualize churn rates by demographic and service type.

## 🔍 Key Insights

- **Top Factor for Churn:** _[Contract Type / Monthly Charges]_ was identified as the strongest predictor of whether a customer leaves.
- **High-Risk Segment:** Customers with _[Month-to-Month]_ contracts and _[Fiber Optic]_ internet service showed the highest churn rates.

## 📂 Project Structure

- `churn_model.ipynb`: The complete Python script (Data Loading -> Modeling -> Evaluation).
- `churn_data.csv`: The cleaned dataset used for training.
- `churn_predictions.csv`: The final output file containing actual vs. predicted values and churn probabilities.
- `Churn_Dashboard.pbix`: The Power BI file visualizing the results.

## 🚀 How to Run

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```
