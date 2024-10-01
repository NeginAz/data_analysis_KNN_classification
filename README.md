# Data Analysis and KNN Classification

This project focuses on applying data analysis techniques and k-NN classification to two datasets: the Iris dataset and the Heart Disease dataset. The goal is to explore the datasets, clean the data, perform normalization, and evaluate model performance using k-NN classification with various tuning and validation methods.

### Datasets

Iris Dataset:
A benchmark dataset for machine learning algorithms. It includes features of three Iris flower species: Setosa, Versicolor, and Virginica. The dataset has 4 attributes and 150 instances.
Heart Disease Dataset:
This dataset includes 14 features and 303 instances, with the classification target being the presence or absence of heart disease (binary classification: 0 or 1).
Objectives

### Data Exploration: 
Clean the data, deal with missing values, and perform normalization (min-max and z-score). Generate exploratory visualizations such as pair plots and calculate statistical properties like mean, variance, skew, and kurtosis.
### KNN Classification:
Train and evaluate KNN classifiers on both datasets.
Perform parameter tuning using cross-validation and report the best-performing k value.
Compare weighted k-NN methods and explore alternative distance metrics.

## Methods

### Data Cleaning: 
Handled missing values using interpolation, approximations, and smoothing.
Exploratory Plots: Generated pair plots for feature exploration and used correlation coefficients to identify feature relationships.
Model Training & Validation:
Iris Dataset: Applied 5-fold cross-validation.
Heart Disease Dataset: Used train-validate-test split (80%-10%-10%) for model tuning.
### Performance Evaluation: 
Assessed classification accuracy, AUC, and F-score.
Results

Best k-value was determined for each dataset, leading to improved classification accuracy.
Analysis of weighted KNN methods showed advantages in certain distance metrics.
Explored different algorithms for KNN to optimize speed and performance.

### Tools and Libraries

Python: Used for implementing the project.
Libraries:
pandas: For data manipulation and cleaning.
numpy: For numerical calculations.
seaborn and matplotlib: For data visualization.
scikit-learn: For implementing KNN classification, cross-validation, and performance metrics.
Usage

To run the project, ensure you have the required libraries installed:

```console
pip install pandas numpy matplotlib seaborn scikit-learn
```
Run the notebook or script files to see the full analysis and KNN classification process.
