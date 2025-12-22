# Data-Driven Prediction of Chronic Obstructive Pulmonary Disease (COPD)

 We apply advanced machine learning techniques to predict Chronic Obstructive Pulmonary Disease (COPD) using synthetic clinical and encounter data from the MedSynora Data Warehouse (DW). The goal is to enable early identification of individuals at risk of developing COPD through comprehensive data integration and predictive modeling.

 - # Installation
    - ### pandas
    - ### numpy
    - ### scikit-learn
    - ### imbalanced-learn
    - ### xgboost
    - ### matplotlib
    - ### seaborn
  We recommend using the Anaconda Python distribution
 and a Python version ≥ 3.7. All dependencies can be installed via:`
 <pre> bash 
 pip install -r requirements.txt  </pre>

 ## Motivation

COPD is a major cause of morbidity and mortality worldwide, especially in aging and urbanized populations. Since COPD is progressive and incurable, early detection and intervention can significantly improve outcomes and reduce healthcare burden. Leveraging synthetic electronic health records from MedSynora DW allows for rapid prototyping and evaluation of machine learning workflows in a privacy-safe environment.

## Files

COPD_Risk_Prediction.ipynb – Jupyter notebook for data processing, model training, and evaluation

DimPatient.csv, DimDisease.csv, FactEncounter.csv – Extracts from the MedSynora DW used in the modeling pipeline

*.png – Output visualizations such as ROC curves, feature importances, confusion matrices
    

