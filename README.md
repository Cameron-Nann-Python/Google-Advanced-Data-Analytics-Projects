# 🚕 Project 2 - Preliminary Data Analysis

## 📘 Overview
This project is part of the Automatidata track in the Google Advanced Data Analytics Certificate Program. In this scenario, Automatidata is a consulting firm engaged by the New York City Taxi & Limousine Commission (TLC). TLC seeks to develop a regression model that predicts taxi fares before a ride begins, enabling greater transparency and customer trust.

TLC has provided a dataset of taxicab trip information to Automatidata for analysis. The project supervisor, Deshawn Washington, has requested a Jupyter notebook that performs preliminary data cleaning. A senior data analyst, Luana Rodriguez, has asked for a summary of the dataset, including:
- Column data types
- Non-null value counts
- Identification of relevant and irrelevant columns
- Other notable data characteristics

## 📄 PACE Strategy Document
The PACE document outlines the strategic framework for approaching the project. It breaks down the workflow into two phases:

1. Set up a Jupyter notebook for the TLC dataset to perform preliminary data analysis
2. Review the dataset and provide the information requested by the senior data analyst

This document serves as a roadmap to planning the data, analyzing data relationships and key features, and providing findings on the dataset.

## 📑 Executive Summary
Key insights from the preliminary analysis include:

1. **Trip distance** and **total fare paid** emerged as the most informative variables for simulating taxi rides.  
2. The dataset contains outliers, including trips with zero distance and negative fare amounts.  
3. Recommended next steps include thorough data cleaning and statistical analysis to prepare the dataset for modeling.

## 📑 Automatidata Lab Notebook
The `project_2_Automatidata_lab.ipynb` file contains the full preliminary data analysis on the TLC dataset

## 📑 Dependencies
- pandas==2.3.1
- numpy==2.3.2

## 📘 Getting Started

1. **Clone the repository**
```
git clone https://github.com/Cameron-Nann-Python/Google-Advanced-Data-Analytics-Projects.git
```
2. **Create a project folder and a virtual environment**
```
# Ran on Python3.13
mkdir project_preliminary_analysis
python -m venv venv
venv\Scripts\activate # Windows
```
3. **Install dependencies**
```
pip install pandas==2.3.1 numpy==2.3.2 ipykernel
```
4. **Open notebook in VSCode**
- Open VSCode
- Open lab notebook `project_2_Automatidata_lab.ipynb` and select the virtual environment for kernel

### 📂 Files Included
- `2017_Yellow_Taxi_Trip_Data.csv`: TLC taxicab dataset
- `project_2_PACE_strategy.pdf`: guide for project workflow 
- `project_2_executive_summary.pdf`: overview of analysis results and next actions
- `project_2_Automatidata_lab.ipynb`: preliminary data analysis lab notebook
