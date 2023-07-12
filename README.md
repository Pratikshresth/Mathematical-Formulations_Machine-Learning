
# Mathematical Formulations of Algorithms
This repository contains Jupyter Notebook files that explain the mathematical formulations and implementation of various algorithms from scratch. The notebooks provide step-by-step explanations and code examples for algorithms such as Linear Regression, Multiple Linear Regression, Gradient Descent, and more.

Welcome to the Machine Learning Algorithms from Scratch repository! This repository contains Python implementations and detailed mathematical formulations of popular machine learning algorithms. Whether you're a beginner seeking to understand the inner workings of these algorithms or an experienced practitioner looking to refresh your knowledge, this repository is a valuable resource.

### [Table of Contents](#table-of-contents)
  * [Algorithms Covered](#algorithms-covered)
    + [Linear Regression](#linear-regression)
    + [Regression Metrics](#regression-metrics)
    + [Multiple Linear Regression](#multiple-linear-regression)
    + [Gradient Descent](#gradient-descent)
    + [Effects of Learning Rate](#effects-of-learning-rate)
    + [Effects of Loss Function](#effects-of-loss-function)
    + [Polynomial Regression](#polynomial-regression)
  * [Getting Started](#getting-started)
  * [Dependencies](#dependencies)

## Algorithms Covered

### Linear Regression
- Closed Form Solution (OLS): An analytical method that finds the optimal parameters of a linear regression model by solving a system of linear equations.
- Non-Closed Solution (Gradient Descent): An iterative optimization algorithm that updates the parameters of a linear regression model by minimizing the cost function using gradient descent.

### Regression Metrics
- Mean Absolute Error (MAE): Measures the average absolute difference between the predicted and actual values, providing an intuitive measure of model accuracy.
- Mean Squared Error (MSE): Measures the average squared difference between the predicted and actual values, emphasizing larger errors more than MAE.
- Root Mean Squared Error (RMSE): The square root of MSE, offering a more interpretable metric in the original scale of the target variable.
- R2 Score (Coefficient of Determination): Measures the proportion of the variance in the dependent variable that can be predicted from the independent variables, indicating the goodness of fit of the model.

### Multiple Linear Regression
- Equation of Hyperplane: Explores the equation that represents the decision boundary or hyperplane in a multiple linear regression model.

### Gradient Descent
- Batch Gradient Descent: An optimization algorithm that updates the model parameters using the gradients of the entire training dataset.
- Stochastic Gradient Descent: An optimization algorithm that updates the model parameters using the gradients of individual training examples, making it computationally efficient for large datasets.
- Mini-Batch Gradient Descent: A hybrid approach that updates the model parameters using the gradients of a small batch of training examples, balancing computational efficiency and convergence speed.

### Effects of Learning Rate
Investigates the impact of learning rate on the convergence and speed of gradient-based optimization algorithms.

### Effects of Loss Function
Examines different loss functions and their implications for model training and performance evaluation.

### Polynomial Regression
Extends linear regression by incorporating polynomial features to capture nonlinear relationships between variables.

### Getting Started
To explore the mathematical formulations and implementations of these algorithms, follow these steps:

1. Install Python (version 3.x) and Jupyter Notebook on your machine.
2. Clone or download this repository to your local environment.
3. Open the Jupyter Notebook file (*.ipynb) corresponding to the algorithm or topic you wish to explore.
4. Run the notebook cells to see the mathematical formulations and execute the code.

### Dependencies
The following dependencies are required to run the Jupyter Notebook files:

- Python 3.x
- NumPy
- Matplotlib
- Pandas (if applicable)
