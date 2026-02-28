# Sales Prediction Using Advertising Budget

## Project Overview

This project builds a Multiple Linear Regression model to predict product sales based on advertising expenditure across different media channels.

The dataset contains advertising budgets for TV, Radio, and Newspaper, along with the resulting Sales figures.

The goal is to understand how each advertising channel contributes to overall sales and to forecast future sales based on budget allocation.

## Dataset Description

### Input Features

* TV. Advertising spend on TV in thousands of dollars.
* Radio. Advertising spend on Radio in thousands of dollars.
* Newspaper. Advertising spend on Newspaper in thousands of dollars.

### Target Variable

* Sales. Units sold in thousands.

## Objective

* Analyze the relationship between advertising spend and sales.
* Identify which channel impacts sales the most.
* Build a regression model for accurate sales prediction.

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

1. Data loading and inspection.
2. Exploratory Data Analysis to identify trends and correlations.
3. Data preprocessing and feature selection.
4. Train test split of dataset.
5. Training Multiple Linear Regression model.
6. Model evaluation using Mean Squared Error and R squared score.
7. Interpretation of coefficients to understand feature impact.

## Model Evaluation Metrics

* Mean Squared Error
* R squared Score

## Expected Outcome

The model predicts sales based on advertising budgets and helps optimize marketing spend by identifying high impact channels.

requirements.txt

numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
