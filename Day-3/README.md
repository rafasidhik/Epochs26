# Exploratory Data Analysis , Data Cleaning & Feature Engineering

## Dataset Overview

This project uses the Used Car Price Prediction dataset to perform Exploratory Data Analysis (EDA), Data Cleaning, and Feature Engineering. The cleaned dataset is prepared for future machine learning model development.

## Data Quality Issues Identified

- Missing values in the **fuel_type**, **accident**, and **clean_title** columns.
- Incorrect data types for **milage** and **price**.
- Outliers present in the **price** column.

## Cleaning Techniques Applied

- Filled missing values using the mode.
- Removed duplicate records.
- Converted **milage** and **price** to numeric data types.
- Removed outliers using the Interquartile Range (IQR) method.

## Feature Engineering

The following new features were created:

- Car Age
- Mileage Per Year
- Luxury Brand Indicator
- Accident Indicator
- Clean Title Indicator

## Five Key Insights

1. A few car brands dominate the dataset.
2. Gasoline is the most common fuel type.
3. Automatic transmissions are more common than manual transmissions.
4. Most vehicles have clean titles and no reported accidents.
5. Feature engineering created useful variables for future machine learning models.