# Association Between C-Reactive Protein (CRP) Levels and Acute Myocardial Infarction in Patients with Type 2 Diabetes

This repository contains data analysis and results from a study investigating the relationship between **C-reactive protein (CRP)** levels and the occurrence of **acute myocardial infarction (MI)** in patients with **type 2 diabetes (T2D)**. 

## Overview

Elevated CRP, a biomarker of systemic inflammation, has been widely recognized as a risk factor for cardiovascular events. However, its specific role in predicting acute MI among individuals with T2D has not been fully clarified.

This study aims to:
- Examine the association between CRP levels and acute MI using **logistic regression analysis**.
- Evaluate predictive performance using **k-nearest neighbors (k-NN)** classification with **10-fold cross-validation**.

## Key Findings

- **Logistic Regression Results**:
  - CRP was significantly associated with acute MI:  
    - OR = 1.024, *p* = 0.00318
  - After adjusting for **age** and **glucose level**:
    - CRP + Age: OR = 1.026, *p* = 0.00176  
    - CRP + Glucose: OR = 1.023, *p* = 0.00457

- **k-NN Classification**:
  - 10-fold cross-validation used to assess model performance.
  - Highest accuracy observed at **k = 11**:
    - Standard k-NN: Accuracy = **0.769**
    - Custom k-NN (variant): Accuracy = **0.686**

## Conclusion

The results indicate a **positive association** between CRP levels and the incidence of acute MI in patients with T2D. Nevertheless, **CRP alone** may not serve as a highly accurate or efficient standalone predictor of MI risk. Additional factors and models should be explored to improve predictive capabilities.

