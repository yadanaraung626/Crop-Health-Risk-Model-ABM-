# Crop-Health-Risk-Model-ABM-
The Crop Health Risk Model is a data science project that predicts crop health and evaluates agricultural conditions using environmental, soil, and management data. The project combines feature engineering and a hierarchical analytical framework to assess crop growth, identify potential risks, and support data-driven agricultural decision-making.
Objectives
Analyze environmental and agricultural factors affecting crop health.
Engineer meaningful scientific features from raw data.
Build a multi-layer analytical model to evaluate crop conditions.
Predict crop growth outlook, immediate risk, and overall crop viability.
Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Jupyter Notebook
Dataset Features

The model analyzes multiple categories of data, including:

Soil nutrients (N, P, K)
Temperature
Humidity
Rainfall
Soil moisture
Soil pH
Organic matter
Sunlight exposure
Wind speed
CO₂ concentration
Irrigation frequency
Pest pressure
Crop growth stage
Water source and soil type
Feature Engineering

To improve prediction quality, several scientific indicators were engineered, including:

Temperature-Humidity Index (THI) – Heat stress indicator
Vapor Pressure Deficit (VPD) – Atmospheric dryness
Growing Degree Days (GDD) – Crop growth accumulation
Soil Moisture Deficit (SMD) – Water shortage indicator
Nutrient balance ratios (N, P, K)

These engineered features were combined into a hierarchical framework consisting of:

Intermediate Indicators (i1–i9)
Crop Condition Layer
Crop Behavior Layer
Output Prediction Layer
Model Outputs

The model predicts:

🌱 Growth Outlook
⚠️ Immediate Risk
✅ Crop Viability

These outputs help evaluate whether crops are in a Healthy, Moderate, Warning, or Critical condition.
