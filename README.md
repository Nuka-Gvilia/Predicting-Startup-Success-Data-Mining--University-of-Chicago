# Predicting-Startup-Success-Data-Mining            

Part of the Data Mining class at the University of Chicago's Master of Science in Analytics program 

## Project Intro/Objective
For this project we built classification and clustering models to predict whether or not a startup will succeed (either reach an IPO, get acquired or still operating)

## Methods Used
- K-Modes Clustering
- Logistic Regression
- Support Vector Machines 
- Random Forest 

## Technologies 
- Python 
- Google Colab 

## Dataset 
Dataset with more information can be found [here](https://www.kaggle.com/datasets/justinas/startup-investments)

The dataset consists of 11 different tables characterizing startups. 
The response variable is broken into 4 categories:
- IPO
- Acquired
- Operating 
- Closed

## Methdology

We created two groups within the responce variable - success and failure. Successful startups included those that either IPO-ed, were acquired or are still operational. Failed startups included the ones that were closed.  We performed clustering analysis to identify similarities among successful startups and compared the effectiveness of the above-mentioned classification algorithms to pick the best one
