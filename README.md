# Logistic Regression and Support Vector Machine (SVM) to Predict Income Levels

We are going to preprocess Income dataset, converting non-numeric columns to numeric and use \
**SVM and logistic regression** machine learning methods to predict the person’s income asbeing \
over or under $50,000 a year.

In this project we use ***Feature selection***,  a process where you automatically select those features\
in your data that **contribute most to the prediction variable or output** in which you are interested.  

There are in general two reasons why feature selection is used:

1.	Reducing the number of features, to reduce overfitting and improve the generalization of models.
2.	To gain a better understanding of the features and their relationship to the response variables.

Here we use ***GridSearchCV*** from sklearn library to do an exhaustive search over more than one set \
of specified parameter values for an estimator object, such as logistic regression, to find the best \
parameters for our model that result in best Cross-validation score (i.e. accuracy score).

 This project also uses ***"sklearn Pipeline"*** to find the optimum number of components for dimensionality \
 reduction using Principal Component Analysis (PCA). **"Pipelines are used to assemble several steps that \
 can be cross-validated together while setting different parameters.**
