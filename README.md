# Modeling of Energy Output in Combined Cycle Power Plants Using Linear and KNN Regression


## Overview
This project presents a detailed analysis of the Combined Cycle Power Plant Data Set, covering the years 2006 to 2011. The goal is to predict the net hourly electrical energy output (EP) using key ambient variables like Temperature (T), Ambient Pressure (AP), Relative Humidity (RH), and Exhaust Vacuum (V). Employing a range of statistical and machine learning techniques, the project explores linear regression, multiple regression, polynomial regression, interaction term analysis, and KNN regression.

## Data Set
The data set includes hourly average ambient variables collected over 6 years when the power plant operated at full load. The features are used to predict the net hourly electrical energy output of the plant.

## Getting Started
### Data Acquisition
- Download the Combined Cycle Power Plant data set from the UCI Machine Learning Repository.

### Data Analysis and Modeling
- Perform preliminary analysis to understand the dataset's structure and variable characteristics.
- Explore relationships between variables using pairwise scatterplots and detailed statistical analysis.
- Apply simple linear regression for each predictor to understand its impact on energy output.
- Conduct multiple regression analysis to evaluate the combined effect of all predictors.
- Compare the results of simple and multiple regression models.
- Investigate nonlinear associations and interactions between predictors.
- Optimize and test the regression models, incorporating interaction terms and nonlinear associations.
- Apply K-nearest neighbor regression and determine the optimal number of neighbors.
- Conduct a comparative analysis of the regression models to evaluate their effectiveness.

## Requirements
Python 3.x
Libraries: numpy, pandas, matplotlib, scikit-learn

## Installation
To set up the project environment, install the required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## Usage
Run the Jupyter notebook Linear_Regression_and_KNN_Cici_Chang.ipynb to perform the analysis. The notebook contains detailed instructions and code for each step of the project.

## Contributing
Contributions are welcome. Please ensure that any enhancements or bug fixes are accompanied by appropriate test cases.
