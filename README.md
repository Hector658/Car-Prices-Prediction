# Car-Prices-Prediction

![p_lot](https://github.com/Hector658/Car-Prices-Prediction/assets/146046209/079ffbbf-33c8-458c-bfb3-8e75b374d8a1)

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


![Captura de pantalla 2023-12-18 194448](https://github.com/Hector658/Car-Prices-Prediction/assets/146046209/ac5f371d-696f-4f5f-8073-58b00195002c)

![Captura de pantalla 2023-12-18 194506](https://github.com/Hector658/Car-Prices-Prediction/assets/146046209/8b5eae3f-e668-42c5-8b16-6a2487f21dc3)



Car count by make


![dist car make](https://github.com/Hector658/Car-Prices-Prediction/assets/146046209/cd59ebdf-28df-4a79-95b2-f8bdc8e72688)




Distribution of car prices by type of fuel and the mileage of each one

![car mil fuel](https://github.com/Hector658/Car-Prices-Prediction/assets/146046209/a7c1c8bb-3517-4a75-94ac-6645b46e5e9b)





Correlation between the variables and the selling price

![heatmap](https://github.com/Hector658/Car-Prices-Prediction/assets/146046209/cb4e249e-a8a7-4495-9523-fb3cd8f80a7e)




According to the heatmap, the variables that most influence price are the ones related to the engine
![pow torq](https://github.com/Hector658/Car-Prices-Prediction/assets/146046209/24a9598e-6330-4583-9899-4a9ee083da4a)




## Building the model

In order to find the best model tests were performed with three python regression methods:
* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

A training data set was used for each of them and the predicted data was compared with the real data, measuring the 
Mean Absolute Error and using the model with the smallest one.


![Captura de pantalla 2023-12-18 194852](https://github.com/Hector658/Car-Prices-Prediction/assets/146046209/d8d4c9a8-d9f3-42e6-9987-7e0075813e8c)






  
  
  
