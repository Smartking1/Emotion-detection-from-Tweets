# Emotion-detection-from-Tweets
Detecting Emotions of Tweets about upcoming Nigeria Election using Natural Language Processing

Detecting Emotions of Tweets about upcoming Nigeria Election using Natural Language Processing
In this article I will show a detailed step on how to detect the emotions behind tweets using NLP models. Detecting emotions behind tweets is very important because it can help to know when an individual making a tweet is in good mood and it can also help businesses  to understand how customers are reacting to their product or service.
DATA COLLECTION: The data used in this project was scraped from twitter, the dataset was about the upcoming Nigeria election. I scraped 60000 tweets containing the hashtag #NigeriaElection. Check out my previous post on how to scrape data from twitter without twitter developer keys
DATA PREPROCESSING: For the data preprocessing I wrote a method to remove tags, hyperlinks, emoticons, retweets and mentions from the dataset. I further went on to eliminate rows that contain non English words as my major focus was on the English words.
MODEL BUILDING: For the emotion detection of tweets I made use of the text2emotion python package which is used to extract emotion from text contents. The package is compatible with 5 different emotion categories as Happy, Angry, Sad, Surprise and Fear.
From the analysis using the visualization gotten after detecting the emotion of tweets
Emotion Analysis39.1% of the tweets were classified as Happy, this means that higher percentage of people are happy about the upcoming election.
23.8% of the tweets were classified as under Fear, this means that people are actually scared about the upcoming election but the percentage is not up to that of those that are happy.
16.2% of the tweets were classified as suprised 
14.8% were classified as Sad
6.1% were classified as Angry

Percentage classification of EmotionEmotion detection can also be applied to other text contents like Reviews, Articles to get the emotion of individuals about a particular concept, topic or product.
