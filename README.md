# Twitter-Sentiment-Analysis
Analyzing the sentiment in tweets using natural language processing (NLP) techniques and Python libraries like Scikit-learn, Pandas, NumPy, and NLTK. This project preprocesses tweet data, tokenizing text, and leveraging machine learning algorithms, the model can classify tweets into positive, negative, or neutral sentiment categories. It demonstrates practical applications of NLP for real-time social media analysis. 

**Project Overview**
This project focuses on analyzing the sentiment of tweets by using a machine learning model based on Logistic Regression. The goal is to classify tweets as positive or negative by extracting features from the text data and training a classifier. Sentiment analysis is a crucial task in natural language processing (NLP) for understanding the public opinion or emotions expressed in text data.

**Features**
1. Preprocessing of raw tweet text (cleaning, tokenization, stopword removal)
2. Feature extraction using TF-IDF Vectorization
3. Sentiment classification using Logistic Regression
4. Performance evaluation with accuracy, precision, recall, and F1-score
5. Visualization of results

**Dataset**
The dataset contains 1,600,000 tweets extracted using the twitter api. The tweets have been annotated (0 = negative, 1 = positive) and they can be used to detect sentiment.
It contains the following 6 fields:
**target**: the polarity of the tweet (0 = negative, 1 = positive)
**ids**: The id of the tweet ( 2087)
**date**: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
**flag**: The query (lyx). If there is no query, then this value is NO_QUERY.
**user**: the user that tweeted (robotickilldozr)
**text**: the text of the tweet (Lyx is cool)

**Requirements**
The project requires the following libraries to run:

Python 3.x
numpy (for numerical computations)
pandas (for handling data frames)
scikit-learn (for machine learning and preprocessing)
nltk (for natural language processing tasks)
