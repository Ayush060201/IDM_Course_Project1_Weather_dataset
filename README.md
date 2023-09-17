# Exploratory data analysis on weather data
# Team: T30

Welcome to this data analysis and modeling project! This repository contains code snippets and explanations for various data analysis tasks, including data preprocessing, linear regression, XGBoost regression, and data visualization. Each section below summarizes a specific code snippet or task along with its purpose and instructions.

## Table of Contents

- [Introduction](#introduction)
- [Data Preprocessing](#data-preprocessing)
- [Linear Regression](#linear-regression)
- [XGBoost Regression](#xgboost-regression)
- [Identifying Columns with Many Null Values](#identifying-columns-with-many-null-values)
- [Visualizing Missing Data](#visualizing-missing-data)
- [License](#license)

## Introduction

This project focuses on data analysis and modeling tasks using Python and popular libraries such as pandas, scikit-learn, XGBoost, and Seaborn. Each section below covers a specific aspect of the project.
Data Source: https://www.kaggle.com/datasets/amirhoseinsedaghati/the-weather-of-187-countries-in-2020

This dataset contains weather data for various countries in 2020.
### The Feature Explanations:

- STATION: The station identifier
- Country/Region: The country or region where the station is located
- DATE: The date of the weather observation in YYYY-MM-DD format
- Year: The year of the weather observation
- Month: The month of the weather observation
- Day: The day of the weather observation
- PRCP: The amount of precipitation (rain or snow)
- SNWD: The depth of snow on the ground
- TAVG: The average temperature
- TMAX: The maximum temperature
- TMIN: The minimum temperature
- SNOW: The amount of snowfall
- LATITUDE: The latitude of the station's location
- LONGITUDE: The longitude of the station's location
- ELEVATION: The elevation of the station's location
- PRCP_ATTRIBUTES: Additional attributes for the precipitation data
- TAVG_ATTRIBUTES: Additional attributes for the average temperature data
- TMAX_ATTRIBUTES: Additional attributes for the maximum temperature data
- TMIN_ATTRIBUTES: Additional attributes for the minimum temperature data
- DAPR: The number of days since the last precipitation of any amount
- MDPR: The multiday precipitation total
- WESD: The water equivalent of the snow depth on the ground
- SNWD_ATTRIBUTES: Additional attributes for the snow depth data

### Operation
Following operations are performed in this data during analysis.
* Loading 
* Visualization
* Preprocessing
	* Handling `null` values
	* Labelling
* Regression
	1. Linear Regression
	2. Ridge Regression
	3. XGB Regression
*  Hyperparameter Tuning

## Data Preprocessing

### Code 1: Filling Null Values in a CSV File

- **Purpose**: This code demonstrates how to handle missing data by filling null values in a CSV file. It provides a flexible approach for dealing with columns like 'STATION,' 'Country/Region,' 'DATE,' 'Year,' 'Month,' 'Day,' 'PRCP,' 'TAVG,' 'TMAX,' and 'TMIN.'
- **Usage**: Replace 'your_data.csv' with your dataset file and customize the fill values as needed.

## Linear Regression

### Code 2: Linear Regression and Difference Visualization

- **Purpose**: This code performs linear regression on a dataset with columns 'Year,' 'Month,' 'Day,' 'PRCP,' 'TMAX,' 'TMIN,' and 'TAVG.' It includes training a Linear Regression model, making predictions, calculating Mean Squared Error (MSE), and visualizing the differences between predicted and real values.
- **Usage**: Replace the dataset file and customize the model as required.

## XGBoost Regression

### Code 3: XGBoost Regression and Difference Visualization

- **Purpose**: This code is similar to Code 2 but employs the XGBoost Regressor for regression tasks. It trains the model, computes MSE, and visualizes differences between predicted and real values.
- **Usage**: Replace the dataset file and customize the model as needed.

## Identifying Columns with Many Null Values

### Code 4: Identifying Columns with Many Null Values

- **Purpose**: This code identifies and lists columns in a dataset that contain more than 20,000 null (missing) values. It helps in pinpointing columns with substantial missing data.
- **Usage**: Replace 'weather.csv' with your dataset file and customize the threshold as required.

## Visualizing Missing Data

### Code 5: Heatmap for Visualizing Missing Data

- **Purpose**: This code generates a heatmap using the Seaborn library to visualize the presence of missing (null) values in a dataset. It aids in understanding the distribution of missing values across columns and rows.
- **Usage**: Replace 'weather' with your DataFrame and customize the visualization as needed.

## License

This project is licensed under the [License Name] License - see the [LICENSE.md](LICENSE.md) file for details.

Feel free to explore and adapt these code snippets to your specific data analysis and modeling projects. If you have any questions or need further assistance, please don't hesitate to reach out.

Happy coding!
