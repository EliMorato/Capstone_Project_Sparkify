# Sparkify Capstone Project

## Libraries
For this project the necessary libraries used are:
 - Pyspark
 - Plotly
 
## Motivation
In this project we work with a music application data called Sparkify and our main goal is to predict whether a user is going to cancel it's subscription or not.

As one can imagine, there is a lot of data registering all the movements a user does while using the application, so this is the principal problem.

## Files
This Project includes just one file: 
 - Sparkify.ipynb: Jupyter Notebook containing all the code needed to develop each one of the steps to reach the objective of the project.

# Results

One of the conclusions we can get from this project is the urgent need to simplify and reduce the data. As we can see in the image above, there are a lot of actions per session and even some sessions may belong to the same user.


![Alt text](newplot.png?raw=true "Actions per session")
![Alt text](newplot.png?raw=true "Actions per session")


If we also think about each action includes many data, it becomes very difficult to deal with it and to get some useful information from this.

Besides, another difficulty has been to define the churn between all the information we had from the beginning. After that, we only have to use what we have learnt about Machine Learning to apply the best practices when training our models and compare the results.

The models we've tried here are:
 - LinearSVC
 - LinearRegression
 - RandomForestClassifier

The result of the analysis is a model built with RandomForestClassifier reaching about 86% accuracy when predicting if a user is going to cancel it's subscription.
