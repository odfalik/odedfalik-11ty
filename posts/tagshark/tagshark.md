---
title: Tagshark - Twitter Geolocation and Sentiment Analysis
date: '2020-11-18'
github: 'https://github.com/odfalik/tagshark'
topics: [Big Data, Python, Spark, Sentiment Analysis]
---

Tagshark is a Twitter geolocation and sentiment dashboard built with Pyspark, Elasticsearch, Kibana Dashboard.

Started as a university assignment for my Big Data class, the foundation of Tagshark consists of two Python scripts.
One uses the Tweepy API to stream Tweets from Twitter containing a keyword such as '#covid19'.
Each tweet's relevant information is passed over socket to the Pyspark process which handles geolocation (using geopy), sentiment
analysis (using VADER), and indexing (using Elasticsearch).

With the data streamed into Elasticsearch, I built a dashboard using Kibana to visualize our data.
