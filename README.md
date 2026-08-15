# Medical Insurance Data Analysis

## Overview

This project focuses on exploring, cleaning, preprocessing, and performing feature engineering on a medical insurance dataset.

The main objective is to understand the data, prepare it for machine learning, and analyze the relationships between the available features and insurance charges.

## Dataset

The dataset contains information about medical insurance customers, including:

- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region
- Insurance charges

The target variable for future machine learning work is `charges`.

## Project Workflow

### 1. Exploratory Data Analysis

Performed initial analysis to understand:

- Dataset structure
- Data types
- Missing values
- Statistical distributions
- Feature distributions
- Relationships between variables
- Potential outliers

### 2. Data Cleaning and Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Checked for duplicate records
- Renamed categorical columns
- Converted categorical variables into numerical representations
- Saved the cleaned dataset as `insurance_cleaned.csv`

Examples of renamed features:

```text
sex     → is_female
smoker  → is_smoker
