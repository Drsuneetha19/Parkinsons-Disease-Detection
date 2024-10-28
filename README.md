# Parkinsons-Disease-Detection
Title: Parkinsons Disease Data Set
Abstract: Oxford Parkinson's Disease Detection Dataset

# Parkinson's Disease Detection Using Machine Learning

This repository contains a machine learning project focused on detecting Parkinson's disease based on vocal frequency features. The study involves data preprocessing, statistical analysis, and machine learning model development to differentiate between Parkinson's-affected individuals and healthy controls.

## Project Overview

Parkinson's disease affects motor functions and often leads to changes in vocal characteristics. This project utilizes a dataset of vocal features to classify individuals as healthy or having Parkinson's disease. Key objectives include:
- **Data Preprocessing**: Cleaning, normalization, and feature selection.
- **Statistical Analysis**: Normality testing and group comparisons.
- **Model Training and Evaluation**: Implementing classification models, with Support Vector Machines (SVM) yielding the highest accuracy.

## Dataset

The dataset includes the following key vocal features:
- **Fundamental Frequency**: Measures like MDVP:Fo(Hz), MDVP:Fhi(Hz), MDVP:Flo(Hz)
- **Amplitude Variation**: Features such as MDVP:Jitter(%), MDVP:Shimmer
- **Nonlinear Dynamical Measures**: RPDE, DFA, and Spread measures
- **Health Status**: `status` column with labels `1` for Parkinson’s and `0` for healthy

### Data Source

The dataset is publicly available and was originally used in various Parkinson's studies. It includes data from patients diagnosed with Parkinson's disease as well as healthy individuals.

Key Methods

Shapiro-Wilk Test: Determines data normality, influencing choice of statistical tests.
Mann-Whitney U Test: Compares vocal features between groups (Parkinson's vs. healthy).
SVM Classifier: Utilized for final model, chosen based on accuracy and reliability in classification.
Results

Accuracy: The SVM classifier achieved the highest accuracy.
Statistical Significance: Vocal features showed significant differences between groups, validating the model’s predictive ability.

