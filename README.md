# Amazon Customer Review Sentiment Analysis

This repository contains a machine learning model for sentiment analysis of Amazon customer reviews.  The model predicts whether a review is positive or negative based on the text of the review.

## Dataset

The dataset used for training and evaluation consists of Amazon customer reviews, labeled with sentiment scores.  Preprocessing steps included removing stop words and handling missing values.

## Model

Multiple classification models were trained and evaluated, including:

* Logistic Regression
* Naive Bayes
* Decision Tree
* Random Forest

The best performing model was selected based on accuracy and saved for future use.  A confusion matrix was generated to visualize model performance.

## Usage

1. **Data Preparation**: Ensure the 'AmazonReview.csv' dataset is in the same directory.

2. **Model Execution**: Run the provided Python script.  The script will train and evaluate the models, select the best one, and save it as `best_model.sav`.

3. **Prediction**:  The script demonstrates prediction on a new set of data to assess the model's performance on unseen reviews.


## Dependencies

* pandas
* scikit-learn
* matplotlib
* wordcloud
* nltk
