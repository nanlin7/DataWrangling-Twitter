# WeRateDogs Twitter Data Wrangling

## Overview

In this project, my goal is to wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualization. WeRateDogs is a very popular Twitter account with over 5.68M followers and has received more than 130K likes. WeRateDogs gained its popularity by rating people’s uploaded image of their dogs and gave a humorous comment about the dog. Their rating system is based on fraction with the denominator fixed at 10 and the numerator is always greater than 10 because “They are good dogs Brent”.

## Data Sources
The data are from three different sources:
- Enhanced Twitter archive in the form of a CSV file. This file contains basic tweet
information such as tweet ID, timestamp, text, etc.
- Additional JSON data extracted via the Twitter API using the Python’s Tweepy library
based on the tweet IDs from above archive.
- The neural network predictions results downloaded programmatically using the Requests
library. This table presents the classification results of each image alongside each tweet
ID, URL, and the confidence level.
After iteratively assessing and cleaning data from these three sources, I conducted exploratory data analysis on the cleaned dataset. 


