# Customer Churn Prediction & Machine Learning Pipeline

An end-to-end enterprise data analytics and machine learning architecture built to predict customer drop-off risk using advanced ensemble methods.

## 📊 Project Overview
This project simulates an industrial customer analytics environment with a dataset of 10,000 consumer accounts. It tracks user behavior, customer service tickets, and purchasing habits to flag accounts that are highly likely to cancel their subscriptions.

## 🛠️ Tech Stack & Skills Demonstrated
* **Languages & Frameworks:** Python, Scikit-Learn, Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Data Engineering:** Automated pipelines, Median Imputation for missing values, Outlier capping via Interquartile Range (IQR)
* **Feature Engineering:** Customer Lifetime Value (CLV) tracking, Daily Purchase Velocity analysis
* **Machine Learning Model:** Gradient Boosting Classifier

## 📈 Key Results & Performance
* **Overall Accuracy:** 98%
* **ROC-AUC Score:** 0.9896 (Excellent predictive discrimination)
* **Key Insight:** Data visualization proved that customer churn risk spikes exponentially once an account crosses 5 or more open support tickets, providing a clear marker for proactive customer success interventions.

## 📁 Repository Structure
* `chrun_analysis.ipynb`: The main Jupyter Notebook containing the clean data pipelines, exploratory plots, and model training logic.
