# Linear Regression Algorithm on Python
Welcome to first part of my repository. In this part, I will introduce you Linear Regression algorithm as well as basic preprocessing steps, cross validation, hyperparameter tuning and more. 

## Contents:

**1.Linear Models in Machine Learning on Python Regression 1:** In this notebook, I firstly talk about the general concept and mathematics behind linear regression. Afterwards, I show some basic preprocessing steps such as one-hot encoding, cleaning missing values, standardization, transforming target feature into normal distribution. I perform all of these steps on Ames Housing Dataset. Lastly, I train `LinearRegression()` algorithm on this processed dataset.


**2.Linear Models in Machine Learning on Python Regression 2:** In the second notebook, we dive deeper into understanding encoding, scaling and skewness. We see that different scaling and encoding algorithms can change performance of our model, in addition to that, we also deal with skewed features. Moreover, since it is also necessary to be familiar with basic visualization skills, in this notebook, I show some functions of seaborn that I frequently use.

**3.Linear Models in Machine Learning on Python Regression 3:** In the third notebook, we visit the mathematics behind linear regression one more time to extent our understanding of this algorithm by adding some new ways to deal with overfitting. We see that how regularization techniques can affect the performance of our model as well as how we can use some function such as `GridSearchCV` or `RandomizedSearchCV` to find best hyperparameters for our model. It is also important to understand general idea behind cross validation to be able to use GridSearchCV properly, therefore, in this notebook we also briefly talk about cross validation.

**4.Linear Models in Machine Learning on Python Regression 4:** In the last notebook, we practice everything we leant in the previous three notebooks by trying to predict death toll on covid dataset. To make it more informative, I also show how to use some animated plots, custom transformers and how to visualize the performance of our model during training with `GridSearchCV()`.
