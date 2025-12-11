# 🚕 Project 6 - Build a Random Forest Model

## 📘 Overview
This project is part of the Automatidata track in the Google Advanced Data Analytics Certificate Program. In this scenario, Automatidata is a consulting firm engaged by the New York City Taxi & Limousine Commission (TLC). TLC has developed a successful regression model that predicts cab fares.

TLC wants to create an app that allows taxicab drivers to see whether a customer will leave a higher tip. Automatidata is tasked with developing a Random Forest classication model to determine whether a customer will leave a generous tip (above 20%). Data from the previous project will be joined with the TLC dataset to predict the tip percentage. The random forest model will be compared to a XGBoost model where 80% of the data will be used for training and 20% for validation scores.

## 📄 PACE Strategy Document

The PACE document outlines the strategic framework for approaching the project. It breaks down the workflow into four phases:

1. Set up a Python notebook for the TLC dataset to build a random forest classification model and XGBoost 
2. Perform EDA to change datatypes and concatenate datasets prior to precessing and modeling
3. Preprocess the dataset and create new features and target variable for tip percentage called `generous`
4. Leverage the scikit-learn and XGBoost libraries to create a random forest model and a XGBoost model and compare model test scores.

This document serves as a roadmap to planning the data, analyzing data relationships and key features, and providing findings on the dataset.

## 📄 Executive Summary

Key insights from the data modeling include:
1. The random forest model outperformed the XGBoost model
2. The features that removed the most impurity from the model were based on vendor ID, passenger count, and predicted fare amount
3. The random forest model produced an f1 score of 0.702 on the test data and the highest error it made was a Type I error in falsely predicting higher tip percentages
4. It is recommended that TLC finds more features that are predictive of the target as most of the features were dropped to avoid data leakage
5. Taxicab drivers should be aware that an app leveraging a deployed model will not always correctly determine a higher tip percentage

## 📄 Automatidata Lab Notebook
The project_6_Automatidata_lab.ipynb file contains the data modeling process on the TLC dataset

## 📄 Dependencies
- pandas==2.3.1
- numpy==2.3.2
- scikit-learn==1.7.1
- matplotlib==3.10.5
- xgboost==3.0.3

  ## 📘 Getting Started
1. **Clone the repository branch into a project folder in VSCode**
```
git clone --branch project-6-build-a-random-forest-model --single-branch https://github.com/Cameron-Nann-Python/Google-Advanced-Data-Analytics-Projects.git
```
2. **Navigate to the project folder and create a virtual environment**
```
# Ran on Python3.13
cd Google-Advanced-Data-Analytics-Projects
python -m venv venv

# activate the virtual environment
venv\Scripts\activate # Windows
```
3. **Install dependencies**
```
pip install pandas==2.3.1 numpy==2.3.2 scikit-learn==1.7.1 matplotlib==3.10.5 xgboost==3.0.3 ipykernel
```
4. **Open notebook and review documents as needed**
- Open lab notebook `project_6_Automatidata_lab.ipynb` and select the virtual environment for the kernel
- Either change the location of the csv or put "csv/" when loading each dataset (Windows) into a DataFrame
- Review `pdf` folder to better understand workflow

## 📂 Files Included
- `2017_Yellow_Tax_Trip_Data.csv`: TLC taxicab dataset
- `project_6_PACE_strategy.pdf`: guide for project workflow
- `project_6_executive_summary.pdf`: overview of analysis and next actions
- `project_6_Automatidata_lab.ipynb`: data modeling lab notebook
- 'nyc_preds_means.csv`: dataset holding predicting and transformed feature columns from past project
