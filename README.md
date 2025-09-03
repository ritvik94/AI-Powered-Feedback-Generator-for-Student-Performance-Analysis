# 🏦 Bank Customer Churn Prediction using XGBoost

This project predicts **customer churn** (whether a bank customer will leave or not) using the **XGBoost classifier**.  
The dataset used is `Churn_Modelling.csv`, and the workflow includes **data preprocessing, feature analysis, model training, evaluation, and visualization**.

---

## 📌 Features
- Data cleaning (handling nulls, duplicates, outliers)
- Exploratory Data Analysis (EDA)
  - Correlation heatmaps
  - Distribution plots
  - Outlier detection using IQR
- Model Training
  - XGBoost Classifier with **class imbalance handling** (`scale_pos_weight`)
- Model Evaluation
  - Accuracy & Balanced Accuracy
  - ROC-AUC score & curve
  - Confusion Matrix
- Feature Importance Visualization

---

## 📂 Project Structure

---

## ⚙️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bank-customer-churn-xgboost.git
   cd bank-customer-churn-xgboost
pip install -r requirements.txt
pandas
numpy
scikit-learn
xgboost
seaborn
matplotlib
python bank_customer_churn_prediction_using_xgboost.py


## 📊 Results & Metrics

- Balanced Accuracy: Handles imbalance better than normal accuracy
- ROC-AUC Curve: Evaluates model discrimination ability
- Confusion Matrix: Shows misclassifications
- Feature Importances: Identifies top churn drivers

- Example plots:

  - ROC Curve for churn prediction
  - Accuracy vs Balanced Accuracy
  - Top drivers of churn
