# Cancer Onset Prediction Using Machine Learning

## Project Overview

This project investigates the application of mathematical modelling and machine learning to cancer onset prediction using historical outpatient data from Lagos State University Teaching Hospital (LASUTH), Nigeria.

The study evaluates three classification algorithms Naïve Bayes (NB), Logistic Regression (LR), and k Nearest Neighbours (kNN)to examine their effectiveness in classifying cancer cases using demographic and clinical variables. The models were evaluated using a 15 year dataset comprising over 1,700 patient records.

## Research Objectives

- Investigate the application of mathematical modelling to healthcare analytics.
- Develop and evaluate machine learning models for cancer onset prediction.
- Compare model performance using accuracy, precision, recall, F1score, and ROC-AUC.
- Examine the strengths and limitations of different classification algorithms in healthcare research.

## Models Evaluated

### 1. Logistic Regression (LR)

Logistic Regression demonstrated balanced and interpretable performance, achieving an ROC-AUC of 0.89 in the original analysis.

### 2. Naïve Bayes (NB)

Naïve Bayes achieved the highest recall of 86% in the original analysis, highlighting its potential relevance for further investigation in screening oriented research.

### 3. k Nearest Neighbours (kNN)

kNN was evaluated as an additional classification approach. Its performance was comparatively weaker in this study. Sensitivity to noise and the representation of categorical variables were identified as relevant considerations.

## Evaluation Metrics

The models were assessed using the following metrics:

- Accuracy
- Precision
- Recall
- F1 score
- ROC-AUC

## Model Performance and Key Findings

The study compared Logistic Regression, Naïve Bayes, and k Nearest Neighbours using historical patient data from LASUTH.

### Logistic Regression (LR)

- **Accuracy:** 84%
- **Precision:** 86%
- **Recall:** 82%
- **F1 score:** 84%
- **ROC-AUC:** 0.89

Logistic Regression achieved the most balanced overall performance among the evaluated models.

### Naïve Bayes (NB)

- **Recall:** 86%
- **Precision:** 79%

Naïve Bayes achieved the highest recall among the evaluated models.

### k Nearest Neighbours (kNN)

- **Accuracy:** 78%
- **Precision:** 76%
- **Recall:** 79%
- **F1 score:** 77%
- **ROC-AUC:** 0.83

kNN recorded comparatively weaker performance, suggesting that preprocessing and feature representation warrant further investigation.

### Comparative Findings

- **Logistic Regression:** Best balanced overall performance among the evaluated models.
- **Naïve Bayes:** Highest recall among the evaluated models.
- **k-NN:** Comparatively weaker performance in this study.

These results reflect the original analysis and do not establish that any model is suitable for clinical diagnosis or screening.

## Tools and Technologies

- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit learn
- Matplotlib
- Seaborn

## Repository Contents

- `cancer_onset_prediction.ipynb` Jupyter Notebook containing the modelling workflow, analysis, visualisations, and results.
- `requirements.txt`  Python dependencies required to support the analysis.

## Dataset and Reproducibility

The original dataset comprises over 1,700 outpatient records spanning 15 years. The dataset is not included in this repository.

Reproducing the original analysis requires authorised access to the dataset and the necessary Python environment. Patient confidentiality and applicable data protection requirements must be respected.

## Research Significance

This project demonstrates the application of probability theory, statistical learning, and comparative machine learning to healthcare analytics. The findings highlight the importance of model selection, data preprocessing, performance evaluation, and ethical considerations in predictive healthcare research.

Potential future work could explore ensemble learning methods, improved feature engineering, multicentre datasets, and external validation to assess whether the findings generalise to other patient populations.

## Disclaimer

This repository is intended for research and educational purposes. The models are not presented as clinically validated diagnostic or screening tools and should not be used to make medical decisions.
