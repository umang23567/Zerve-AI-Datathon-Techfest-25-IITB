# Zerve AI Datathon – Insurance Claim Prediction Challenge

Participated in the **Zerve AI Datathon**, conducted as part of **Techfest IIT Bombay**, focused on building predictive models that generalize well to unseen data.

## Overview
The challenge involved predicting the likelihood of **insurance claims** using an **anonymized tabular dataset**, where feature meanings were hidden. Models were trained on the provided data and used to generate predictions for a **hidden test set**, which was used for final evaluation. Performance was measured using **Normalized Gini**, along with assessment of modeling methodology and reasoning during the final presentation.

## Key Tasks
- Preprocessed and analyzed anonymized, imbalanced tabular data  
- Designed validation strategies aligned with the competition metric  
- Performed feature handling and exploratory analysis  
- Experimented with multiple supervised learning models  
- Generated final prediction files for hidden test evaluation  

## Modeling Approach
- Conducted data analysis and model experimentation to identify effective approaches  
- Built an **ensemble of LightGBM and CatBoost** for improved robustness  
- Optimized models with respect to **Normalized Gini**  

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Scikit-learn  
- LightGBM, CatBoost  

## Outcome
- Achieved **~0.297 Normalized Gini on a validation split derived from the training data**, used for model selection and tuning  
- Secured **5th position in the final round at IIT Bombay**, based on hidden test performance and presentation  
