[Machine Learning Full Report.pdf](Machine Learning Full Report.pdf)

# Machine Learning Project 1: Unsupervised Learning

This project analyzes mobile device usage data using unsupervised learning techniques. The aim is to uncover hidden user behavior patterns and segment users into distinct groups.  

---

## Overview
- **Objective:** Apply Principal Component Analysis (PCA) and clustering to identify mobile user segments.  
- **Main Points:**  
  - Reduced dimensionality with PCA while retaining ~90% variance.  
  - Performed hierarchical clustering to group users into heavy, moderate, and light usage categories.  
  - Identified key drivers such as app usage time, screen-on time, and battery drain.  
- **Tools Used:** Python (pandas, numpy, scikit-learn, matplotlib, seaborn)  

---

## Outputs
- PCA variance plots and feature loadings.  
- Dendrograms and cluster visualizations.  
- Behavioral segmentation insights for UX and marketing applications.

---

# Machine Learning Project 2: Regression

This project applies regression models to the World Happiness dataset to quantify how socioeconomic and demographic factors influence happiness scores across countries.  

---

## Overview
- **Objective:** Build regression models to explain variance in happiness scores.  
- **Main Points:**  
  - Multiple linear regression applied to factors such as GDP per capita, social support, and healthy life expectancy.  
  - Found GDP, social support, and health to be the strongest predictors.  
  - Conducted residual diagnostics and checked for multicollinearity.  
- **Tools Used:** Python (pandas, scikit-learn, statsmodels, seaborn, matplotlib)  

---

## Outputs
- Regression tables with coefficients and p-values.  
- Diagnostic plots validating model assumptions.  
- Insights for policymakers and social research on well-being.  

---

# Machine Learning Project 3: Classification

This project builds classification models to detect fraudulent transactions in a highly imbalanced credit card dataset, where fraud cases account for only ~0.17% of total transactions.  

---

## Overview
- **Objective:** Train and evaluate classification models for fraud detection.  
- **Main Points:**  
  - Implemented logistic regression, decision tree, and random forest classifiers.  
  - Applied SMOTE to address dataset imbalance.  
  - Evaluated performance with precision, recall, F1-score, and ROC-AUC.  
- **Tools Used:** Python (pandas, scikit-learn, imbalanced-learn, seaborn, matplotlib)  

---

## Outputs
- Confusion matrices, precision/recall metrics, and ROC curves.  
- Random Forest with SMOTE achieved the best fraud detection performance.  
- Demonstrates the importance of imbalanced classification strategies in financial risk management.  

