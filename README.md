# UW_Regression

Assignments

W1: Simple Linear Regression
- Write a function to compute the simple linear regression weights using the closed form solution
- Write a function to make predictions of the output given the input feature
- Turn the regression around to predict the input/feature given the output
- Evaluate different models via RSS 

W2: Multiple Linear Regression (I)
- Create more potential features (feature engineering)
- Use scikit-learn to create multiple linear regression models and compute the regression weights (coefficients)
- Write a function to compute the RSS given the regression weights, predictors and outcome
- Look at coefficients and interpret their meanings
- Evaluate multiple models via RSS

W2: Multiple Linear Regression (II)
- Add a constant column of 1's to a DataFrame to account for the intercept
- Convert DataFrame into numpy array
- Write a get_predictions() function using numpy
- Write a numpy function to compute the derivative of the regression weights with respect to a single feature
- Write gradient descent function to compute the regression weights given an initial weight vector, step size and tolerance
- Use the gradient descent function to estimate regression weights for multiple features

W3: Assessing Performance
- Write a function to take an an array and a degree and return an data frame where each column is the array to a polynomial value up to the total degree
- Use matplotlib to visualize polynomial regressions
- Use matplotlib to visualize the same polynomial degree on different subsets of the data
- Use a validation set to select a polynomial degree
- Assess the final fit using test data

W4: Ridge Regression (I)
- Use scikit-learn to create polynomial regression
- Use matplotlib to visualize polynomial regressions
- Use scikit-learn to create ridge regression (with different L2 penalties)
- Use matplotlib to visualize polynomial regressions under L2 regularization
- Choose best L2 penalty using cross-validation
- Assess the final fit using test data

W4: Ridge Regression (II)
- Write a Numpy function to compute the derivative of the ridge regression weights with respect to a single feature
- Write gradient descent function to compute the regression weights given an initial weight vector, step size, tolerance, and L2 penalty

W5: Feature Selection & Lasso (I)
- Use scikit-learn to create lasso regression (with different L1 penalties)
- Choose best L1 penalty using a validation set
- Choose best L1 penalty using a validation set, with additional constraint on the size of subset

W5: Feature Selection & Lasso (II)
- Write a function to normalize features
- Implement coordinate descent for LASSO
- Explore effects of L1 penalty

W6: Nearest Neighbors & Kernel Regression
- Find the k-nearest neighbors of a given query input
- Predict the output for the query input using the k-nearest neighbors
- Choose the best value of k using a validation set
