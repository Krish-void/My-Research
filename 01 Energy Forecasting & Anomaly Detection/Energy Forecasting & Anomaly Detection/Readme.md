# Energy Forecasting & Anomaly Detection

**A Machine Learning Approach for Detecting Abnormal Energy Consumption Patterns**

## Overview

This research investigates the use of machine learning for electricity consumption forecasting and the detection of potentially abnormal consumption patterns. The proposed approach analyses deviations between actual and predicted consumption to identify observations that differ from expected behaviour.

**Research Pipeline:** Forecasting → Residual Analysis → Anomaly Detection → Interpretation

## Research Objectives

- Develop and evaluate machine learning models for short-term electricity consumption forecasting.
- Investigate temporal, lag-based, and rolling statistical features.
- Explore residual-based methods for detecting potential anomalies.
- Analyse detected patterns using feature importance and explainability techniques.
- Evaluate forecasting performance and robustness using time-aware experiments.

## Dataset

**ElectricityLoadDiagrams20112014 — UCI Machine Learning Repository**

- 370 electricity consumers
- 15-minute measurement intervals
- Data covering 2011–2014

**Source:** [UCI Dataset](https://archive.ics.uci.edu/dataset/321/electricityloaddiagrams20112014)

The dataset is not included in this repository due to its size. Refer to the source above to obtain the data.

## Methodology

1. Data validation and exploratory analysis
2. Preprocessing and feature engineering
3. Chronological train-validation-test splitting
4. Forecasting model development and comparison
5. Residual-based anomaly detection
6. Interpretability and robustness analysis

**Planned forecasting models:** Naive Baseline, Linear Regression, Random Forest, Gradient Boosting, and XGBoost.

**Evaluation metrics:** MAE, RMSE, and R².

Potential anomalies will be investigated using statistical thresholds and methods such as Isolation Forest. Detected anomalies will not be treated as confirmed physical faults without independent evidence.

## Technology Stack

Python · Pandas · NumPy · Scikit-learn · XGBoost · SHAP · Matplotlib · Google Colab

## Project Progress

- **Week 1:** Dataset understanding and exploratory data analysis completed.
- **Week 2:** Preprocessing and feature engineering in progress.
- **Next stages:** Forecasting, anomaly detection, interpretability, and robustness experiments.

## Research Team

- Krishna Sharrma
- Jaydev Rana
- Subhojit Giri

**Institution:** SRM Institute of Science and Technology (SRMIST)  
**Department:** Computer Science and Engineering – Data Science

## Research Status

This is an ongoing undergraduate research project. Model comparisons, experimental results, and conclusions will be documented after validation. The effectiveness and contribution of the proposed framework will be determined through experiments rather than assumed in advance.