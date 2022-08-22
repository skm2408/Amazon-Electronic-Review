# Amazon-Electronic-Review

# Sentiment-analysis-on-amazon-reviews

This project showcases a comparative study between different machine learning models to perform sentiment analysis on the customer reviews of Amazon products in the Electronics category using two different vectorizer (Bag Of
Words and TF-IDF). The primary models we will look into for our analysis are Support Vector Machines, Logistic Regression, Random Forest Classifier, K-Nearest Neighbour.

## Dataset Source
Amazon Product Reviews Dataset (2018 Updated Version)<br>
https://www.kaggle.com/datasets/magdawjcicka/amazon-reviews-2018-electronics?select=electronics_small.csv

## Data Description
Includes reviews and corresponding ratings. Columns are following:

- overall - rating of the product (1 to 5)
- vote - helpful votes of the review
- reviewText - text of the review
- summary - summary of the review
- reviewTime - time of the review (raw)

## Result
| Model | Vectorizer Used | Accuracy |
------- | ------------- | -------- |
| Logistic Regression  | Count Vectorizer(Bag Of Words)  | 92.67  |
| Logistic Regression       | TF-IDF Vectorizer  | 92.95  |
| SVM  | Count Vectorizer(Bag Of Words)  | 91.76  |
| SVM        | TF-IDF Vectorizer  | 93.48  |
| KNN  | Count Vectorizer(Bag Of Words)  | 90.83  |
| KNN        | TF-IDF Vectorizer  | 90.85  |
| Random Forest  | Count Vectorizer(Bag Of Words)  | 92.22  |
| Random Forest        | TF-IDF Vectorizer  | 92.40  |
