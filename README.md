# README for Jacksonville Zoo W.I.L.D. Program Applicant Analysis

## Goal
Given the data we have on applicants and participants in the W.I.L.D. program, the goal of this project was to analyze the admissions process to help select for the applicants that would ultimately participate the most in the program.

## Source data
Source data was provided by facilitators of the W.I.L.D. program at the Jacksonville Zoo. It is kept in the /data/ directory of this repository. A detailed explanation of how we processed the data is available in the final report provided to the zoo.

## About this repository
This repository contains:
* __data/__: folder containing the data used in our analysis (note that raw data has been removed because of PII concerns)
* __data/clean/__: folder containing the processed data that feeds into our models
* __code/__: folder with the jupyter notebooks we used for data cleaning and modeling
* __code/EDA.ipynb__: jupyter notebook with the code for our exploratory data analysis
* __code/data_cleaning.ipynb__: jupyter notebook with the code for our data cleaning
* __code/linear_regression.ipynb__: jupyter notebook with the code for our linear (and ridge) regressions
* __code/logistic_regression.ipynb__: jupyter notebook with the code for our logistic regressions
* __code/model_prep.ipynb__: jupyter notebook with the code that preps our cleaned data for modeling
* __code/xgboost.ipynb__: jupyter notebook with the code for our xgboost model

## Other considerations
* Due to sensitivity around our data and recommendations, our final report on this project is not available in this repository. It was provided to our stakeholders directly.
* Similarly, raw data is not available in this repository as it contained PII data.
