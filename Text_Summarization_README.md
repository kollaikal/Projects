# Text Summarization Model Comparison (LSTM vs. Machine Learning Algorithms)
This repository showcases an experimental analysis of different algorithms for text summarization, aiming to improve accuracy in providing concise and informative summaries for news articles, product reviews, and other long-form content. Given the decline in manual reading post-COVID and the popularity of AI-driven models like GPT, this project aims to create a more efficient way to consume information quickly.

The thesis compares the performance of Long Short-Term Memory (LSTM) networks against traditional machine learning algorithms like Random Forest, Support Vector Machines (SVM), Logistic Regression, and K-Nearest Neighbors (K-NN) to determine the best model for summarizing large amounts of text.

# Research Motivation
After the COVID-19 pandemic, many individuals found it difficult to maintain long-form reading habits due to time constraints and a shift toward digital consumption. With the rise of tools like GPT, manual reading has been replaced by AI-powered content generation. However, there is still a significant demand for methods that can summarize text quickly and accurately, helping users consume content efficiently.

# Algorithms Compared
The following algorithms are used for comparison in this thesis:

LSTM (Long Short-Term Memory): A sequence-to-sequence model that handles long-range dependencies in text data. This model is trained to predict a sequence of words (summary) from the given input (news article or product review).
Random Forest: A versatile ensemble method used for classification and regression tasks. It builds multiple decision trees and aggregates their results for improved performance.
SVM (Support Vector Machine): A supervised learning algorithm used for classification tasks. It works by finding the hyperplane that best separates data points.
Logistic Regression: A simple yet powerful classification algorithm commonly used for binary and multiclass classification problems.
K-NN (K-Nearest Neighbors): A non-parametric algorithm that classifies new data based on the majority class of its nearest neighbors.

# Data Preprocessing
Text Cleaning: Removal of URLs, HTML tags, unnecessary characters, and stop words.
Tokenization: Both reviews and their summaries are tokenized using Keras' Tokenizer.
Padding: Sequences are padded to ensure consistent input lengths.
Feature Engineering: The text data is vectorized, and essential features are extracted for each algorithm.

# Evaluation Criteria
The models are evaluated based on the following:

Accuracy: The proportion of correctly predicted summaries.
Precision/Recall/F1 Score: Metrics used for classification models, especially when class imbalance is present.
Execution Time: The time taken by each algorithm to generate a summary.
Model Complexity: An analysis of how complex or computationally expensive each model is to train and use.

# Usage

Data Preparation:
Preprocess the dataset of text and summary pairs. Clean the text, remove stop words, expand contractions, etc.
Model Training:
Train each model (LSTM, Random Forest, SVM, Logistic Regression, K-NN) using the preprocessed data.
Performance Comparison:
Evaluate each model using the test set and compare the results based on accuracy, execution time, and other relevant metrics.
Result Analysis:
Analyze which algorithm provides the best trade-off between accuracy, performance, and efficiency in real-world applications.

# Results
This section will include a comparative analysis based on metrics such as accuracy, execution time, and model complexity, highlighting the pros and cons of each algorithm.

# Conclusion
Based on the evaluation, we conclude the best-performing algorithm for text summarization considering the trade-offs between accuracy and efficiency, offering potential improvements for applications where fast, reliable summaries are necessary.
