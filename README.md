# Customer-Churn-Prediction
Machine Learning project on the Telco Customer Churn dataset – includes EDA, preprocessing, SMOTE for class imbalance, and model comparison (Random Forest, XGBoost, LightGBM). Best model (LightGBM) achieved ~79% accuracy and ~64% recall on churners.

# Telco Customer Churn Prediction

This project predicts customer churn using the **Telco Customer Churn dataset**.  
The goal is to identify customers likely to leave a telecom service provider, enabling proactive retention strategies.  

---

## 📊 Project Overview
- **Dataset**: IBM Telco Customer Churn dataset (~7,043 records).  
- **Objective**: Predict whether a customer will churn (leave) or not.  
- **Approach**:  
  - Exploratory Data Analysis (EDA) & feature engineering.  
  - Preprocessing: handling missing values, encoding categorical features, class balancing with **SMOTE**.  
  - Model training: **Random Forest, XGBoost, LightGBM**.  
  - Hyperparameter tuning using **GridSearchCV** and **RandomizedSearchCV**.  
  - Model evaluation with **confusion matrix, ROC curve, PR curve, and classification report**.  

---

## 🚀 Results
- **Best Model**: LightGBM  
- **Test Accuracy**: ~79%  
- **Recall on churners**: ~64%  
- Outperformed baseline models on both accuracy and recall.  

---

## 🛠️ Tech Stack
- **Languages**: Python  
- **Libraries**: scikit-learn, XGBoost, LightGBM, imbalanced-learn, pandas, numpy, matplotlib, seaborn  
- **Environment**: Jupyter Notebook  
