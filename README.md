# ECE 228 Group 29
 Gordon Duncan, Shubhum Kumar, Stephen Kim
# Introduction
This is the README for ECE 228 Group 029 for Spring 2022. We included all of the files that we used for data cleaning/gathering and our models. 
# Data Cleaning
Our raw Wildfire data is in the **Data** folder

We clean our data and the process is in **Data Cleaning.ipynb**. Unfortunately, the entire file cannot be run since the API KEY is not included, but the resulting data is in the **Cleaned Data** folder.

We then split our cleaned data into training data and test data. This is then stored in the **Model Data** folder. 
# Data Visualization
holomap.html, points.html are visualizations generated from the cleaned data and they provide a visualization for the Wildfire data per year.
# Logistic Regression & MLP
The logistic regression and MLP model (training and testing) are in the **Logistic-Regression-MLP.ipynb**.
# LSTM
The LSTM model (training and testing) are in the **Time Series Analysis.ipynb**.
# Random Forest
The Random Forest model (training and testing) are in the **Random Forest.ipynb**.

To run the Random Forest model, open up the **Random Forest.ipynb** file
- Run the Imports section
- Run the Data Preparation
- Run the Optimal HyperParameter Analysis section
