---
title: Linear Regression
date: '2020-06-11'
github: 'https://github.com/odfalik/cs4375-lin-reg'
topics: [Machine Learning, Python, Numpy]
---


For this assignment, we processed a dataset from the UCI Machine Learning Repository. This dataset contained the MPG for several hundred models of cars along with their specifications such as displacement, mileage, horsepower, year, origin, and name.

After an initial preprocessing which involved stripping non-numerical attributes and deleting samples with missing attributes, we had in a total dataset of 392 samples with seven attributes. Next, we wrote a Python program to learn a gradient descent-based linear regression model to predict the MPG of a car and evaluated it against Scikit-learn’s linear regression model.