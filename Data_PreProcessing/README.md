# Clinic Data Analysis and Preprocessing
This code is for perform data analysis and data preprocessing on a CSV file containing historical purchase data from a clinic. The purpose of this analysis is to process and explore the data, identify patterns, and perform some time series analysis.

## Prerequisites

- Python 3.x
- Pandas
- Scikit-learn
- Statsmodels

## Usage
Run the Python script using your preferred Python interpreter. The script performs the following steps:

- Load the CSV data into a Pandas DataFrame.
- Convert the 'Date' column to a datetime format and sort the DataFrame by date.
- Remove rows with missing values.
- Identify medicines with purchase counts of at least 25.
- Encode categorical features using LabelEncoder.
- Calculate the correlation matrix and display correlations with the target feature 'Quantity'.
- Select relevant columns ('Date' and 'Quantity') for further analysis.
- Resample data on a weekly basis and visualize.
- Perform Augmented Dickey-Fuller test for stationarity.
- Plot the resampled data.
- Split the data into training and test sets.

## Note
Use this final training and test sets data for all the time series model.
