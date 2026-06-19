# Breast Cancer Classification

This project focuses on predicting whether a breast tumor is **benign** or **malignant** using the Breast Cancer Wisconsin Diagnostic dataset.

## Project Overview

The main goal is to build and evaluate machine learning models that can accurately classify tumors based on various cell nucleus measurements. The project includes:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Feature selection and engineering
* Model training and evaluation
* Hyperparameter tuning
* Model interpretation using feature importance and SHAP

## Dataset

The dataset contains 569 samples and 30 numerical features extracted from digitized images of breast mass cell nuclei.

Target classes:

* **M** = Malignant
* **B** = Benign

## Models Used

Some of the models explored in this project include:

* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest
* Gradient Boosting
* XGBoost (optional)

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

Since this is a medical classification problem, special attention was given to **recall**, as missing a malignant case can have serious consequences.

## Results

The best-performing models achieved very high classification performance, demonstrating that the dataset is well-suited for machine learning applications.

## Tools & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Optuna
* SHAP

## Future Improvements

* Model stacking and ensembling
* Probability calibration
* Deployment with FastAPI
* Model monitoring and drift detection

---

This project was completed as part of a machine learning learning journey focused on developing practical skills in data preprocessing, model building, optimization, and interpretability.

