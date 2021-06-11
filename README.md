# Multivariate Linear Regression

## Problem Statement

Linear Regression with multiple variables is implemented to predict the prices of houses using size of the house (in square feet) and number of rooms as features. Suppose you are selling your house and you want to know what a good market price would be.

## Implementation

### Feature Normalization

Feature normalization is performed since size of houses and number of bedrooms are on different scales. This helps in making gradient descent converge faster.

- Subtracted the mean value of each feature from the dataset.
- After subtracting the mean, additionally, the features are divided by their respective “standard deviations.”

### Cost Function and Gradient Descent

Vectorized implementation of the cost function and gradient descent has been done.

## Best Learning Rate

The cost versus iterations was plotted to identify the best value of alpha.

<p align="center">
<img src="/Resources/learning-rate.PNG">
</p>

## Normal Equation
