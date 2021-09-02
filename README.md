# Twitter_Data_Analysis

Twitter Data Analysis Using Spark
Nowadays, data is growing and accumulating faster than ever before. Currently, around 90% of all data generated in our world was generated only in the last two years. Due to this staggering growth rate, big data platforms had to adopt radical solutions in order to maintain such huge volumes of data.

Spark Streaming discretizes the data into tiny, sub-second micro-batches. In other words, Spark Streaming receivers accept data in parallel and buffer it in the memory of Spark’s workers nodes. Then the latency-optimized Spark engine runs short tasks to process the batches and output the results to other systems.Unlike the traditional continuous operator model, where the computation is statically allocated to a node, Spark tasks are assigned to the workers dynamically on the basis of data locality and available resources.This enables better load balancing and faster fault recovery.

One of the main sources of data today are social networks.We worked on dealing, analyzing, and extracting insights from social network data in real time using one of the most important big data echo solutions out there—Apache Spark, and Python.

We build a simple application that reads online streams from Twitter using Python, then processes the tweets using Apache Spark Streaming to identify hashtags and, finally, returns top trending hashtags and represents this data in real-time.We also worked on historical data and made analatical insights on it.

# Technology Used
1. Apache Spark
2. Spark SQL
3. Spark Web UI
4. Python
5. Git + GitHub

# Problem statement

1. Historical Data Analysis on "ELON MUSK" from 30-01-2015 to 14-07-2020
2. Analyse the real time streaming tweets of famous personality (Politicians or actors).
3. Retrieving the trending hashtags of a famous personality.
4. To fetch the location of a person who has retweeted on particular hashtag.
5. Fetching the user details who retweeted with the name "ELON MUSK"

# API and Required Modules

- Twitter API - for Building Apps and analyzing on twitter streaming & historical data
- Tweepy - is an open source Python package that gives you a very convenient way to access the Twitter API with Python.

# DataSet Link

- https://www.kaggle.com/vidyapb/elon-musk-tweets-2015-to-2020/version/1

