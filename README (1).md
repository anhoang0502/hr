# Employee Attrition Prediction

## Project Overview
This project contains a Jupyter Notebook designed to analyze and predict employee attrition. The project utilizes various machine learning techniques, with a focus on Naive Bayes classifiers, and employs advanced data balancing strategies to handle imbalanced target variables.

## Dataset
The analysis is conducted using the dataset file named `employee_attrition_dataset_10000 (1).csv`. This dataset comprises 10,000 employee records across 26 distinct features, including demographics, job role, monthly income, performance rating, work-life balance, and the final attrition status.

## Methodology
The notebook follows a comprehensive data science pipeline:
1. Setup and Data Loading: Importing required libraries and reading the dataset.
2. Data Preprocessing: Scaling features using MinMaxScaler and structuring the data for modeling.
3. Resampling Imbalanced Data: Utilizing techniques such as SMOTE, Edited Nearest Neighbours (ENN), and SMOTEENN to ensure robust model training.
4. Modeling: Implementing and evaluating multiple Naive Bayes algorithms (Bernoulli, Complement, Gaussian, and Multinomial).
5. Evaluation: Assessing model performance using accuracy scores, confusion matrices, and imbalanced classification reports.

## Dashboard
To view the interactive dashboard for this project, please open the `NHÓM-4_DASHBOARD.pbix` file using Microsoft Power BI.

## Prerequisites
To execute the notebook, ensure the following Python libraries are installed:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn
