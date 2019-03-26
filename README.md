# Sparkify Capstone Project

1. [Installation](#libraries)
2. [Project Motivation](#motivation)
3. [Files](#files)
4. [Result](#results)
5. [Acknowledgements](#acknowledgements)

## Libraries <a name="libraries"></a>
For this project the necessary libraries used are:
 - pyspark
 - pyspark.sql
 - pyspark.sql.types
 - pyspark.sql.functions
 - pyspark.ml
 - pyspark.ml.feature
 - pyspark.ml.classification
 - pyspark.ml.tuning
 - pyspark.ml.evaluation
 - plotly.offline
 - plotly.graph_objs
 
## Motivation <a name="motivation"></a>
In this project we work with a music application data called Sparkify and our main goal is to predict whether a user is going to cancel its subscription or not.

As one can imagine, there is a lot of data registering all the movements a user does while using the application, so this is the principal problem.

## Files <a name="files"></a>
This Project includes just one file: 
 - Sparkify.ipynb: Jupyter Notebook containing all the code needed to develop each one of the steps to reach the objective of the project.

# Results <a name="results"></a>
One of the conclusions we can get from this project is the urgent need to simplify and reduce the data, as there are a lot of actions per session and multiple sessions per user.

Moreover, regarding the action data, it includes a lot of information from the server that may not be useful for obtaining any insights about churn modelling.

Besides, another difficulty has been to define the churn between all the information we had from the beginning. After that, we only have to use what we have learnt about Machine Learning to apply the best practices when training our models and compare the results.

The models we've tried here are:
 - LinearSVC
 - LinearRegression
 - RandomForestClassifier

The result of the analysis is a model built with RandomForestClassifier reaching about 86% accuracy when predicting if a user is going to cancel it's subscription.

## Acknowledgements<a name="acknowledgements"></a>
Fundamentally, I used [The Apache Spark documentation](https://spark.apache.org/docs/latest/)
