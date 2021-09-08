# Tales from the Crypto

![Stock Sentiment](Images/sentimental.jpeg)

## Background

There's been a lot of hype in the news lately about cryptocurrency, so I wanted to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

In this assignment, I applied natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. I also applied fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

Complete the following tasks:

1. [Sentiment Analysis](#1---Sentiment-Analysis)
2. [Natural Language Processing](#2---Natural-Language-Processing)
3. [Named Entity Recognition](#3---Named-Entity-Recognition)

---

## Files

[Starter Notebook](Starter_Code/crypto_sentiment.ipynb)

---

## Instructions

----

### 1 - Sentiment Analysis

Using the [newsapi](https://newsapi.org/) I pulled the latest news articles for Bitcoin and Ethereum and created a DataFrame of sentiment scores for each coin.

I used descriptived statistics to answer the following questions:

> Which coin had the highest mean positive score?
>   Bitcoin with score of .068100

> Which coin had the highest negative score?
>   Ethereum with a max compound score of .735100

> Which coin had the highest positive score?
>   Ethereum with score of .167000

---

### 2 - Natural Language Processing

In this section, I used NLTK and Python to tokenize text, find n-gram counts, and create word clouds for both coins. 

#### Tokenize

I completed the following tasks:

1. Lowercase each word.
2. Remove punctuation.
3. Remove stop words.

#### N-grams

Next, I looked at the ngrams and word frequency for each coin.

1. Used NLTK to produce the ngrams for N = 2.
2. Listed the top 10 words for each coin.

#### Word Clouds

Finally, I generated word clouds for each coin to summarize the news for each coin.

![btc-word-cloud.png](Images/btc-word-cloud.png)

![eth-word-cloud.png](Images/eth-word-cloud.png)

---

### 3 - Named Entity Recognition

In this section, I built a named entity recognition model for both coins and visualize the tags using SpaCy.

![btc-ner.png](Images/btc-ner.png)

![eth-ner.png](Images/eth-ner.png)

---

## Resources

[Vader Sentiment Analysis](http://www.nltk.org/howto/sentiment.html)

---