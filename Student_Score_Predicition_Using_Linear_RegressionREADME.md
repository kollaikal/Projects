# Student Scores Prediction Using Linear Regression

## Overview
This project implements a simple linear regression model to predict student scores based on the number of study hours. The dataset is sourced from an online repository and is used to train and evaluate a linear regression model.

## Prerequisites
Before running the script, ensure you have the following Python libraries installed:
- matplotlib
- pandas
- numpy
- scikit-learn

You can install missing dependencies using:

"pip install matplotlib pandas numpy scikit-learn'


## Dataset
The dataset used is obtained from [](http://bit.ly/w-data) and consists of two columns:
- Hours: Number of study hours
- Scores: Percentage score obtained

## Steps in the Code
1. **Load the dataset**: The dataset is read into a Pandas DataFrame.
2. **Visualize the data**: A scatter plot is generated to observe the relationship between study hours and scores.
3. **Prepare the data**: The dataset is split into training and testing sets (80-20 split).
4. **Train the model**: A linear regression model is trained using the training data.
5. **Visualize the regression line**: The best-fit regression line is plotted.
6. **Make predictions**: The model predicts scores for the test dataset.
7. **Evaluate performance**: The model's accuracy is evaluated using metrics such as:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R-squared score (R2)
8. **Custom prediction**: The model predicts a score for a student who studies 9.25 hours.


## Expected Output
- A scatter plot of study hours vs. scores.
- A linear regression line fitted to the data.
- A bar chart comparing actual vs. predicted scores.
- Evaluation metrics such as MAE, MSE, RMSE, and R2 score.
- Predicted score for a student studying 9.25 hours.

## Example Prediction Output
No of Hours = 9.25
Predicted Score = 93.69
