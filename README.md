# Coronary Heart Disease Risk Prediction


Project Overview
The primary objective of this exploratory data analysis (EDA) is to lay a strong analytical foundation for the development of a predictive model aimed at identifying individuals at high risk of developing coronary heart disease (CHD) within the next 10 years. This predictive endeavor is crucial for early intervention strategies and enhancing patient outcomes by targeting preventive measures to those most at risk.

Repository Structure
This repository contains the following files:

project_report.pdf: Detailed report on the exploratory data analysis, model development, and findings.
prediction.csv: The prediction results for individuals in the dataset, indicating their risk of developing CHD within the next 10 years.
model_pipeline.pkl: The trained model pipeline used for predicting CHD risk.
pipeline_flow_chart.png: A visual representation of the model pipeline, illustrating the steps involved in data preprocessing and model prediction.



Files Description
project_report.pdf
This report provides a comprehensive overview of the exploratory data analysis, including:

Data description and preprocessing steps
Statistical analysis and visualizations
Feature selection and engineering
Model development and evaluation
Key findings and conclusions
prediction.csv
This file contains the prediction results, with the following columns:

patientID: Unique identifier for each individual in the dataset
TenYearCHD: The predicted probability of developing CHD within the next 10 years

model_pipeline.pkl
This is the serialized model pipeline, which includes all preprocessing steps and the trained predictive model. The pipeline can be used to make predictions on new data.

pipeline_flow_chart.png
A flow chart that visually represents the steps involved in the model pipeline, including:

Data preprocessing
Feature engineering
Model training
Prediction generation
