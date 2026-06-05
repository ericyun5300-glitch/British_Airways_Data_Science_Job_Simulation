**British Airways Job Simulation**
This repository contains my professional solutions for the British Airways Job Simulation hosted on Forage. The project demonstrates end-to-end data processing, quantitative analysis, and predictive machine learning.

**🚀 Project Components**
Task 1 (Operational Analysis): Analyzing airport lounge operations and passenger eligibility using structured grouping and quantitative metrics.
Task 2 (Predictive Modeling): Designing a machine learning pipeline to predict customer booking conversions.

**🛠️ Tech Stack & Tools**
Data & Business Analytics: Python (Pandas), Microsoft Excel (Quantitative Analysis)
Machine Learning: Python, Scikit-learn (RandomForestClassifier)

**📈 Key Workflow & Implementation Details**

**Part 1: Operational Lounge Analysis & Customer Grouping (Task 1)**

Data Categorization: Grouped operational flight data into distinct regional categories:

Group A: Europe
Group B: North America
Group C: Asia and Middle East

Total Capacity Analysis: Calculated total passenger volume for each regional group by aggregating seat configurations (First, Business, and Economy Class).

Lounge Eligibility Assessment: Evaluated lounge accessibility by analyzing passenger distribution across loyalty tiers (TIER1, TIER2, TIER3) for each regional group.

Operational Insights: Synthesized metrics to assess lounge eligibility and demand, providing recommendations for optimized resource allocation based on regional passenger segments.

**Part 2: Predictive Modeling of Booking Behavior (Task 2)**

Data Preprocessing: Handled data encoding using pd.get_dummies to transform categorical variables into a machine-readable format.

Feature Engineering: Identified and prioritized features including purchase_lead, flight_hour, and length_of_stay to enhance model predictive power.

Model Training: Implemented a RandomForestClassifier baseline model with an 80/20 data split.

Model Evaluation: Achieved a 73% accuracy rate, verified through 5-Fold Cross-Validation (cross_val_score) to ensure robust generalization.

Explainable AI (XAI): Extracted feature_importances_ to visualize the top 3 drivers (Purchase Lead, Flight Hour, Length of Stay) impacting booking outcomes.
