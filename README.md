# Udacity-Data-Wranging-Project
This project is based on the WeRateDogs Twitter account user @dog rates's tweet archive. WeRateDogs is a Twitter account that rates users' dogs and adds a lighthearted comment. The denominator of these scores is almost always 10. however, the numerators? frequently more than 10. 11/10, 12/10, 13/10, etc. Why? because "Brent, they're good dogs." Over 4 million people follow WeRateDogs, and it has been featured in international media.

Three sources contribute to the dataset:

WeRateDogs downloaded and emailed Udacity their Twitter archive. This database includes all 5000+ of their tweets as of August 1, 2017, along with the text, extract rating, dog name, and dog stage. Manually downloading this file

A file that predicts the breed of dog based on the images. This file includes the tweet ID, picture URL, and image number, among other things. It is hosted on Udacity's servers and should be downloaded programmatically using the Requests library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad image-predictions/image-predictions.tsv

Using the tweet IDs from the WeRateDogs Twitter archive to find each tweet's retweet and favorite ("like") counts, then querying the Twitter API with Python's Tweepy package to obtain each tweet's JSON data.

The daset were cleaned and merged. I derived the following insights:

most tweets were posted using n Iphone. This could be because most of the tweets came from WeRateDogs page
golden retriever is the most popular dog breed. This could be be because they are most common bred breed
Most popular dog names are Cooper, Charlie and Lucy. This could be because the page are based in the United State of America. In other regions we may find different names
The most retweeted dog is seen swimming in the pool with a pair of sunglasses in it's mouth. It's quite an interesting photo which many may not have seen before. This could be the reason why many of their followers retweeted it
