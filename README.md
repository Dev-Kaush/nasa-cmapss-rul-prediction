# nasa-cmapss-rul-prediction
Objective: Developed a machine learning regression pipeline to estimate the Remaining Useful Life (RUL) of turbofan engines based on transient sensor data.

Dataset: NASA C-MAPSS (Commercial Modular Aero-Propulsion System Simulation).

Current Implementation: Focuses on the FD001 sub-dataset (single operating condition, single fault mode) to establish the baseline preprocessing and regression architecture.

Technical Stack:
    Language: Python
    Libraries: Scikit-learn, Pandas, NumPy, Matplotlib
  
Pipeline Overview:
1.Data Processing: Cleaned and normalized sensor readings; dropped constant-value sensor columns to eliminate noise.

2.Feature Engineering: Mapped operating conditions to sensor outputs to establish degradation baselines.

3.Model Training: Evaluated regression models to predict continuous RUL values for the engines.

Results:
    Achieved an RMSE of [Insert Number] on the test set.

Future Work (Phase 2):
    Scale the existing pipeline to ingest datasets FD002 through FD004, requiring advanced feature engineering to account for multiple operating conditions and complex, multi-fault degradation modes.
