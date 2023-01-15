---
title:  "WeRateDog Twitter Account Analysis"
mathjax: true
layout: post
categories: media
---


![dog_image](https://user-images.githubusercontent.com/96656540/212531909-0b61fc95-2ee7-49ce-9299-9e1e82735066.jpg)

# Project Description
WeRateDogs is a Twitter account with over 9.2 million followers that rates dogs above the rating numerator of 10. e.g 13/10, 14/10, 12/10 etc. 
Data of these tweets were gathered manually and programmatically as twitter_archive_enhanced.csv, image.predictions.tsv and tweet_json using various 
Python libraries like Request and Tweepy. The gathered data were loaded as twitter_archive, image_prediction and df_tweet for data wrangling and visualization. 
Thereafter, the cleaned files were combined into a file called twitter_master_archive.csv.
The combined data was then analyzed and visualized to draw insights into the data. The results of this analysis are as follows;

# Highest Liked Dog
The Dog stage consists of four stages: doggo, floofer, pupper, puppo. 
A visualization of the dog stage and favorite count shows that pupper dog stage has the highest favorite count.

![Highest_liked_dog](https://user-images.githubusercontent.com/96656540/212532309-b589e3e8-6b13-4f88-b374-31705a2b7185.png)

# Highest Occurrence of Dog Name
Here, 850 names of dogs were visualized taking the frequency of the highest occurrence. The visualization shows Copper has the highest occurrence.

![Highest_occurence_of_Dog_Names](https://user-images.githubusercontent.com/96656540/212532436-2bc7845e-2740-4de4-993a-867c18e6f74c.png)

# Breed Predictions
The predictions of dog breeds was generated through a neural network that can classify dog breeds. The dog breeds were categorized into p1, p2, and p3. 
The most frequent dog breed prediction for p1 was Golden Retriever while the most frequent for p2 was Labrador Retriever and Cardigan and for p3 was Labrador Retriever.

# Golden Retriever and Labrador Retriever
![breed_prediction](https://user-images.githubusercontent.com/96656540/212533166-cf84382b-3f59-4918-b7b2-3df0e5fea207.png)

Code of this project can be found [here on Github](https://github.com/sakinahali/We_Rate_Dogs-Dataset)
