# Natural-Language-Processing
Tales from the Cypto 


Background
There's been a lot of hype in the news lately about cryptocurrency, so you want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

In this assignment, you will apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. You will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

Complete the following tasks:

Sentiment Analysis
Natural Language Processing
Named Entity Recognition
Files
Starter Notebook

Homework Guide
Guide for the homework including which lesson each concept was introduced in and tips for a great submission!

Instructions
Sentiment Analysis
Use the newsapi to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.

Use descriptive statistics to answer the following questions:

Q: Which coin had the highest mean positive score?

A: Bitcoin with the higher mean of 0.041000

Q: Which coin had the highest compound score?

A: Ethereum with a max compound score of 0.91200

Q. Which coin had the highest positive score?

A: Ethereum with a highest positive score of 0.278000

Natural Language Processing
In this section, you will use NLTK and Python to tokenize the text for each coin. Be sure to:

Lowercase each word
Remove punctuation
Remove stop words
Next, look at the ngrams and word frequency for each coin.

Use NLTK to produce the ngrams for N = 2.
List the top 10 words for each coin.
Finally, generate word clouds for each coin to summarize the news for each coin.
