# Diabetes Prediction: Model Exploration

**A notebook study in preparing, comparing, and evaluating classifiers on a public diabetes dataset.** This project documents a complete machine-learning experiment, from data exploration to model evaluation.

[Open the notebook](https://github.com/AhmedMagdi2003/GTC_ML_Project_2_Diabetes_Prediction_Model/blob/main/Notebook.ipynb) · [View the repository](https://github.com/AhmedMagdi2003/GTC_ML_Project_2_Diabetes_Prediction_Model)

## The project

The goal is to examine how preprocessing, feature transformations, class balancing, and model selection affect a binary classification task on the Pima Indians diabetes dataset. It is intended for learning and experimentation, not clinical use.

## What the notebook explores

- Exploratory review of the dataset and selected measurements.
- Handling zero values used as missing-value proxies in some fields.
- Derived age and BMI group features.
- Class balancing with SMOTE and model selection using cross-validation.
- Comparison of Support Vector Machine and Gradient Boosting classifiers with classification metrics and plots.

## Explore the project

Open Notebook.ipynb in Jupyter or Google Colab with diabetes.csv available beside it, then run the cells in order. The repository does not include a dependency lockfile, so install the Python packages imported by the notebook in your environment.

## Built with

Python · pandas · NumPy · scikit-learn · imbalanced-learn · Jupyter

## Data and responsible use

The included dataset is limited in size and population coverage. Its patterns should not be generalized to other populations without appropriate evidence. This project is not a diagnostic tool and must not be used to make medical decisions. Review the notebook's split, cross-validation, preprocessing, and resampling placement before interpreting or comparing results. No unverified performance score is claimed here.

## About

Built by Ahmed Magdi as an applied machine-learning study. [Repository](https://github.com/AhmedMagdi2003/GTC_ML_Project_2_Diabetes_Prediction_Model)
