# 🚕 Project 4 - Statistical Data Analysis

## 📘 Overview
This project is part of the Automatidata track in the Google Advanced Data Analytics Certificate Program. In this scenario, Automatidata is a consulting firm engaged by the New York City Taxi & Limousine Commission (TLC). TLC seeks to develop a regression model that predicts taxi fares before a ride begins, enabling greater transparency and customer trust.

Automatidata has reviewed the TLC taxicab dataset, and is looking to increase earnings for taxicab drivers, which is captured by the variable `fare_amount`. There are multiple payment methods, stored in a variable `payment_type`, that appear to influence the fare amount paid by the customer, and the current responsibility of my role is to determine if there is a statistically significant relationship between `fare_amount` and `payment_type`

## 📄 PACE Strategy Document:

The PACE document outlines the strategic framework for approaching the project. It breaks down the workflow into four phases:

1. Set up a Python notebook for the TLC dataset to perform statistical analysis
2. Perform EDA to clean dataset prior to analysis
3. Conduct an A/B test determine the effect of average credit card payments on fare amount vs average cash payments on fare amount
4. Use hypothesis testing to formualte a two-sample t-test with random sampling to determine whether there is a statically significant difference between the average credit card and cash payment

This document serves as a roadmap to planning the data, analyzing data relationships and key features, and providing findings on the dataset. 

## 📄 Executive Summary
Key insights from the statistical data analysis include:
1. The A/B test rejected the null hypothesis that there was no difference between the average credit card and cash payments.
2. Average fare amounts for credit card users were signficantly higher than those for cash users.
3. Recommended action is to encourage taxicab drivers to accept credit card payments to increase fare amount earned.

## 📄 Automatidata Lab Notebook
The `project_4_Automatidata_lab.ipynb` file contains the full statistical data analysis on the TLC dataset

## 📄 Dependencies
- pandas==2.3.1
- numpy==2.3.2
- scipy==1.16.1

## 📘 Getting Started
1. **Install Anaconda Navigator and create a virtual environment with Conda**

2. **Install the Jupyter Extension in VS Code, select the Conda environment as the kernel, and install the ipykernel package**
- The package will automatically request to be installed in VS Code when trying to running a cell in a .ipynb file

```
3. **Install dependencies**
```
pip install pandas==2.3.1 numpy==2.3.2 scipy==1.16.1 ipykernel
```

4. **Open notebook and review documents as needed**
- Open lab notebook `project_4_Automatidata_lab.ipynb` and select the virtual environment for kernel
- Review `pdf` folder to better understand workflow

### 📂 Files Included
- `2017_Yellow_Tax_Trip_Data.csv`: TLC taxicab dataset
- `project_4_PACE_strategy.pdf`: guide for project workflow
- `project_4_executive_summary.pdf`: overview of analysis and next actions
- `project_4_Automatidata_lab.ipynb`: statistical data analysis lab notebook


