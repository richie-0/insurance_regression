# Insurance Charges Prediction

This repository contains a Python script for predicting insurance charges based on age using linear regression. The script utilizes the pandas, numpy, matplotlib, and scikit-learn libraries.

## Installation

### To run this script, you'll need to install the following Python packages:

- [pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)
- [numpy](https://numpy.org/install/)
- [matplotlib](https://matplotlib.org/stable/users/installing.html)
- [scikit-learn](https://scikit-learn.org/stable/install.html)

### You can install these packages using pip:

#### `pip install pandas numpy matplotlib scikit-learn`

## Usage

1. Clone the repository:

git clone https://github.com/richie-0/insurance_regression

2. Navigate to the directory:

cd repository

3. Run the script:

python insurance_prediction.py

## Description

The script performs the following steps:

1. Reads insurance data from a CSV file.
2. Displays summary statistics and checks for missing values.
3. Prepares the data by defining x and y variables.
4. Visualizes the relationship between age and charges using a scatter plot.
5. Splits the data into training and testing sets.
6. Trains a linear regression model on the training data.
7. Visualizes the line of best fit on both training and testing data.
8. Interprets the model coefficients.
9. Computes the correlation matrix.
10. Evaluates the model using metrics such as R-squared, mean absolute error, and mean squared error.

## Dependencies

- pandas
- numpy
- matplotlib
- scikit-learn
