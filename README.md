# Cyclone Preheater Anomaly Detection

## Overview

This project analyzes cyclone preheater industrial process data to identify abnormal observations and abnormal time periods using multivariate anomaly detection.

## Dataset

The dataset contains six cyclone preheater process variables collected at 5-minute intervals.

## Methodology

1. Data cleaning
2. Missing-value handling
3. Sensor data preparation
4. Exploratory analysis using histograms
5. Multivariate Isolation Forest
6. Anomaly scoring
7. Temporal grouping of anomalous observations
8. Abnormal-period extraction
9. Visualization of detected anomalies

## Model

Isolation Forest is used to identify observations with unusual combinations of the six sensor measurements.

## Results

The analysis identifies anomalous observations and groups consecutive anomalies into abnormal periods. Each abnormal period is reported using its start time, end time, and number of anomalous observations.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

es