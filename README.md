# 🛡️ Sentinel-Finance: Credit Card Fraud Detection

### 📌 Problem Statement & Project Impact

* **The Problem: Market Information Asymmetry in Financial Transactions**
    In the secondary vehicle market and financial transactions, fraud represents a tiny fraction of total volume (less than 0.2%). This extreme imbalance creates an "Accuracy Paradox" where standard models fail to catch malicious activity while maintaining high accuracy scores. This lack of transparency leads to financial losses and decreases trust in digital payment systems.

* **The Solution: Machine Learning for Fair & Transparent Pricing**
    This project develops a Machine Learning solution that leverages a specialized dataset to identify key features impacting transaction security. By using a **Random Forest Classifier**, the model provides a transparent tool for distinguishing between legitimate behavior and fraudulent anomalies. This ensures fair pricing and security for both buyers and sellers in the financial ecosystem.

---

### 📊 Dataset Overview
The dataset contains 284,807 transactions with the following features:
* **V1-V28:** PCA-transformed behavioral features (top 20 selected for this model).
* **V17, V14, V12, V10:** The most significant predictors identified during analysis.
* **Amount:** The transaction value.
* **Class:** Target variable (0 for Legitimate, 1 for Fraud).

---

### 🛠️ Technologies Used
* **Python** (Data Science Core)
* **Scikit-Learn** (IsolationForest,Random Forest, RobustScaler, Precision-Recall Metrics)
* **Pandas & NumPy** (Data Cleaning and Transformation)
* **Matplotlib & Seaborn** (Statistical Visualization)
