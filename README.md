# ML_Projects

---

# Fraud Detection Model

## 📌 Project Overview

This project aims to **predict fraudulent financial transactions** using machine learning techniques.
The dataset contains **6,362,620 transactions** with 10 features, including transaction amount, balances, and fraud labels.
The work involves **data cleaning, feature engineering, model building, and insights extraction** to support proactive fraud prevention.

## 📂 Dataset

* **Rows:** 6,362,620
* **Columns:** 10 (including `amount`, `oldbalanceOrg`, `newbalanceOrig`, `oldbalanceDest`, `newbalanceDest`, and `isFraud`)
* **Source:** Provided CSV file
* **Target Variable:** `isFraud` (0 = Non-Fraud, 1 = Fraud)

## 🛠️ Steps Performed

1. **Data Cleaning**

   * Checked for missing values
   * Identified and treated outliers
   * Handled anomalies in balances
2. **Exploratory Data Analysis (EDA)**

   * Transaction amount distribution
   * Fraud patterns by amount
   * Correlation heatmap
3. **Feature Engineering**

   * Balance difference features
   * Removal of highly correlated variables
4. **Model Development**

   * Selected suitable ML algorithms (Random Forest / XGBoost / etc.)
   * Feature selection based on importance & domain logic
5. **Model Evaluation**

   * Metrics: Precision, Recall, ROC-AUC, Confusion Matrix
6. **Business Insights & Recommendations**

   * Key factors influencing fraud
   * Suggested prevention strategies
   * Post-implementation monitoring plan

## 📊 Key Insights

* Fraud tends to occur with **higher transaction amounts** than normal transactions.
* Certain balance anomalies strongly correlate with fraud.
* Destination account patterns are important fraud indicators.

## 🚀 How to Run

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
2. Open the notebook:

   ```bash
   jupyter notebook Fraud_Detection.ipynb
   ```
3. Run all cells in sequence.

## 📈 Deliverables

* Jupyter Notebook with analysis & model
* Visualizations showing fraud patterns
* Actionable recommendations for fraud prevention

---
 
