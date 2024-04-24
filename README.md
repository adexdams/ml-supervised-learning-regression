# ML Supervised Learning (Regression Problem)
This ML project shows a model that predicts target feature (price) from reading other features for used cars.
* This demo was developed following the completion of the "Complete A.I. & Machine Learning, Data Science Bootcamp" courses: https://www.udemy.com/course/complete-machine-learning-and-data-science-zero-to-mastery/


## Problem Statement
Given the data on used car sales we used regression models to predict the price of cars that meet the features collected.


## Data
**Source of data:** This dataset was collected from the Udemy lessons. It was manipulated to contain empty rows, now it has a shape of 1,000 rows and 5 columns.


## What you should expect
* The following steps were taken on the dataset to develop an ML model:
* The ML package technology was imported into the file to execute the task.
* The data was read and explored to show a description of the data content, this included bar charts of car brands and a histogram of prices.
* The data was processed using the pipeline method to fill in missing features with mean or preset values.
* The data is randomized and then split into train and test groups which were used to fit and score the model
* The initial model score was 22% after modeling.
* Then I tried to improve the model with hyperparameter tunning using GridSearchCV
* The model improved by 2% to score 24.9% in the new score
* The model was saved to file using joblib


## Next Steps
See the Python notebook attached to this repository for the modeling work.
