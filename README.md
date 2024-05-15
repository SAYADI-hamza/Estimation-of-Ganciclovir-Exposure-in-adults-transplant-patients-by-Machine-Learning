Here you can find scripts, RDS files, CSV, and complementary data related to Estimation of Ganciclovir Exposure in adults transplant patients by Machine Learning.

The files entitled "valganciclovir_900_DIE", "valganciclovir_450_DIE", "valganciclovir_450_QOD" and "valganciclovir_450_BIS" are scripts used to develop machine learning models to predict the AUC of ganciclovir from 2 or 3 samples. In these files, xgboost is developed. We used the Lalagkas and Vezina models for the implementation. 
These files also contain the script for the external validation of our xgboost models on validation datasets based on the Caldes and Chen model implementation.


The RDS file named "auc_daptomycin_xgboost_1_99_res0_temp_filter.rds" is the RDS file of the xgboost model developed in "Dapto_AUC_ML". 
You can load it directly to run the script instead of starting from the beginning of the generation of this model.

The HTML file named "Dapto_AUC_external.html" is the script for the external validation of our xgboost model in the external dataset based on Garreau model implementation.

The PDF named "Complementary data.pdf" corresponds to supplemental data. 
It contain figure S1:  Scatterplots of bias as a function of reference AUCss in the validation set.


The HTML file named "dapto_cyrielle_reviewer_answer_281223.html" is the script used to generate Bayesian estimations of Daptomycin AUC. This script has been established at the request of the reviewer for article submission.
CSV files named "data_2_pt_map_be_dapto_simul_dvorchik_temp_filter_res0.csv" and "external_data_2_pt_map_be_dapto_simul_garreau.csv" are the CSV files needed to run "dapto_cyrielle_reviewer_answer_281223."
