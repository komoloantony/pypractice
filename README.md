
Project Overview
This project involves analyzing student performance data to understand individual subject scores (Math, English, Science), identify statistical measures, and predict scores based on study hours. It also includes identifying top and bottom performing students.

Data Source
The data for this analysis is loaded from student_performance_dataset.xlsx.

Key Analyses Performed
Data Loading and Inspection: Loaded student performance data into a pandas DataFrame.
Descriptive Statistics: Calculated mean, median, and standard deviation for Math, English, and Science scores.
Visualizations: Plotted individual subject scores to visualize student performance distribution.
Predictive Modeling: Used Linear Regression to predict Math, English, and Science scores based on 'Study Hours'.
Student Performance Ranking: Identified top and bottom students based on their overall average scores across subjects.
2. Other Projects
Music Database
(Details about this project are not available in the current notebook, but it typically involves managing and querying music-related data.)

Student Database
(This project is related to the current student performance analysis, focusing on the broader management and structure of student information.)

Manual DataFrame Creation and Manipulation
(Details about this project are not available in the current notebook, but it likely involves creating and manipulating pandas DataFrames manually to understand their structure and operations.

#**Mini-Temperature AI Project**
This notebook demonstrates a simple AI project to predict monthly temperatures using a Decision Tree Classifier.

Project Overview
The goal of this project is to build a basic model that can predict whether the temperature for a given month is 'high' or 'low' based on historical temperature data.

Data
The dataset consists of:

Months: An integer representing the month of the year (1-12).
Temperature: The corresponding temperature for that month.
Model
A DecisionTreeClassifier from the sklearn library is used to train the model. The 'Months' are used as input features (X), and 'Temperature' is the target variable (y).

Usage
The notebook allows you to input a month (1-12) and get a prediction for its temperature. It will also classify the temperature as 'high' (>= 25 degrees) or 'low' (< 25 degrees).
