# 🚕 Project 5 - Build a Multiple Linear Regression Model

## 📘 Overview
This project is part of the Automatidata track in the Google Advanced Data Analytics Certificate Program. In this scenario, Automatidata is a consulting firm engaged by the New York City Taxi & Limousine Commission (TLC). TLC seeks to develop a regression model that predicts taxi fares before a ride begins, enabling greater transparency and customer trust.

Automatidata has reviewed the TLC taxicab dataset, and is looking to increase earnings for taxicab drivers, which is captured by the variable fare_amount. Automatidata is preparing to construct a multiple linear regression model for the TLC taxicab dataset and the current responsibility of my role is to perform EDA, preprocess the data, and build a regression model.

## 📄 PACE Strategy Document

The PACE document outlines the strategic framework for approaching the project. It breaks down the workflow into four phases:

1. Set up a Python notebook for the TLC dataset to build a multiple linear regression model
2. Perform EDA to clean dataset prior to precessing and modeling
3. Preprocess the dataset and create new predictor columns
4. Leverage the scikit-learn library to create a regression model and explore model results

This document serves as a roadmap to planning the data, analyzing data relationships and key features, and providing findings on the dataset.

## 📄 Executive Summary

Key insights from the data modeling include:
1. The model was able to explain 87& of the variance of the test data
2. The mean absolute error for the test data was $2, inferring that the predicted values deviated from the true values by $2
3. `mean_distance` was a newly created variable that had the greatest effect on predicting the target variable `fare_amount`
4. The recommended next steps are to find ways to improve model performance and to encourage taxicab drivers to prioritize routes with longer distances to maximize earnings

## 📄 Automatidata Lab Notebook
The project_5_Automatidata_lab.ipynb file contains the data modeling process on the TLC dataset

## 📄 Dependencies
- pandas==2.3.1
- numpy==2.3.2
- scikit-learn==1.7.1
- matplotlib==3.10.5
- seaborn==0.13.2
  
## 📘 Getting Started
1. **Clone the repository branch into a project folder in VSCode**
```
git clone --branch project-5-build-a-multiple-linear-regression-model --single-branch https://github.com/Cameron-Nann-Python/Google-Advanced-Data-Analytics-Projects.git
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
pip install pandas==2.3.1 numpy==2.3.2 scikit-learn==1.7.1 matplotlib==3.10.5 seaborn==0.13.2 ipykernel
```

4. **Open notebook and review documents as needed**
- Open lab notebook `project_4_Automatidata_lab.ipynb` and select the virtual environment for kernel
- Either change the location of the csv or put "csv/" when loading dataset (Windows)
- Review `pdf` folder to better understand workflow
## 📂 Files Included
- `2017_Yellow_Tax_Trip_Data.csv`: TLC taxicab dataset
- `project_5_PACE_strategy.pdf`: guide for project workflow
- `project_5_executive_summary.pdf`: overview of analysis and next actions
- `project_5_Automatidata_lab.ipynb`: data modeling lab notebook

