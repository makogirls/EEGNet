# Diagnosis of Epileptic Seizure and Tumor with EEG Classification

This repository details the project for the 2023 Yonsei University Digital Healthcare Bootcamp (2023/01/16-2023/01/18).
The project's aim was to diagnose epileptic seizures and tumors using EEG signal classification.

## Motivation
The background of this project lies in the significance of EEG (Electroencephalogram) signals in the early detection and diagnosis of epileptic seizures and brain tumors. Despite the complexities and noise present in EEG data, the development of robust models for analysis and visualization can enhance diagnostic accuracy.

## Dataset Overview and Preprocessing
The dataset utilized for this study is sourced from [Kaggle's Epileptic Seizure Recognition Dataset](https://www.kaggle.com/datasets/harunshimanto/epileptic-seizure-recognition). The dataset consists of EEG readings categorized into five sets representing different brain activity states. 

### Data Understanding and Initial Processing
The initial dataset consists of 23 measurements per 500 subjects, with 178 EEG features recorded in microvolts (uV). The classes are distributed as follows:
- Class 1: Epileptic Seizure state
- Class 2: Brain tumor patients' tumor region
- Class 3: Brain tumor patients' non-tumor region
- Class 4: Normal Eyes Closed state
- Class 5: Normal Eyes Open state

### Data Extraction and Transformation
Classes were balanced, and the dataset was randomized to avoid biases in the training results.

### Data Visualization and Preprocessing Techniques
- Pearson Correlation Coefficient visualization to understand feature correlations
- Z-Score Normalization for data uniformity
- Principal Component Analysis (PCA) for dimensionality reduction

## Model Selection
A variety of machine learning models were trained and tested, maintaining the class ratio within the split of training and test sets. Models included Support Vector Machine, Logistic Regression, Multilayer Perceptron, Gaussian Process Regression, and KNN (k-Nearest Neighbors).

## Visualization
Results were visualized to synthesize the performances of various models on both seizure and tumor data.

## Conclusions
The project team implemented several strategies to enhance model accuracy:
- Data preprocessing improvements
- Hyperparameter tuning with machine learning models
- Cross-validation techniques
