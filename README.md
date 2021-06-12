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

The prediction can also be done using Normal Equation instead of gradient descent. It does not require feature scaling as well. The formula of the normal equations is shown in Fig. below:

<p align="center">
<img src="/Resources/normal-equation.PNG">
</p>

# Directory Structure

<pre>
📦Multivariate-Linear-Regression
┣ 📂Dataset
┃ ┗ 📜ex1data2.txt
┣ 📂Documents
┃ ┗ 📜Linear Regression.docx
┣ 📂Resources
┃ ┣ 📜learning-rate.PNG
┃ ┗ 📜normal-equation.PNG
┣ 📜A1_Q1_Part_2.ipynb
┗ 📜README.md
</pre>
