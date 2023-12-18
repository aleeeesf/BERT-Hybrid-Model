# Social Media Sentiment Analysis with BERT Hybrid Model
This repository contains a proposed hybrid model for sentiment analysis in Spanish tweets. It combines features extracted by BERT with post metadata to enhance the accuracy of sentiment analysis.

## Model decription
The model utilizes the BERT architecture to extract text features and combines them with a Multilayer Perceptron (MLP) that receives post metadata. This integration of textual features and metadata improves the understanding of sentiment expressed in tweets.

![image](/hybrid.png)

## Dataset Structure
The dataset is proprietary and not available at the moment. It consists of 6078 records of Spanish tweets. Each record has the following attributes:

+ favorite_count: Number of "likes" received by the tweet.
+ retweet_count: Number of times the tweet has been retweeted.
+ user_followers_count: Quantity of followers of the user who posted the tweet.
+ user_friends_count: Number of users followed by the user.
+ user_favourites_count: Number of tweets marked as favorites by the user.
+ user_statuses_count: Total number of tweets published by the user.
+ user_verified: Indicates whether the user is verified or not.
+ user_has_extended_profile: Indicates whether the user has an extended profile.
+ user_default_profile: Indicates whether the user uses the default profile.
+ preprocessed: Preprocessed text of the tweet.
