# Energy Prediction for Automobile A/C Systems

An NSF-funded research project I worked on through California State University, 
Northridge's Research Experience for Undergraduates (REU) program. The overarching goal of this project 
was to identify what variables play the most significant roles in A/C energy consumption. 

This repository contains some of the work I've contributed to the project. 
** Work is still in progress **

## Description

The project consisted of collecting data, analyzing data, and then creating and training models. There were many steps along this process.

We collected extensive data from a vehicle using an OBD-II logger. The logger captures over-the-road data in time-series format, logged onto a CSV file. We analyzed the data using Python and its libraries, like pandas and NumPy. Data pre-processing techniques such as missing value imputation, normalization, feature engineering, and feature selection are used to clean the data for model training and testing. Utilizing Matplotlib and Seaborn, many visualizations and plots were made to help better understand our data. In the end, we tested various models with scikit-learn and TensorFlow. Models include Random Forest Regressor, Polynomial Regression, Regression DNN, and LSTM.

![ac and co2](https://github.com/ND68/Energy-Prediction-for-Automobile-AC-Systems/blob/main/plots/ac_vs_co2.png?raw=true)

![temps](https://github.com/ND68/Energy-Prediction-for-Automobile-AC-Systems/blob/main/plots/temps.png?raw=true)

## Getting Started

### Dependencies

Python libraries
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Tensorflow

### Executing program

* All code files run in JupyterNotebooks/JupyterLabs. This is best for viewing data and plots.

## Authors

Nathan Dong,
Adel Tazhibi, 
Kavyalata Kothari, 
Dr. Taehyung Wang
