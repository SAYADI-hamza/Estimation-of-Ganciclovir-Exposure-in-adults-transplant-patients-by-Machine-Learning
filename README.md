Here you can find scripts, RDS files, CSV, and complementary data related to Estimation of Ganciclovir Exposure in adults transplant patients by Machine Learning.

The files entitled "valganciclovir_900_DIE", "valganciclovir_450_DIE", "valganciclovir_450_QOD" and "valganciclovir_450_BIS" are scripts used to develop machine learning models to predict the inter dose AUCss of ganciclovir from 2 or 3 samples. In these files, xgboost is developed. We used the Lalagkas and Vezina models for the implementation. 
These files also include the script for the external validation of our xgboost models on validation datasets based on the Caldes and Chen model implementation, and for estimating the AUC using MAP-BE with the Lalagkas and Vezina models.

The files titled "Patients_from_Lalagkas_et_al_model" and "Patients_from_Vezina_et_al_model" contain the pharmacokinetic profiles of simulated patients used to train the ML algorithms.

The files titled "patients_from_Caldés_et_al_model_and_AUCss_estimation." and "patients_from_Chen_et_al_model_and_AUCss_estimation" contain the simulated patients used for external validation of our ML algorithms. These files also include the estimated AUC values by the ML algorithms and estimated by MAP-BE using the Lalagkas and Vezina models

The PDF named "Complementary data.pdf" corresponds to supplemental data. 
It contain figure S1:  Scatterplots of bias as a function of reference AUCss in the validation set.

