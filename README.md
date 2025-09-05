# 🚕 Project 3 - Exploratory Data Analysis

## 📘 Overview
This project is part of the Automatidata track in the Google Advanced Data Analytics Certificate Program. In this scenario, Automatidata is a consulting firm engaged by the New York City Taxi & Limousine Commission (TLC). TLC seeks to develop a regression model that predicts taxi fares before a ride begins, enabling greater transparency and customer trust.

TLC has provided a dataset of taxicab rides. The Automatidata project manager, Deshawn Washington, has requested a Python notebook showing the structuring and cleaning of this dataset with visualizations to show data relationships. The management team requested a Tableau visualization of the most import relationship for non-technical stakeholders. 

## 📄 PACE Strategy Document
The PACE document outlines the strategic framework for approaching the project. It breaks down the workflow into three phases:

1. Set up a Python notebook for the TLC dataset to perform explorary data analysis
2. Create data visualizations for technical and non-technical stakeholders
3. Create an executive summary to share results

This document serves as a roadmap to planning the data, analyzing data relationships and key features, and providing findings on the dataset.

## 📄 Executive Summary
Key insights from the exploratory data analysis include:
1. Variables **trip_distance** and **total_amount**, representing the taxicab ride duration and total fee paid respectively, were the most significant features to predict the target.
2. Issues with the data arose in the form of outliers and invalid data entries.
3. Recommended actions include robust data cleaning, removal of outliers, and removal of insignificant features from the dataset.
## 📈 Tableau Public Visualization

The following visualization shows the relationship between two features that best represent a taxi ride,`Trip Distance` and  `Total Amount`:

<div class='tableauPlaceholder' id='viz1757023252382' style='position: relative'><noscript><a href='#'><img alt='Trip Distance vs Total Amount 2017 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Au&#47;AutomatidataVisualizations&#47;trip_distance_total_amount_2017&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='AutomatidataVisualizations&#47;trip_distance_total_amount_2017' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Au&#47;AutomatidataVisualizations&#47;trip_distance_total_amount_2017&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>

The visualization can be accessed at the link provided below:
https://public.tableau.com/app/profile/cameron.nann/viz/AutomatidataVisualizations/trip_distance_total_amount_2017

## 📄Automatidata Lab Notebook
The `project_3_Automatidata_lab.ipynb` file contains the full exploratory data analysis on the TLC dataset

## 📄 Dependencies
- pandas==2.3.1
- numpy==2.3.2
- matplotlib==3.10.5
- seaborn==0.13.2
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
pip install pandas==2.3.1 numpy==2.3.2 maplotlib==3.10.5 seaborn==0.13.2 ipykernel
```
4.  **Create the csv folder**
```
mkdir input
```
5. **Open notebook in VSCode**
- Open VSCode
- Open lab notebook `project_3_Automatidata_lab.ipynb` and select the virtual environment for kernel


### 📂 Files Included
- `2017_Yellow_Taxi_Trip_Data.csv`: TLC taxicab dataset
- `project_3_PACE_strategy.pdf`: guide for project workflow
- `project_3_executive_summary.pdf`: overview of analysis and next actions
- `project_3_Automatidata_lab.ipynb`: exploratory data analysis lab notebook
