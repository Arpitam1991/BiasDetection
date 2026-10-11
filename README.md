# Bias Detection in Income Prediction

A Jupyter notebook project focused on exploring bias and fairness in a machine learning classification task using the UCI Adult Census dataset. The notebook investigates how demographic factors such as sex, race, and relationship status may influence predictions related to income level.

## Project Overview

This project analyzes the Adult dataset and applies preprocessing, exploratory data analysis, and model evaluation techniques to study potential bias in decision-making systems. The notebook is designed as a learning-focused demonstration of data cleaning, feature engineering, model comparison, and fairness analysis.

The primary task is to predict whether an individual's income is:
- `<= 50K`
- `> 50K`

The notebook also considers ethics and privacy concerns by examining whether the model disproportionately affects groups based on protected attributes.

## Motivation

Machine learning models can unintentionally encode discrimination present in historical data. In domains like hiring, lending, and public policy, this may lead to systematic unfairness. This project aims to highlight how data and model behavior can reflect social bias and why fairness-aware evaluation is important.

## Dataset

The project uses the UCI Adult Census dataset, often referred to as the "Adult" dataset.

### Features
The dataset includes attributes such as:
- age
- workclass
- fnlwgt
- education
- education-num
- marital-status
- occupation
- relationship
- race
- sex
- capital-gain
- capital-loss
- hours-per-week
- native-country
- class

### Target Variable
- `class` (income category)

## Notebook Contents

The notebook includes:
- Data import from Google Drive
- Handling encoding issues in the dataset
- Data cleaning and preprocessing
- Renaming columns to meaningful names
- Exploratory data analysis
- Statistical checks
- Model training and evaluation
- Fairness/bias analysis considerations
