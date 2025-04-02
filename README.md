# Gold Recovery Optimization Project

**Objective:** Develop a robust machine learning model to optimize gold recovery by analyzing industrial purification data.

## Overview
This project involves preprocessing, analyzing, and modeling data to improve gold recovery efficiency. The solution uses advanced evaluation metrics (sMAPE) and data validation techniques to ensure reliable results.

## Key Steps:
1. **Data Preparation:** 
   - Open and inspect datasets (`gold_recovery_train.csv`, `gold_recovery_test.csv`, `gold_recovery_full.csv`).
   - Verify recovery calculations (`rougher.output.recovery`) using the training set and assess errors (MAE).
   - Identify missing features in the test set and preprocess data effectively.

2. **Data Analysis:**
   - Explore metal (Au, Ag, Pb) concentration changes during purification stages.
   - Compare particle size distributions across training and testing sets.
   - Identify and remove anomalies in total substance concentrations.

3. **Model Building:**
   - Implement custom sMAPE evaluation metric.
   - Train multiple models and apply cross-validation to identify the best performer.
   - Test the chosen model on validation and testing datasets.

## Tools:
- Python libraries: `Pandas`, `NumPy`, `scikit-learn`
- Metrics: sMAPE (Symmetric Mean Absolute Percentage Error)
