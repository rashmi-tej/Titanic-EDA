# Titanic Exploratory Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The goal is to understand the factors that influenced passenger survival and identify meaningful patterns in the data.

## Objectives

* Explore the Titanic dataset.
* Handle missing values and clean the data.
* Analyze survival patterns using visualizations.
* Summarize key findings from the analysis.

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Data Cleaning

The dataset contained missing values in the Age, Cabin, and Embarked columns. Missing Age values were filled using the median, missing Embarked values were filled using the mode, and the Cabin column was removed because it contained too many missing values.

## Key Findings

* Female passengers had a higher survival rate than male passengers.
* First-class passengers were more likely to survive than passengers in lower classes.
* Children generally had better survival chances than older adults.
* Gender, passenger class, and age were the most important factors affecting survival.

## Future Work

Future work could include building machine learning models to predict passenger survival and performing additional feature engineering to improve prediction accuracy.