Here you can find scripts, RDS files, CSV, and complementary data related to Estimation of Ganciclovir Exposure in adults transplant patients by Machine Learning.

The HTML file named "Dapto_AUC_ML.html" is the script for developing machine learning models to predict Daptomycin AUC from 2 samples. 
In this HTML, xgboost are developed. We used the Dvorchik model for the implementation.

The RDS file named "auc_daptomycin_xgboost_1_99_res0_temp_filter.rds" is the RDS file of the xgboost model developed in "Dapto_AUC_ML". 
You can load it directly to run the script instead of starting from the beginning of the generation of this model.

The HTML file named "Dapto_AUC_external.html" is the script for the external validation of our xgboost model in the external dataset based on Garreau model implementation.

The PDF named "Complementary data.pdf" corresponds to supplemental data. 
It contains:
Table S1: Best-tuned parameter values for each XGBoost model.
Table S2: Contingency table for categorized predictions (...)
Table S3: Performances of the machine learning models in the training and testing datasets to estimate Daptomycin AUCs obtained from two samples.

The HTML file named "dapto_cyrielle_reviewer_answer_281223.html" is the script used to generate Bayesian estimations of Daptomycin AUC. This script has been established at the request of the reviewer for article submission.
CSV files named "data_2_pt_map_be_dapto_simul_dvorchik_temp_filter_res0.csv" and "external_data_2_pt_map_be_dapto_simul_garreau.csv" are the CSV files needed to run "dapto_cyrielle_reviewer_answer_281223."
