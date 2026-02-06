# 🛡️ Sentinel-Finance: Credit Card Fraud Detection

### 📌 Problem Statement & Project Impact

* **The Problem: Market Information Asymmetry in Financial Transactions**
    In financial ecosystems, fraud represents a tiny fraction of total volume (less than 0.2%). This extreme imbalance creates an "Accuracy Paradox" where standard models fail to catch malicious activity while maintaining high accuracy scores. This lack of transparency leads to financial losses and decreases trust in digital payment systems.

* **The Solution: Machine Learning for Fair & Transparent Pricing**
    This project develops a Machine Learning solution that leverages a specialized dataset to identify key features impacting transaction security. By using a **Random Forest Classifier**, the model provides a transparent tool for distinguishing between legitimate behavior and fraudulent anomalies. This ensures security for both providers and users in the financial ecosystem.

---

### 📊 Dataset Overview
Due to file size limitations on GitHub, the dataset is not hosted in this repository. 
* **Source:** You can download the official dataset here: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
* **Size:** ~150 MB (284,807 transactions).
* **Feature Selection:** To optimize performance, I performed feature importance analysis and selected the **20 most impactful variables** 

---

### 🛠️ Technologies Used
* **Python** (Data Science Core)
* **Scikit-Learn** (Random Forest, RobustScaler, Precision-Recall Metrics)
* **Pandas & NumPy** (Data Cleaning and Transformation)
* **Matplotlib & Seaborn** (Statistical Visualization)
