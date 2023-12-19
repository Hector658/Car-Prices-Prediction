# Car-Prices-Prediction

## Project Overview
* Downloaded a Dataset with information about over 6 thousand cars
* Cleaned the information so that it is possible to use in a python model
* Bulit a model to determine the price of cars given their features 

## Skills used in this project
* Cleaning datasets fixing typos, filling missing values, replacing or droping data and handling duplicate rows
* Using Python plotting tools to make histograms, scatter plots, and others
* Handling training and test data so it can be used in the regression models of Python

## Libraries 
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit-Learn


## Data Cleaning
The downloaded data contained multiple variables such the name, the mileage, transmission and other important aspects when buying a car as well as the selling price wich is our target variable.
The data was also messy and contained duplicated rows as well as missing values. Here are the most important steps taken to make it.

  * Checking and dropping duplicate rows
  * Droping characters in order to have a cleaner format
  * Replacing missing values with the mean of a certain column
  * Converting columns to numerical
  * Dropping columns and missing values
  * Replacing values in order to have a cleaner format
  * Converting words to numbers (first to one, or second to 2 for example)
  * Saving Dataframe in CSV format
 
  ## Exploratory Data Analysis
Comparing the cheapest and the most expensive car and their specifications

Car count by make

Distribution of car prices by type of fuel and the mileage of each one

Correlation between the variables and the selling price

According to the heatmap, the variables that most influence price are the ones related to the engine


## Building the model

In order to find the best model tests were performed with three python regression methods:
* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

A training data set was used for each of them and the predicted data was compared with the real data, measuring the 
Mean Absolute Error and using the model with the smallest one.









  
  
  
