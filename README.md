# 🧠 Stroke Risk Prediction

This project aims to predict the likelihood of stroke in patients using demographic and clinical data. Developed as part of the Healthcare Analytics (DSO 568) course at the University of Southern California, the project supports early intervention by helping healthcare providers identify high-risk individuals during routine checkups.

Combining machine learning techniques with medical insights, the model offers a scalable and interpretable solution for proactive stroke prevention.

---

## 📊 Project Overview

The dataset includes 5,110 patient records with variables such as age, hypertension, heart disease, BMI, glucose levels, and smoking status. Only ~5% of patients had experienced a stroke, presenting a significant class imbalance challenge.

Key steps in the project included:

- Conducting exploratory data analysis and data cleaning  
- Addressing class imbalance using SMOTE  
- Training and evaluating multiple classification models  
- Tuning hyperparameters to optimize performance  
- Comparing model results and selecting the best solution for deployment  

---

## 🎯 Objectives

- Build a predictive model to estimate the risk of stroke based on patient data  
- Prioritize recall to minimize false negatives in clinical settings  
- Identify the most influential features associated with stroke  
- Ensure the model is both generalizable and interpretable for healthcare use  

---

## 🧠 Machine Learning Models Explored

| Model               | Description                                                |
|--------------------|------------------------------------------------------------|
| Logistic Regression | Interpretable baseline model for comparison               |
| Decision Tree       | Rule-based model for visual explanation                   |
| Random Forest       | Robust ensemble model handling feature interactions       |
| XGBoost             | Tuned gradient boosting model with strong performance     |
| **Ensemble (RF + XGBoost)** | Final model combining both models for optimal results        |

✅ **Final Model**: **Ensemble of Random Forest and XGBoost**  
- **Accuracy**: 95.47%  
- **Precision**: 94%  
- **Recall**: 97%  
- **F1-Score**: 96%  
- **AUC-ROC**: 99.04%  

The ensemble model outperformed all individual models by effectively balancing sensitivity and specificity, making it ideal for medical decision-making.

---

## 🔍 Key Features Used

- Age  
- Hypertension  
- Heart disease  
- Average glucose level  
- BMI  
- Smoking status  
- Gender  
- Work type  
- Residence type  

Feature selection was based on both statistical correlation and medical relevance.

---

## 📈 Clinical Impact

- Assists in identifying patients at high risk of stroke using readily available data  
- Enables early-stage screening during outpatient visits  
- Supports physicians in prioritizing preventive care efforts  
- Reduces reliance on manual assessments or costly diagnostic procedures  
- Increases confidence in clinical decisions through interpretable model outputs  

---

## 💡 Technologies & Tools

- Python  
- Pandas, NumPy  
- Scikit-learn 
- Matplotlib, Seaborn  
- SMOTE (for class imbalance handling)  
- Jupyter Notebook & Google Colab for modeling and experimentation  

