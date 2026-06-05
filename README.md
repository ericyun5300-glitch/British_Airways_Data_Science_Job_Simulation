# British Airways Data Science Job Simulation

This repository contains my data engineering and predictive modeling pipeline completed during the British Airways Virtual Internship on Forage. 

## 🚀 Project Overview
The objective of this project is to analyze customer booking data and build a high-performance machine learning model to predict whether a customer will complete a flight booking (`booking_complete`).

## 🛠️ Tech Stack & Methods
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn (RandomForestClassifier), Matplotlib, Seaborn
* **Validation:** 5-Fold Cross-Validation to ensure robust generalization performance.
* **Feature Engineering:** Implemented One-Hot Encoding via `pd.get_dummies` to properly handle categorical variables.

## 📈 Key Workflow & Insights
1. **Data Validation:** Evaluated dataset structure and confirmed zero missing values using `df.isnull().sum()`.
2. **Model Training:** Trained a RandomForest baseline model on an 80/20 train/test split, achieving a stable baseline accuracy.
3. **Cross-Validation:** Verified model stability and mitigated sampling bias using `cross_val_score`.
4. **Feature Importance:** Extracted top-performing drivers predicting customer conversions to deliver actionable business insights.
