# Delaney-With-Descriptors
## Predicting Aqueous Solubility Using Machine Learning (Delaney Dataset)

## Overview

This project applies machine learning techniques to predict the aqueous solubility of chemical compounds using the Delaney dataset. The goal is to develop a predictive model that can assist in drug discovery and materials science by estimating solubility based on molecular properties.

## Dataset Description

The Delaney dataset contains molecular structures and their corresponding aqueous solubility values (logS). The dataset includes:

SMILES representations of chemical compounds

Molecular descriptors (e.g., molecular weight, polar surface area)

Experimental solubility values


## Project Workflow

1. Data Preprocessing

Conversion of SMILES strings to molecular descriptors

Feature engineering (e.g., molecular weight, logP, hydrogen bond donors/acceptors)

Handling missing values and scaling numerical features


 2. Exploratory Data Analysis (EDA)

Distribution of solubility values

Correlation analysis of molecular descriptors

Visualization of molecular properties



3. Model Development

Applied regression models:

Linear Regression

Support Vector Machine (SVM)


Hyperparameter tuning using GridSearchCV



4. Model Evaluation

Performance metrics: RMSE, R², MAE

Comparison of model predictions vs. actual solubility values



## 5. Recommendations

Feature Importance Analysis: Identified key molecular descriptors influencing solubility

Improved Predictions: Ensembled models performed better than single regressors

Further Enhancements:

Use deep learning models for feature extraction

Expand dataset with additional molecular properties

Experiment with transfer learning from chemical databases





## Technologies Used

Python (Pandas, NumPy, Scikit-learn, RDKit for molecular processing)

Jupyter Notebook

Matplotlib & Seaborn for visualization


Conclusion

The project successfully demonstrates how machine learning can predict aqueous solubility from molecular structures. The best-performing model provides accurate estimations, supporting applications in drug formulation and material science.

Repository Structure

How to Use

1. Clone the repository:

git clone https://github.com/onyedika39/Delaney-With-Descriptors



Future Work

Implement deep learning approaches e.g. graph neural networks

Integrate additional chemical datasets

Deploy a web-based solubility predictor
