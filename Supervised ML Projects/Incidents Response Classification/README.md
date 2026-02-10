# Incidents Response Classification
This project focuses on building a machine learning model to classify cybersecurity incidents by predicting their IncidentGrade (triage grade). The goal is to support Security Operation Centers (SOCs) by automating incident prioritization, enabling faster detection of critical threats and improving response efficiency. The project uses large-scale incident datasets containing categorical and timestamp-based features such as AlertTitle, Category, EntityType, and more.

# Work Overview
The workflow of this project follows a complete ML pipeline:
1. Data Exploration & Preprocessing
2. Data Balancing
- Applied SMOTE to solve class imbalance in the target feature IncidentGrade.
3. Model Training & Evaluation
  
 Trained and compared multiple ML models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - XGBoost
  - LightGBM
  - Gradient Boosting
    
Evaluation metrics used:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
📌 Best Model: Random Forest

# Requirements
To run this project, install the requirements folder
