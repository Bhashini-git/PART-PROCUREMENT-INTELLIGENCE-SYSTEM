# Part Procurement Intelligence System

This repository contains the internship report for my project completed at **Hindustan Aeronautics Limited (HAL), Avionics Division, Hyderabad**. Due to organizational confidentiality and intellectual property policies, the source code, datasets, and internal dashboards cannot be shared publicly. This report documents the system architecture, machine learning methodology, feature engineering pipeline, predictive modeling approach, and dashboard design implemented during the internship.

## Project Overview

The **Part Procurement Intelligence System** is a machine learning–based decision support solution designed to improve procurement planning by predicting lead times for critical aircraft components. Traditional procurement planning often relies on historical averages, making it difficult to anticipate delays caused by supplier performance, administrative processing, or logistics. This project introduces a predictive analytics framework that forecasts procurement timelines using historical procurement records and visualizes insights through interactive Power BI dashboards.

## Key Features

* Predicts procurement lead time using supervised machine learning.
* Separates procurement into administrative and supplier logistics phases for detailed delay analysis.
* Performs feature engineering on procurement, supplier, and financial data.
* Handles missing values, categorical encoding, and date transformations using Scikit-learn pipelines.
* Uses HistGradientBoostingRegressor for lead-time prediction.
* Generates interactive Power BI dashboards for procurement monitoring.
* Supports data-driven procurement planning and operational decision-making.

## Technology Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* HistGradientBoostingRegressor
* Power BI
* Joblib
* Anaconda

## Project Architecture

The solution follows a modular architecture consisting of:

* Data preprocessing pipeline
* Feature engineering module
* Machine learning training pipeline
* Prediction engine
* Model evaluation module
* Power BI reporting dashboard

## Machine Learning Workflow

The predictive pipeline includes:

* Data cleaning and preprocessing
* Missing value imputation
* Feature engineering
* Categorical encoding
* Regression model training
* Model evaluation using MAE, RMSE, and R²
* Lead-time prediction and visualization

## Dashboard

Power BI dashboards were developed to visualize:
<img width="1029" height="694" alt="image" src="https://github.com/user-attachments/assets/f70018c9-17f7-4401-b35e-11334cfa3c3c" />


* Procurement lead-time trends
* Supplier performance
* Country-wise sourcing analysis
* Procurement bottlenecks
* Component-level predictions

## Repository Contents

* Internship Report (PDF)
* Project documentation
* System architecture
* Methodology
* Dashboard screenshots (where permitted)

## Confidentiality Notice

This repository contains **documentation only**. The implementation code, procurement datasets, dashboards, and other project artifacts were developed during my internship at **Hindustan Aeronautics Limited (HAL)** and cannot be published due to confidentiality and organizational data protection policies. This repository is intended to demonstrate the project's design, methodology, and technical approach without disclosing proprietary information.
