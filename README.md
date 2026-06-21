# Fraud Transaction Detection Using Machine Learning

## Project Overview

This project focuses on detecting fraudulent financial transactions using advanced Machine Learning techniques. The objective is to identify suspicious activities in transaction data, reduce financial risks, and support secure digital payment systems through predictive analytics.

## Key Contributions

### Data Quality & Preprocessing

* Improved data quality by handling missing values and inconsistencies.
* Applied the **Interquartile Range (IQR)** method to identify and cap outliers.
* Addressed multicollinearity among features using the **Variance Inflation Factor (VIF)** technique.
* Performed feature engineering to improve model performance and interpretability.

### Machine Learning Methodology

* Developed a fraud detection pipeline using supervised machine learning.
* Resolved class imbalance issues using **SMOTE (Synthetic Minority Over-sampling Technique)**.
* Trained and evaluated multiple classification models:

  * Logistic Regression
  * Random Forest
  * XGBoost
  * LightGBM
* Compared models using key evaluation metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
* **LightGBM achieved the best overall performance** for fraud detection.

### Fraud Analysis & Insights

* Identified the most influential fraud indicators:

  * Transaction Type (**TRANSFER**, **CASH_OUT**)
  * Large balance discrepancies (**diff_balance_org**)
  * Unusual transaction amounts
* Analyzed fraud patterns and behavioral characteristics of fraudulent transactions.

### Strategic Fraud Prevention Framework

Proposed a practical fraud prevention strategy including:

* Real-time transaction monitoring
* Risk-based fraud scoring
* Tiered alerting and notification system
* Infrastructure improvements for fraud detection
* Continuous model monitoring and retraining
* Performance measurement framework using fraud detection KPIs

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* LightGBM
* XGBoost
* Matplotlib
* Seaborn
* SMOTE (Imbalanced-Learn)
* Jupyter Notebook

## Results

* Successfully improved fraud detection performance through data preprocessing and class balancing.
* LightGBM emerged as the top-performing model.
* Generated actionable insights that can help financial institutions strengthen fraud prevention mechanisms.

## Learning Outcomes

* Data Cleaning & Preprocessing
* Feature Engineering
* Class Imbalance Handling
* Fraud Analytics
* Machine Learning Classification
* Model Evaluation & Optimization
* Financial Risk Analysis

## Conclusion

This project demonstrates how Machine Learning and Data Science can be leveraged to detect fraudulent financial transactions effectively. By combining robust preprocessing techniques, class balancing methods, and advanced ensemble models such as LightGBM, the solution provides accurate fraud detection and practical recommendations for real-world financial security systems.
