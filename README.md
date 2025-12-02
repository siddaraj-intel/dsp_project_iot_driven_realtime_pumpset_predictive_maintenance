# dsp_project_iot_driven_realtime_pumpset_predictive_maintenance




Problem Statement: Predict Remaining Useful Life (RUL) for industrial assets to enable proactive maintenance.
Dataset Description: ~166K rows, 50 sensors, RUL target, fail_in_H label, right-skewed distribution.
High-Level Approach:

Preprocessing (unit/cycle inference, imputation, labeling)
EDA (distribution, correlations, failure class imbalance)
Modeling (LightGBM, CatBoost, event flags, stratified splits)
Evaluation (RMSE, MAE, R², parity plots, residual analysis)


Summary of Results:

Best Model: LightGBM + Event Flags
RMSE ≈ 12.56, MAE ≈ 6.49, R² ≈ 0.9969
Event-driven features improved accuracy by ~2.4%


Next Steps: SHAP analysis, LSTM modeling, real-time deployment.





Steps to Execute :
-------------------------
Copy the entire dsp-poc folder in the google drive under MyDrive

Also copy the dsp_rul_generate folder to MyDrive.

Excute Code in the following Order -

First run the " dsp_rul_and_eda.ipynb " 

Post that

enter the dsp-poc/predictive_maintenance_pipeline folder and run in serial order as per name.


