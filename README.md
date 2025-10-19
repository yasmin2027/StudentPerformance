# Project Overview

This project predicts students' exam scores based on key performance factors such as study hours, teacher quality, and parental education.
By using Linear Regression, the model identifies how study hours and other factors influence student performance.

# Objectives

Clean and preprocess the dataset (handle missing values).

Visualize relationships between factors (e.g., hours studied, teacher quality).

Train and evaluate a Linear Regression model to predict exam scores.

Measure model performance using MAE, MSE, and R² score.

# Dataset Information

The dataset used is StudentPerformanceFactors.csv, which contains features like:

Feature	Description
Hours_Studied	Number of hours studied per week
Exam_Score	Student's exam result (target variable)
Teacher_Quality	Rating of teacher quality
Parental_Education_Level	Parents' highest education level
Distance_from_Home	Distance of the student’s home from school
School_Type	Type of school (Public or Private)
Internet_Access	Whether the student has internet access
Motivation_Level	Self-reported motivation level

# Libraries Used

Pandas → Data handling and cleaning
Matplotlib → Data visualization
Scikit-learn (sklearn) → Model training and evaluation

# Steps in the Project

1-Load Dataset

  Read and explore the CSV file using pandas.

2-Data Cleaning

  Filled missing values with the most frequent value (mode) for categorical features.

3-Data Visualization

   Created bar charts and line plots to visualize the distribution of categorical and numeric variables.

4-Model Building

  Split the data into training and testing sets (80/20).
  Trained a Linear Regression model to predict Exam_Score from Hours_Studied.

5-Model Evaluation

  Calculated the following metrics:
  MAE (Mean Absolute Error)
  MSE (Mean Squared Error)
  R² Score

6-Visualization of Results

  Compared actual vs predicted exam scores using a scatter and regression line plot

