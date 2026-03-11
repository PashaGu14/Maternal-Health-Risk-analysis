# Maternal Health Risk Analysis

## Overview

Maternal health outcomes remain a critical public health challenge, particularly in regions where consistent prenatal monitoring is limited. This project analyzes clinical indicators associated with maternal risk levels using the **Maternal Health Risk Dataset**.

The goal of this analysis is to identify physiological indicators that most strongly correlate with elevated maternal health risk and to explore whether combinations of vital signs can predict maternal risk classification.

The workflow combines:

* Exploratory data analysis
* SQL-style analytical queries
* Statistical correlation analysis
* Risk scoring
* Predictive modeling

Through this analysis, the project demonstrates how healthcare datasets can be transformed into decision-support insights that help identify high-risk pregnancies earlier.

---

# Tech Stack

| Tool             | Role                                 |
| ---------------- | ------------------------------------ |
| Python           | Core analysis workflow               |
| pandas           | Data manipulation and transformation |
| NumPy            | Numerical calculations               |
| SQLite           | Structured data querying             |
| Seaborn          | Statistical visualization            |
| Matplotlib       | Plotting and charting                |
| scikit-learn     | Machine learning models              |
| Jupyter Notebook | Reproducible research environment    |

---

# Analysis Workflow

| Step | Phase                         | Description                                                |
| ---- | ----------------------------- | ---------------------------------------------------------- |
| 1.   | Setup & Configuration         | Define analysis parameters and visualization settings      |
| 2.   | Data Acquisition              | Load maternal health dataset and perform validation checks |
| 3.   | SQL Database Layer            | Store dataset in SQLite and execute clinical queries       |
| 4.   | Exploratory Analysis          | Examine risk distributions and demographic trends          |
| 5.   | Clinical Correlation Analysis | Analyze relationships between vital signs                  |
| 6.   | Risk Factor Modeling          | Train a classifier to predict maternal risk levels         |
| 7.   | Risk Metrics                  | Construct a maternal risk scoring system                   |
| 8.   | Patient Segmentation          | Identify maternal health profiles using clustering         |
| 9.   | Executive Summary             | Summarize key insights and implications                    |

---

# Notebook Setup

## Steps 1-3 have been uploaded in an HTML and Ipynb file.

---
# 4. Exploratory Analysis:

## Examine risk distributions and demographic trends
Initial exploration shows how maternal risk levels are distributed across the dataset and highlights basic demographic patterns. Visualizations suggest that risk classification varies across age and vital sign ranges, indicating that multiple physiological indicators may contribute to maternal risk.

---

# 5. Clinical Correlation Analysis:

## Analyze relationships between vital signs

Correlation analysis reveals relationships between physiological indicators, particularly between systolic and diastolic blood pressure. Elevated blood pressure levels appear more frequently within higher risk classifications, suggesting cardiovascular indicators play a meaningful role in maternal risk assessment.

---

# 6. Risk Factor Modeling

## Train a classifier to predict maternal risk levels

A Random Forest classifier was trained to predict maternal risk categories using physiological indicators. The model demonstrates that maternal risk classification can be predicted using features such as blood pressure, blood sugar, heart rate, and body temperature.

---

# 7. Risk Metrics

## Construct a maternal risk scoring system

A composite maternal risk score was created by combining key physiological indicators into a single metric. The resulting score produces distinct averages across risk groups, providing a simplified representation of maternal health risk.

---

# 8. Patient Profile Segmentation

## Identify maternal health profiles using clustering

Clustering analysis groups patients with similar physiological characteristics. The results reveal distinct maternal health profiles, suggesting that different combinations of clinical indicators correspond to different risk patterns.

# Results Snapshot:

- This analysis identified several physiological indicators associated with maternal health risk classification.

## Key findings: 

* Higher systolic and diastolic blood pressure levels appear more frequently among high-risk pregnancies.

* Elevated blood sugar is associated with increased maternal risk classification.

* The classification model demonstrates that maternal risk levels can be predicted using combinations of physiological indicators.

* Clustering analysis reveals distinct maternal health profiles, suggesting that risk arises from multiple interacting factors rather than a single indicator.

# 9. Executive Summary

Conclusions from the analysis:
* Elevated **blood sugar levels** and **systolic blood pressure** are strongly associated with high maternal risk classifications.
* Older maternal age groups demonstrate a higher concentration of elevated risk levels.
* Machine learning classification models can effectively predict maternal risk categories using physiological indicators.
* Clustering analysis reveals distinct maternal health profiles, indicating that risk is often driven by combinations of clinical factors rather than individual indicators alone.

## Key Techniques:

* This project demonstrates several analytical and machine learning techniques commonly used in data science workflows:

* Exploratory Data Analysis (EDA) using statistical summaries and visualizations

* SQL-based analytical querying using SQLite

* Correlation analysis for identifying relationships between variables

* Feature engineering and data preprocessing

* Supervised machine learning using Random Forest classification

* Feature importance analysis for model interpretability

* Composite risk score development

* Unsupervised clustering using K-Means for patient segmentation
