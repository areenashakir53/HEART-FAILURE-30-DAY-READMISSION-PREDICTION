# Heart Failure 30-Day Readmission Prediction

## Project Overview

This project focuses on predicting whether a patient will be readmitted to the hospital within 30 days after a heart-failure-related hospitalization using machine learning.

The goal is to explore patient information, train classification models, compare their performance, and understand how well they generalize to unseen data.

## Problem Statement

Hospital readmissions can increase healthcare costs and affect patient outcomes. Machine learning may help identify patients at higher risk of readmission so healthcare teams can investigate opportunities for better follow-up care and discharge planning.

This project is an educational machine-learning exercise and is not intended for clinical decision-making.

## Project Objectives

- Explore and understand the heart failure patient dataset.
- Prepare the data for machine learning.
- Identify the target variable and exclude unsuitable columns.
- Train and compare three classification models.
- Evaluate model performance using multiple metrics.
- Examine potential overfitting and underfitting.
- Identify the most suitable model based on evaluation results.

## Dataset and Target Variable

The target variable is `Readmitted_30_Days`, which represents whether a patient was readmitted within 30 days.

The project uses 34 predictor features covering patient demographics, lifestyle, medical history, clinical measurements, hospitalization details, and medication information.

`Patient_ID` is excluded from the predictors because it is an identifier rather than a clinical predictor.

## Machine Learning Models

The project compares three classification algorithms:

1. **Logistic Regression** — a baseline model for binary classification.
2. **K-Nearest Neighbors (KNN)** — predicts a class using nearby data points.
3. **Decision Tree** — predicts a class using a sequence of decision rules.

## Project Workflow

1. Load and explore the dataset.
2. Inspect data types, missing values, duplicates, and target distribution.
3. Prepare categorical and numerical features.
4. Split the data into training and testing sets.
5. Train the three classification models.
6. Evaluate training and testing performance.
7. Compare the models and investigate overfitting or underfitting.
8. Interpret the results and identify limitations.

## Evaluation Metrics

The models are evaluated using:

- **Accuracy:** Overall proportion of correct predictions.
- **Precision:** How many predicted readmissions were actual readmissions.
- **Recall:** How many actual readmissions were identified.
- **F1-score:** A balance between precision and recall.
- **ROC-AUC:** How well the model distinguishes between the two classes.

Confusion matrices and model comparison visualizations can also help explain model performance.

## Repository Contents

- `Heart_Failure_Readmission_Prediction.ipynb` — Jupyter notebook containing the project code and analysis.
- `Heart Failure Readmission Project.docx` — Written project report.
- `README.md` — Project overview and documentation.

## Results

The three models should be compared using their actual evaluation results. The best model should be selected based on multiple metrics, generalization performance, and the healthcare context rather than accuracy alone.

*Add the final model comparison table and best-model conclusion here after verifying the results in the notebook.*

## Limitations

- Model performance depends on the quality and representativeness of the dataset.
- Class imbalance may affect the evaluation results.
- Potential data leakage must be investigated carefully.
- Performance on one dataset does not guarantee performance in other hospitals or patient populations.
- Clinical validation and additional testing would be necessary before any real-world use.

## Conclusion

This project demonstrates a machine-learning workflow for a healthcare classification problem, from data preparation and model training to evaluation and comparison. It highlights the importance of selecting models using multiple performance metrics and carefully assessing their limitations.

---

**Project:** Heart Failure 30-Day Readmission Prediction  
**Focus:** Machine Learning | Healthcare Analytics | Binary Classification
