                                    **Tiktok Review Sentiment Analysis**
This project performs sentiment analysis on TikTok reviews from the Google Play Store. 
By analyzing the sentiment of user reviews, we aim to understand user satisfaction and identify common themes in the feedback.

**Project Setup**
We begin by importing necessary libraries and loading the dataset. The libraries used include:
1.pandas: For data manipulation and analysis.
2.matplotlib.pyplot: For data visualization.
3.WordCloud: For generating word cloud visualizations.
4.nltk: The Natural Language Toolkit for natural language processing tasks.

**Explanation**
**Import Libraries**: We import several libraries essential for data processing, visualization, and sentiment analysis.
**Download Stopwords**: We download the stopwords corpus from NLTK to help with text preprocessing.
**Initialize Stemmer**: We initialize a SnowballStemmer to reduce words to their root form, aiding in consistent text analysis.
**Load Dataset**: We load the TikTok reviews dataset using pandas and display the first few rows to understand its structure.

**Text Preprocessing**
To ensure the text data is clean and ready for sentiment analysis, we define a preprocessing function that performs several cleaning steps.
This function removes unwanted characters, converts text to lowercase, removes stopwords, and applies stemming.

**Data Visualization: Rating Distribution**
To understand the distribution of ratings given by users, we create a pie chart that shows the proportion of each rating score.

**Data Visualization: Word Cloud**
To visualize the most frequently occurring words in the reviews, we generate a word cloud. This helps in identifying common themes and sentiments expressed by users.

**Sentiment Analysis**
To analyze the sentiment of the reviews, we use the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool from the NLTK library. 
This tool provides a robust way to classify the polarity of text.

**Data Visualization: Word Cloud for Positive Reviews**
To gain further insights into the most frequently mentioned words in positive reviews, we generate a separate word cloud for reviews with a higher positive sentiment score than negative sentiment score.

**Data Visualization: Word Cloud for Negative Reviews**
To gain further insights into the most frequently mentioned words in negative reviews, we generate a separate word cloud for reviews with a higher negative sentiment score than positive sentiment score.

**Summary and Future Work**
This project provides valuable insights into user opinions on TikTok by performing sentiment analysis and visualizing key themes.
