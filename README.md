# Analisa Iklim dan Banjir Jakarta

This project analyzes climate factors and their relationship to flooding events in Jakarta.  
Using machine learning models such as **Random Forest** and **Logistic Regression**, the study explores predictive modeling of flood occurrences based on climate data (2016–2020).

---

## Overview
Jakarta faces recurring floods due to heavy rainfall, land subsidence, and insufficient drainage infrastructure. This project aims to provide insights and predictive capabilities by analyzing meteorological features such as:
- Rainfall
- Humidity
- Temperature
- Wind speed

By leveraging data-driven methods, the project seeks to support **flood risk mitigation** and **decision-making**.

---

## Methodology
1. **Data Collection**  
   - Climate and flood datasets (2016–2020) sourced from Kaggle and government reports.

2. **Data Preparation**  
   - Cleaning and preprocessing (handling missing values, outliers).  
   - Encoding categorical features and balancing data using **SMOTE**.

3. **Modeling**  
   - Logistic Regression: baseline linear model.  
   - Random Forest: ensemble-based model for complex feature interactions.  

4. **Evaluation Metrics**  
   - Accuracy  
   - Precision & Recall  
   - F1-score  
   - ROC-AUC with visualization

5. **Visualization**  
   - Flood frequency by region, month, and year.  
   - ROC Curves for model comparison.  

---

## Key Findings
- **Random Forest** achieved higher overall accuracy (~92%) and precision but lower recall.  
- **Logistic Regression** achieved higher recall (~81%) and ROC AUC (~87%), making it more suitable when detecting flood events is the top priority.  
- Trade-offs highlight that the choice of model depends on whether minimizing false negatives (flood detection) or false positives (precision) is more important.  

---

## Tools & Environment
- Python (Google Colab)  
- scikit-learn  
- Pandas, NumPy  
- Matplotlib, Seaborn  

---

## Authors
- Hendy Cahyadi Tandiono  
- Stefanus Marcellino  
- Benediktus Arthur Suparto  
- Jordi Austin Iskandar  
- Geoffrey Duncan Julianto  
- Joseph Budihartanto  

---
