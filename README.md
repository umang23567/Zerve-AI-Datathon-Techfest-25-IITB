# Zerve AI Datathon – Insurance Claim Prediction Challenge

Participated in the **Zerve AI Datathon**, conducted as part of **Techfest IIT Bombay**, focused on building predictive models for **insurance claim prediction** using anonymized tabular data.

## Overview
The challenge involved training machine learning models on an **anonymized tabular dataset** related to insurance claims and generating predictions for a **held-out test set** used for final evaluation. Model performance was assessed using **Normalized Gini**, along with evaluation of methodology and reasoning during the final presentation.

## Modeling Approach
- Preprocessed and analyzed anonymized, imbalanced insurance-related tabular data  
- Conducted exploratory data analysis and model experimentation to identify effective approaches  
- Built an **ensemble of LightGBM and CatBoost** for best performance
- Optimized models with respect to **Normalized Gini**  

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Scikit-learn  
- LightGBM, CatBoost  

## Outcome
- Achieved **~0.297 Normalized Gini** on a validation split derived from the training data, used for model selection and tuning  
- Secured **5th position in the final round at IIT Bombay**, based on model performance on unseen test data (submission csv) and presentation  
