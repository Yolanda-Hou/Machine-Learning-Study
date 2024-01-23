# Machine Learning Study
This is Yolanda's notebook for machine learning study. A practical self-study guidance for machine learning models and how to perform them in R.
## Linear regression
### What is linear regression
- A linear regression is a statistical model that analyzes the relationship between a response variable (often called y) and one or more variables and their interactions (often called x or explanatory variables).
- linear regression assumes that there exists a linear relationship between the response variable and the explanatory variables. This means that you can fit a line between the two (or more variables). 
- Simple linear regression is a useful approach for predicting a response on the basis of a single predictor variable.
- In practice we often have more than one predictor, where we need to use the muliple linear regression. 
### How to perform linear regression in R
- use `cars` dataset that comes with R by default.
- us `lm()` function to fit the model then use `summary()` function to get some detailed information
- see example code for detail
=======
## Logistic regression
### What is logistic regression
- Logistic regression is a type of classification model for supervised machine learning.
- Logistic regression finds the best possible fit between the predictor and target variables to predict the probability of the target variable belonging to a labeled class/category. 
### How to perform logistic regression in R
- use the Smarket data set from the ISLR package as an example
- fit the logistic regression model to predict Direction using Lag1,Lag2,Lag3,Lag4,Lag5, and Volume
- NOTE: When fitting a logistic regression model using the glm() function, you need to specify family="binomial"
- see detail in example code

