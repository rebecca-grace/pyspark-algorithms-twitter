# Twitter Data: Word2Vec and collaborative filtering

### 1. Folder Structure

```python
MKGFormer
 |-- tweet-data-code.ipynb	# Main code notebook
 |-- tweets.json    # Input text data
```

## 2. Overview

This project implements 2 analysis workloads using Twitter tweets data.

1. Finding the top 5 users with similar interests as a given Twitter user id. The involves using tweet information to create a document representation of the tweet IDs each user ID has interacted with, then using Word2Vec to calculate the similarity.
2. The second workload uses an ALS (Alternating Least Squares) collaborative filtering algorithm to suggest to a given user ID similar users to mention in a tweet. This is based on similarity between mention users they have mentioned in the past.