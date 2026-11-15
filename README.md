# maybelline-customer-sentiment-analysis
# Maybelline Customer Review Mining and Sentiment Analysis

## 1. Introduction

This project focuses on analyzing customer opinions about Maybelline Fit Me Matte + Poreless Foundation using YouTube comments.

The main purpose is to understand customer satisfaction and identify positive, negative, and neutral opinions about the product.

## 2. Project Objectives

- Collect customer comments from YouTube.
- Clean and preprocess the collected data.
- Perform sentiment analysis.
- Classify comments into Positive, Negative, and Neutral categories.
- Visualize customer opinions using graphs.
- Identify commonly used positive and negative words.

## 3. Tools and Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- YouTube Data API v3
- VADER Sentiment Analyzer

## 4. Data Collection

Customer comments were collected from public YouTube videos related to Maybelline Fit Me Foundation using the YouTube Data API.

The collected dataset includes:
- Video ID
- Customer Comment
- Likes
- Published Date

## 5. Data Preprocessing

The collected comments were cleaned by:
- Removing empty comments.
- Removing duplicate comments.
- Converting text into lowercase.
- Removing URLs and unwanted characters.
- Removing extra spaces.

## 6. Sentiment Analysis

VADER Sentiment Analyzer was used to classify customer comments into three categories:

- Positive
- Negative
- Neutral

## 7. Data Visualization

Bar charts and pie charts were created to visualize the distribution of customer sentiments.

## 8. Project Files

- `Maybelline_Sentiment_Analysis.ipynb`
- `positive_reviews.csv`
- `negative_reviews.csv`
- `neutral_reviews.csv`
- `final_maybelline_sentiment.csv`
- `sentiment_bar_chart.png`
- `sentiment_pie_chart.png`

## 9. Conclusion

This project analyzes customer opinions about Maybelline Fit Me Matte + Poreless Foundation using YouTube comments. The collected comments are cleaned and classified into Positive, Negative, and Neutral categories using VADER sentiment analysis.

The results help understand customer opinions and identify common positive and negative feedback.

## 10. Limitations

- VADER is primarily designed for English text.
- Sarcasm and context may affect sentiment classification.
- Results depend on the available YouTube comments.


