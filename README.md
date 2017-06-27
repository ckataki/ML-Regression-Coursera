# README #

This is the IPython repository for the Machine Learning: Regression course of Coursera. We will use k-nearest neighbors, lasso, ridge, and polynomial regression to predict house prices.

### Week 1: Use data on house sales in King County to predict house prices using simple (one input) linear regression. ###
    * Use graphlab SArray and SFrame functions to compute important summary statistics.
    * Write a function to compute the Simple Linear Regression weights using the closed form solution.
    * Write a function to make predictions of the output given the input feature.
    * Turn the regression around to predict the input given the output.
    * Compare two different models for predicting house prices.
### Week 2: Use data on house sales in King County to predict house prices using multiple regression. ###
    * Use SFrames to do some feature engineering.
    * Use built-in graphlab functions to compute the regression weights (coefficients/parameters).
        - Write gradient descent function to compute the regression weights given an initial weight vector, step size and tolerance.
    * Given the regression weights, predictors and outcome write a function to compute the Residual Sum of Squares.
    * Look at coefficients and interpret their meanings.
    * Evaluate multiple models via RSS.
### Week 3: Compare different polynomial regression models in order to assess which model fits best. ###
    * Use matplotlib to visualize polynomial regressions.
    * Use matplotlib to visualize the same polynomial degree on different subsets of the data.
    * Use a validation set to select a polynomial degree, and assess the final fit using test data.
### Week 4: Run ridge regression multiple times with different L2 penalties to see which one produces the best fit. ###
    * Use a pre-built implementation of regression (GraphLab Create) to run polynomial regression, with and without L2 penalties.
        - Write a gradient descent function to compute the regression weights given an initial weight vector, step size, tolerance, and L2 penalty.
    * Use matplotlib to visualize the effect of L2 regularization.
    * Choose best L2 penalty using cross-validation, and assess the final fit using test data.
### Week 5: Use LASSO to select features, building on a pre-implemented solver for LASSO. ###
    * Run LASSO with different L1 penalties.
        - Implement your own LASSO solver via coordinate descent, and explore effects of L1 penalty.
    * Choose best L1 penalty using a validation set.
    * Choose best L1 penalty using a validation set, with additional constraint on the size of subset.
### Week 6: Use k-nearest neighbors regression to predict house prices. ###
    * Find the k-nearest neighbors of a given query input.
    * Predict the output for the query input using the k-nearest neighbors.
    * Choose the best value of k using a validation set.


### How do I get set up? ###

* Python version: 2.7.12
* GraphLab Create: greater than 1.7
* Dependencies: Numpy, Matplotlib, IPython