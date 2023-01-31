# [Finding Donors](https://abhinrustagi.github.io/finding-donors/)

> I completed this small project as part of Udacity's Machine Learning Nanodegree. 

### Problem

Given a dataset of the income of multiple individuals, find out whether an individual will donate to CharityML (a fictional charity organization) or not. 

### Approach

Considering this problem will have a binary resolve with respect to each individual (yes or no), I decided to try out 3 different algorithms:

0. Naive Bayes (Base Model)
1. Logistic Regression
2. Support Vector Machines
3. K Nearest Neighbours

Here's the result of the accuracy I achieved on the training set:

| Model                   | Accuracy %  |
|-------------------------|-------------|
| Naive Bayes             | ~25         |
| Logistic Regression     | ~84         |
| Support Vector Machines | ~86         |
| KNN                     | ~87         |

I chose to go ahead with Logistic Regression since it gave the best results on the testing set.

**I received a final accuracy score of 84.2% with this model on the testing set.**
