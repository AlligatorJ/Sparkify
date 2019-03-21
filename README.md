# Sparkify
Predicting churn with Spark

# Libaries

 The notebooks runs on IBM Watson Studio with Phyton 3.5 and Spark with follwing liabries required:
 
  Pyspark
  
  Numpy
  
  Pandas
  
  Seaborn
  
  Matplotlib
  
 # Required data
 
 medium-sparkify-event-data.json: user log data of the streaming service Sparkify
 
 The required data is provided by Udacity as part of the Data Science Program
 
 
# Motivation
For many businesses it is crucial crucial to predict if a user it is likely to quit using this service (called “churn”). The success of a subscription based service e. g. music streaming is related to the total number of user of the service. As more users use the service as more revenues can be generated by subscription fees or advertising. If you can predict churn you can target the user with specific measures to keep the user using the service.

This project uses log data of a fictional music streaming service called Sparkify. The software Spark is used to process the data and to demonstrate how to predict churn. The Project contains the following steps:

1.Exploratory Data Analysis
2. Extract and engineering of features for the model
3. Building and of a machine learning model
4. Evaluation and refinement of the model

The project is conducted by using PySpark and deployed on the cloud platform IBM Watson.
# Files
Sparkify.ipynb: 
Jupiter Notebook with exploration of data and prediction model


# Summary

The project showed how to process large datasets of a streaming service with spark and how to deploy the solution to a cluster. The performance of the model with a accuracy of 0.84 and a F1-score of 0.82 is already very good. With a bigger dataset and more computational power to conduct a grid search over a lager space of hyperparamters (or with random search) even better results could be reached.

# Acknowledgements

Udacity Data Science Program (https://eu.udacity.com/)
 
