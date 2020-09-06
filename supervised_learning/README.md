
# Supervised Learning

Majority of applied machine learning uses supervised learning.
## What is Supervised Learning 

 Supervised learning is where you have input variables (X) and an output variable (Y ) and you use an algorithm to learn the mapping function from the input to the output.The goal of all supervised machine learning algorithms is to best estimate a target function (f) that maps input data (X) onto output variables (Y ). This describes all classification and regression problems. 


Supervised learning is typically done in the context of:
1. **Classification**, when we want to map input to output labels, or
2. **Regression** when we want to map input to a continuous output


## When to use Supervised Learning

* With supervised machine learning, the algorithm learns from labeled data.
* Fully labeled means that each example in the training dataset is tagged with the answer the algorithm should come up with on its own. 
* So, a labeled dataset of flower images would tell the model which photos were of roses, daisies and daffodils. When shown a new image, the model compares it to the training examples to predict the correct label.

If you have a set of existing data including the target values that you wish to predict (labels) then you probably need supervised learning (e.g. is something true or false; or does this data represent a fish or cat or a dog? Simply put - you already have examples of right answers and you are just telling the algorithm what to predict). You also need to distinguish whether you need a classification or regression. Classification is when you need to categorize the predicted values into given classes (e.g. is it likely that this person develops a diabetes - yes or no? In other words - discrete values) and regression is when you need to predict continuous values (1,2, 4.56, 12.99, 23 etc.). There are many supervised learning algorithms to choose from (k-nearest neighbors, naive bayes, SVN, ridge..)

## How it Works

![](https://github.com/Jean-njoroge/Machine-Learning-Resources/blob/master/Images/Supervised_machine_learning_in_a_nutshell.png)
## Algorithms


| Category | Algorithm | Notes |
|---|---| ---| 
| **Linear Models for Regression or Classification**|Ordinary Linear Regression(OLS) | establish a relationship between the dependent and independent variables |
| |Linear Regression with Lasso or Ridge Regularization |  |
| |Logistic Regression| predicts the probability of true/false or yes/no responses on the basis of the independent variable’s value. |
| |Naive Bayes| |
| |Stochastic Gradient Descent (SGD), Coordinate Descent (CD), and Quasi-Newton (QN) (including L-BFGS and OWL-QN) solvers for linear models | |
| **Nonlinear Models for Regression or Classification**| Random Forest| |
| |Decision tree-based models| |
| |	K-Nearest Neighbors (KNN)| |
| |Support Vector Machine Classifier| |

## Business Use Cases
