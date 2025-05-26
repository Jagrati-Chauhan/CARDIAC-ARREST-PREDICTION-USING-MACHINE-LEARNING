# 🫀 Cardiac Arrest Prediction using Machine Learning

This project aims to build a predictive machine learning model to assess the risk of cardiac arrest based on patient data. The model leverages data from the NHANES dataset (1999-2016) and explores the influence of key health indicators on coronary heart disease (CHD) occurrence.

##  📊 Project Overview

Dataset: NHANES (1999-2016) – Demographic, examination, lab tests, and questionnaire data (~37,000 records)

Objective: Predict the risk of cardiac arrest (CHD) using machine learning models and identify significant contributing factors.

## 🔍 Key Features

* Data Preprocessing:
    * Merged multi-year NHANES data
    * Handled class imbalance using SMOTE and under-sampling
    * Feature selection via Chi-Square test & Random Forest importance

* Exploratory Data Analysis:
    * Visual insights: Histograms, Pie charts, Bubble plots, Scatter plot
    * Key trends in age, gender, cholesterol, uric acid, pulse rate

* Model Training & Evaluation:
    * Logistic Regression
    * Random Forest (Best model: ~91% accuracy, F1 = 0.91)
    * Gradient Boosting
    * K-Nearest Neighbors
    * Support Vector Machine

* Hypothesis Testing:
    * T-Tests for Age, Glycohemoglobin, Pulse Rate
    * Chi-Square test for Diabetes
    * Mann-Whitney U-Test for Pulse variations

## 📈 Results

| Model                  | Accuracy   | F1 Score   | AUC Score  |
| ---------------------- | ---------- | ---------- | ---------- |
| Random Forest          | **91.21%** | **0.9133** | **0.9127** |
| K-Nearest Neighbors    | 88.51%     | 0.8912     | 0.8864     |
| Gradient Boosting      | 87.50%     | 0.8766     | 0.8755     |
| Support Vector Machine | 84.74%     | 0.8495     | 0.8480     |
| Logistic Regression    | 82.34%     | 0.8257     | 0.8239     |


## 🛠️ Future Directions

* Integrate medical images (ECG, MRI) for enhanced prediction.
* Deploy the model into Electronic Health Records (EHR) systems for real-time clinical use.
* Expand the dataset with additional risk factors and test across global populations.

## 📜 License
This project is licensed under the MIT License.

## 💡 Acknowledgments

* NHANES Dataset - CDC
* Scikit-Learn, Pandas, Matplotlib, Seaborn - Core ML & data libraries
