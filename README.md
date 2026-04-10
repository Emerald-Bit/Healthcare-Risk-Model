# Predicting Clinical Trial Completion from ISRCTN Registry Data

### Executive Summary


**Problem** Predict whether a registered clinical trial will complete or terminate 
early.

**Data** ISRCTN registry data; 27,506 records and 29 working columns after 
initial pruning.

**Source Link:** ISRCTN Advanced Search Results

**Target** Completed = 1, Not Completed = 0, with an approximate 96:4 class 
split.

**Stack** Snowflake preprocessing, Python feature engineering, SciBERT embeddings, MLflow tracking.

**Outcome** XGBoost delivered the best overall macro F1 baseline, with further scope for minority-class tuning.

Please view the report for more information.
