# Udacity's Data Scientist Nanodegree Data Science Capstone Project - Sparkify Project

by Pascal Dsouza

## Table of Contents


1 Installation

2 Dependencies

3 Project Motivation

4 File Description

5 Results


# Installation:

In addition to the Anaconda distribution of Python versions 3.5+, please install the following packages:

NumPy, Matplotlib, Seaborn
PySpark

# Project Description & Motivation:

In this project, the objective is to make use of the big data and distributed computing nature of Spark to explore and understand the Sparkify dataset provided, and use machine learning APIs from Spark ML to build and tune models to predict the churn rate of Sparkify. Sparkify is a fictional music streaming service similar to Spotify, and the dataset used in this project is mainly activity logs from each user which would be useful for predicting the churn rate of Sparkify.

# File Description:

in the below link  notebook available here to showcase work related to this project. The notebook is exploratory in searching through and working with the data pertaining to the churn rate prediction of the subject in hand, and markdown cells were used to assist in walking through the thought process for individual steps.
please find the link to access notebook 
https://github.com/pascaldsouza/capstone-project 

Data frame & models  saved from workspace are too big so coulldnt load in Github

# Results

I have used 3 models to comparing for churn rate prediction are logistic regression, random forest classifier, and gradient-boosted tree classifier. glassfier model better peformed compare to othe rtwo Models based on F1 score .so gradient classfier is further tuned to increase the performance.However it is imperative to keep in mind that there is always still room for improving the performance of churn rate prediction.

The main findings and research for this project can be found in the medium  post available link below 
https://medium.com/@pasvyff/churn-prediction-rate-using-pyspark-2c97bc348d25
