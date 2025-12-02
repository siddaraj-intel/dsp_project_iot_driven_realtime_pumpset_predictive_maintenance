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
