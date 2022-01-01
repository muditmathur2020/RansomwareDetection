# Ransomware Detection using Machine Learning

![Ransomware](Photos/header.jpeg)

**Goal of this Project**
Predict Ransomware based on file properties extracted from a tool. This model is a part of Full Antivirus + Malware Protection Software.
Its a classification problem (Supervised Machine Learning). The data was immbalanced and needed to be transformed (Synthetic Samples: SMOTE-Tomek).


**Highlights**
* Lazy Predict for AutoML
* Lime for Local Explainations
* WoE 

**Model Performance on Test Dataset**

![Ransomware](Photos/confusion_matrix.png)
- Confusion Matrix 

**Metrics**
* F1 Score: 0.99
* Matthews Correlation Coefficient (MCC): 0.985
* AUC-ROC: 0.993



**Additional Libraries Used:**
* pefile
* pickle
* joblib
* mlxtend
* statsmodels
* sklearn

**Concepts Used:**
* Multicollinearity (VIF)
* Weight of Evidence (Feature Selection)

