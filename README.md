# BRFSS--Heart-attack-prediction
![Heart attack](https://www.emergencyphysicians.org/siteassets/emphysicians/all-images/kwtg/heart-attack.jpg)

## Project Overview
This project aims to develop a machine learning model to predict the risk of heart attacks, utilizing data from the 2011 Behavioral Risk Factor Surveillance System (BRFSS). Given the high incidence and serious consequences of heart attacks—occurring every 40 seconds in the United States—it is essential to develop effective predictive tools to identify risk factors and improve preventive interventions.

The BRFSS is the leading telephone survey system in the United States that collects state data on health risk behaviors, chronic health conditions, and use of preventive services. Established in 1984, it now conducts over 400,000 interviews annually, making it the largest continuous health survey system in the world.

## Goal
By developing a predictive model for heart attack risk, this project aims to assist in the prevention and management of this critical health condition. 

## Dataset
The data used in this project is publicly available in ASCII format and has been converted into a CSV file using Python. The dataset consists of **506,467 records** and **450 variables**, including a binary target variable, **CVDINFR4**, which indicates whether an individual has ever been diagnosed with a heart attack. 

The variables are categorized into:
- Record identification variables
- Questionnaire variables
- Computed variables

Special attention has been paid to the issue of unbalanced data due to the health-medical nature of the dataset.

## Methodology
The project was carried out using the KNIME software, incorporating official extensions such as H2O and Python. The typical machine learning procedure followed includes:
1. Data Reading: Importing the dataset into the KNIME environment.
2. Data Wrangling: Cleaning and preparing the data for analysis.
3. Exploration: Analyzing the dataset to identify patterns and insights.
4. Transformation: Preparing the data for model training.
5. Analysis: Learning from the data, making predictions, and scoring the results.

