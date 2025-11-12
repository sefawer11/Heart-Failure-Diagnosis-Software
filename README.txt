Heart Failure Mortality Prediction System
Overview
A professional MATLAB-based GUI application for predicting heart failure mortality risk using advanced machine learning models. The system provides real-time risk assessment with interactive visualizations and comprehensive reporting capabilities.
Features

4 AI Models: Baseline Neural Network, Dropout Regularization, Early Stopping, SCG Optimization
Interactive Interface: Modern, user-friendly GUI with color-coded risk indicators
Real-time Analysis: Instant mortality risk predictions with confidence scores
Population Comparison: Visual comparison of patient metrics against population distributions
Batch Processing: Analyze multiple patients from CSV/Excel files
Export Reports: Generate detailed prediction reports in text format

Requirements

MATLAB R2019b or later
Neural Network Toolbox
Statistics and Machine Learning Toolbox
Pre-trained models file: saved_models/heart_failure_models.mat
(Optional) Dataset: heart_failure_clinical_records_dataset.csv

Installation

Clone or download all files to your MATLAB workspace
Ensure saved_models/ directory contains trained models
Run HeartFailurePredictionGUI() in MATLAB command window

Usage
Single Patient Prediction

Launch: Run HeartFailurePredictionGUI() in MATLAB
Input Data: Enter patient clinical parameters:

Demographics: Age, Sex
Clinical: Ejection Fraction, Creatinine, Sodium, CPK, Platelets
Conditions: Anemia, Diabetes, High BP, Smoking
Follow-up: Time period in days


Select Model: Choose from dropdown (Dropout Regularization recommended)
Predict: Click "PREDICT MORTALITY RISK" button
View Results: Review risk level, probability, and population comparisons

Quick Start Examples

Click "✓ High Risk Example" to load a high-risk patient profile
Click "✓ Low Risk Example" to load a low-risk patient profile
Click "🗑️ Clear" to reset all inputs

Batch Prediction

Prepare CSV/Excel file with 12 columns (clinical features)
Click "Batch Prediction" button
Select your data file
Review summary statistics
Save results with predictions added

Export Reports

After prediction, click "Export Report" to save detailed analysis as text file