## How to run Linear regression in Python scikit-Learn

### Scikit-learn
 is a powerful Python module for machine learning. It contains function for regression, classification, clustering, model selection and dimensionality reduction.


In this section I am going to fit a linear regression model and predict the Boston housing prices. I will use the least squares method as the way to estimate the coefficients.

Y = boston housing price(also called “target” data in Python)

and

X = all the other features (or independent variables)

First, I am going to import linear regression from sci-kit learn module. Then I am going to drop the price column as I want only the parameters as my X values. I am going to store linear regression object in a variable called lm.


- I explored the boston data set and then renamed its column names.
- I explored the boston data set using .DESCR, my goal was to predict the housing prices using the given features.
- I used Scikit learn to fit linear regression to the entire data set and calculated the mean squared error.
- I made a train-test split and calculated the mean squared error for my training data and test data.
- I then plotted the residuals for my training and test datasets.