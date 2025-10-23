# House Price Prediction
*A core regression project predicting median house values using Linear Regression on the California Housing Dataset. It models the relationship between demographic and geographical factors and price. Evaluated using key metrics: Mean Squared Error (MSE) and the R-squared (R2) Score.*

## Overview
This project addresses a classic regression problem in machine learning by building a model to predict continuous values. It utilizes the **California Housing Dataset** to implement a **Linear Regression** model capable of forecasting the median house value in a given district based on demographic and geographical features. The repository demonstrates a complete regression pipeline from data fetching to model evaluation.

## Goal
The primary goal is to develop an accurate and interpretable **Linear Regression** model to estimate the median house price, helping to identify which features have the strongest predictive influence on housing value.

## Methodology
The prediction process follows these steps:
- **Data Loading & Inspection**: The *California Housing Dataset* is fetched, and an initial inspection is performed to understand its structure and check for missing values.
- **Feature/Target Separation**: The input features (X) and the target variable (Price) are isolated.
- **Data Splitting**: The dataset is split into training and testing sets to validate the model's performance on unseen data.
- **Preprocessing**: Features are scaled using `StandardScaler` to ensure all variables contribute equally to the model training process.
- **Model Training**: The **Linear Regression** model is trained on the scaled training data.
- **Prediction & Analysis**: Predictions are generated on the test set and compared against the actual prices.

## Features
- **Regression Analysis**: Focuses on predicting a continuous outcome (**Median House Value**).
- **Linear Regression**: Implementation of the fundamental linear regression algorithm.
- **Data Preprocessing**: Includes feature scaling using `StandardScaler`.
- **Visualization**: Plots actual versus predicted values to visualize model fit.

## Results and Metrics
The model's predictive power is rigorously evaluated using standard regression metrics:
- **Mean Squared Error (MSE)**: Measures the average squared difference between the estimated values and the actual value. A lower MSE indicates better performance.
- **R-squared (R2) Score**: Represents the proportion of the variance in the dependent variable that is predictable from the independent variables. A value closer to $1.0$ signifies a better fit.

## Tech Stack
The following core technologies and libraries were used:
| Tool | Purpose |
|------|---------|
|**Python**|Primary programming language for all analysis and modeling.|
|`scikit-learn`|Used for **Linear Regression**, data splitting, and calculating MSE/R2 metrics.|
|`pandas`|Used for creating and manipulating the housing dataset `DataFrame`.|
|`matplotlib` / `seaborn`|Used for generating plots of data distribution and model residual errors.|

## Prerequisites
- **Python 3.x** environment.
- Required Python packages (listed in **Installation**).

## Installation
**Clone the repository and install the dependencies:**

1. #### Clone the repository
```bash
git clone https://github.com/Tanmay2923/House-Price-Prediction-.git
```

2. #### Install necessary Python libraries
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Running the Application
The analysis is executed via a Jupyter/Colab notebook.
1. Open the file `House Price Prediction` in Google Colab or a local Jupyter Notebook environment.
2. Execute all cells sequentially to run the full pipeline, from data loading to model evaluation.
