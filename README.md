# Machine Learning for predicting protein yield
This project implements Gaussian Process Regression (GPR) to predict protein yield based on various features. The datasets used for this project are publicly available. The model is built using PyMC, a probabilistic programming framework, and leverages Bayesian inference to estimate the parameters of the Gaussian Process. This is benchmarked against a random forest regression model and linear regression model to compare performance.

A set of feature importance metrics are also calculated to understand the contribution of each feature to the model's predictions.

## Installation
To run this project, you need to have Python installed along with the required packages. You can install the necessary packages using pip:
```bash
pip install -r requirements.txt
```
## Usage
1. Open the `bayesian_modelling_I.ipynb` notebook in Jupyter Notebook or JupyterLab.
2. Run the cells sequentially to load the data, preprocess it, and fit the Gaussian Process Regression model.
3. The notebook includes sections for training the model, making predictions, and evaluating the model's performance on both training and validation datasets.
4. The results of the predictions and performance metrics will be displayed in the notebook.
5. You can also visualize the predictions against the actual GFP yield values using the provided plotting functions.


## Features
- Implementation of Gaussian Process Regression using PyMC.     