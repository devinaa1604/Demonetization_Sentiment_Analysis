# Sentiment Analysis on Demonetization in India
![](Images/demonitization-india.png)


## Background
The demonetization of ₹500 and ₹1000 banknotes was a step taken by the Government of India on 8 November 2016, ceasing the usage of all ₹500 and ₹1000 banknotes of the Mahatma Gandhi Series as a form of legal tender in India from 9 November 2016.

The announcement was made by the Prime Minister of India Narendra Modi in an unscheduled live televised address to the nation at 20:15 Indian Standard Time (IST) the same day. In the announcement, Modi declared circulation of all ₹500 and ₹1000 banknotes of the Mahatma Gandhi Series as invalid and announced the issuance of new ₹500 and ₹2000 banknotes of the Mahatma Gandhi New Series in exchange for the old banknotes. Ever since then, there have been multiple debates about the decision and effects of it. 

This project aims to understand the sentiments in the population of India right after the announcement was made. 

## Data
The data set was picked up from [Kaggle](https://www.kaggle.com/arathee2/demonetization-in-india-twitter-data).

It contains 14,940 tweets ranging from Nov 8th 2016 to the end of 2017. 

## Data Cleaning
Removed
- Links
- Retweets
- Converted everything to lower case
- Usernames
- Tabs
- Blank spaces before and after the tweets
- Punctuation

Removed stop words after unnesting tweets

## Analysis
### Top 15 words
This gives a count of top 15 unique words that are most used in the tweets. 

<img src="Images/Top_15_Words.png" width="600" height="450">

### Word Cloud
Here, the red words show negative words and the green are the positive words. This was made by using the Bing Lexicon.

<img src="Images/WordCloud.png" width="600" height="450">

### Results of NRC Lexicon
NRC Lexicon analyzes the words on a spectrum of 8 emotions: Anger, Anticipation, Disgust, fear, Joy, Sadness, Surprise, and Trust. 

Here, trust is highest and still not too far behind is fear. This aligns with the fact that India is the biggest democracy in the world, policies of the government are supported by the majority with a feeling of trust however, a big change like this also bring in the feeling of fear. 

<img src="Images/NRCLexicon.png" width="600" height="500">

### Overall Sentiment
Even in the previous plot, even through the highest feeling was of trust, the other feelings that followed that were of fear, anger and sadness. Therefore, the cumulative total shows a overall negative feeling. 

<img src="Images/Overall_Sentiment.png" width="600" height="500">
