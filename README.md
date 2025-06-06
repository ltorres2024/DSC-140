# Titanic Dataset Analysis - DSC 140

This repository contains a basic data analysis project completed for the DSC 140 course using the famous Titanic dataset. The objective was to explore and visualize relationships between passenger demographics, ticket information, and survival rates.

## Overview

The project walks through:
- Data loading and cleaning
- Exploratory Data Analysis (EDA)
- Pivot tables and statistical tests
- Basic visualizations using `matplotlib` and `seaborn`

## Dataset

We used the `titanic_train.csv` dataset, which contains details for ~900 passengers aboard the Titanic, including:
- Passenger class (`Pclass`)
- Name, sex, and age
- Number of siblings/spouses aboard (`SibSp`) and parents/children (`Parch`)
- Ticket and fare
- Embarkation port
- Survival outcome

## Key Analyses

- **Age Distribution:** A histogram of passenger ages shows the demographic distribution.
- **Embarkation Locations:** A pie chart illustrates proportions of passengers from each embarkation point.
- **Age vs. Fare:** A scatter plot shows the correlation (with regression line) between passenger age and fare paid.
- **Fare by Class and Gender:** A pivot table and bar chart show how average fare varied across passenger classes and genders.
- **Survival by Gender:** A pivot table and chi-square test show a statistically significant correlation between gender and survival.

## Statistical Insight

A chi-squared test of independence was conducted to examine the relationship between survival and gender. The test resulted in a **p-value < 1e-50**, indicating a very strong relationship between these two variables in the dataset.

## Tools Used

- Python 3
- pandas
- matplotlib
- seaborn
- scipy.stats
