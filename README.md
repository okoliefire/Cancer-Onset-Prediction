# Cancer Onset Prediction Using Machine Learning

## Project Overview

This project investigates the application of mathematical modelling and machine learning to cancer onset prediction using historical outpatient data from Lagos State University Teaching Hospital (LASUTH), Nigeria.

The study evaluates three classification algorithms—Naïve Bayes (NB), Logistic Regression (LR), and k-Nearest Neighbours (k-NN)—to examine their effectiveness in classifying cancer cases using demographic and clinical variables. The models were evaluated using a 15-year dataset comprising over 1,700 patient records.

## Research Objectives

- Investigate the application of mathematical modelling to healthcare analytics.
- Develop and evaluate machine learning models for cancer onset prediction.
- Compare model performance using accuracy, precision, recall, F1-score, and ROC-AUC.
- Examine the strengths and limitations of different classification algorithms in healthcare research.

## Models Evaluated

### 1. Logistic Regression (LR)

Achieved an ROC-AUC of 0.89 in the original analysis and demonstrated balanced and interpretable performance among the evaluated models.

### 2. Naïve Bayes (NB)

Achieved the highest recall of 86% in the original analysis, highlighting its potential relevance to screening-oriented research where identifying positive cases is important.

### 3. k-Nearest Neighbours (k-NN)

Was also evaluated as a classification approach. Its performance was comparatively weaker in this study. Sensitivity to noise and the representation of categorical variables were identified as relevant considerations.

## Evaluation Metrics

The models were assessed using the following metrics:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

## Tools and Technologies

- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn

## Repository Contents

- `cancer_onset_prediction.ipynb` — Jupyter Notebook containing the modelling and analysis workflow.

## Dataset and Reproducibility

The original dataset comprises over 1,700 outpatient records spanning 15 years. The dataset is not included in this repository. Reproducing the original analysis requires authorised access to the data and the necessary Python environment.

## Research Significance

This project demonstrates the application of probability theory, statistical learning, and comparative machine learning to healthcare analytics. The findings highlight the importance of model selection, data preprocessing, performance evaluation, and ethical considerations in developing predictive approaches for healthcare research.

The reported results reflect the original study and should not be interpreted as evidence of clinical validation or readiness for medical decision-making.

## Disclaimer

This repository is intended for research and educational purposes. The models are not presented as clinically validated diagnostic or screening tools.
