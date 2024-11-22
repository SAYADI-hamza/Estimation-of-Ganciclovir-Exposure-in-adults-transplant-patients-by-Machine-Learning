Here, you will find scripts, Excel files, and supplementary data related to the estimation of ganciclovir exposure in adult transplant patients using machine learning.

The scripts/ folder contains:
-Scripts used to develop machine learning models for predicting the inter-dose AUCss of ganciclovir based on 2 or 3 sample measurements.
-Script for the external validation of XGBoost models using simulated validation datasets .
-Scripts for estimating AUC using the MAP-BE method with the Lalagkas and Vezina models.

The data/ folder contains pharmacokinetic profiles and AUC values for:
-Simulated patients used to train and test the machine learning algorithms (..._dvp_ML.xlsx).
-Simulated patients used for external validation of the ML algorithms, based on the Caldés et al. and Chen et al. models.

The "Shinyapps" file contains a link to a Shiny interface for real-time calculation of inter-dose AUCss. 

The PDF titled "supplementary materials.pdf" contains additional data and supporting materials related to the study.
