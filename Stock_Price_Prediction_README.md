## Stock Price Prediction with Sentiment Analysis
This project aims to predict the stock prices of BSE Sensex (BSESN) based on historical stock data and news sentiment. It utilizes machine learning models like Random Forest, Decision Tree, XGBoost, and AdaBoost for regression. The model is enhanced with sentiment analysis of the news headlines, using tools such as TextBlob and VADER for subjectivity and polarity scores.

# Project Overview**
The primary goal of this project is to explore how the sentiments of daily news headlines can impact stock prices. The dataset used in this project includes historical stock price data and news headlines from India, specifically the BSESN stock index. The steps involved in the process include data collection, preprocessing, feature engineering, sentiment analysis, and machine learning modeling for stock price prediction.

# Key Components:**
Stock Data: Historical stock prices from Yahoo Finance.
News Data: Daily news headlines related to the stock market.
Sentiment Analysis: Using TextBlob and VADER to analyze news sentiment.
Feature Engineering: Combining stock data and sentiment features.
Machine Learning Models: Random Forest, Decision Tree, XGBoost, and AdaBoost.
Table of Contents
Installation
Dataset
Sentiment Analysis
Machine Learning Models
Results
Conclusion
License
Installation
To get started with this project, clone the repository and install the necessary dependencies.

# Clone the repository:**
bash
Copy
Edit
git clone https://github.com/your-username/stock-price-prediction.git
cd stock-price-prediction

# The dataset is composed of two parts:

India News Headlines: Contains daily headlines from Indian news sources.
Data File: india-news-headlines.csv from kaggle
Columns: Date, Category, News
Stock Data: Historical stock prices of BSE Sensex.
Data File: ^BSESN.csv
Columns: Date, Open, High, Low, Close, Volume

# Sentiment Analysis
The sentiment analysis component extracts the sentiment from the news headlines using two methods:

TextBlob: Calculates subjectivity and polarity for each headline.
VADER (Valence Aware Dictionary and sEntiment Reasoner): Extracts positive, negative, and neutral scores for each headline.
This sentiment data is then merged with stock data to create a more comprehensive dataset for prediction.

# Machine Learning Models
Four different machine learning models are used for stock price prediction:

Random Forest Regressor
Decision Tree Regressor
XGBoost Regressor
AdaBoost Regressor
Each model is trained on the data, and the prediction errors are calculated using Mean Squared Error (MSE). The model performance is evaluated based on the MSE value, and it is concluded that Random Forest Regressor performs the best.

# Results
Here are the Mean Squared Errors for each model:

Random Forest: 0.0329
Decision Tree: 0.0699
XGBoost: 0.0466
AdaBoost: 0.0356
From the results, Random Forest outperforms the other models in terms of prediction accuracy.

# Conclusion
The project successfully predicts stock prices using both historical data and sentiment analysis of news headlines. The Random Forest model provides the best performance among all tested models. Sentiment analysis adds a new dimension to predicting stock prices by leveraging the impact of news sentiment.
