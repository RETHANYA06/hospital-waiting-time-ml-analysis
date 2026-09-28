# Hospital Waiting Time ML Analysis

## Project Overview

This project analyzes patient waiting times in a hospital outpatient department (OPD). The goal is to identify waiting-time patterns, understand possible congestion during appointment periods, compare weekday and weekend performance, and use a Random Forest model to predict total patient waiting time.

## Dataset

The dataset contains 100 patient records with the following information:

* Patient ID
* Department
* Appointment Time
* Registration Time
* Consultation Time
* Discharge Time
* Doctor
* Day
* Appointment Type

## Data Analysis

The analysis includes:

* Data cleaning and validation
* Registration waiting time calculation
* Doctor waiting time calculation
* Total patient waiting time calculation
* Department-wise waiting-time analysis
* Appointment scheduling analysis
* Weekday vs weekend comparison
* Data visualizations

## Machine Learning

**Algorithm:** Random Forest Regressor

The model predicts **Total Waiting Time** using appointment and patient-related scheduling information.

### Model Evaluation

| Metric   |        Result |
| -------- | ------------: |
| MAE      | 10.71 minutes |
| RMSE     | 13.41 minutes |
| R² Score |         0.108 |


## Project Files

* `hospital_waiting_time.csv` — Dataset
* `Hospital_Waiting_Time_Analysis.ipynb` — Python/Colab analysis
* `Hospital_Waiting_Time_Analysis.pdf` — Project report
