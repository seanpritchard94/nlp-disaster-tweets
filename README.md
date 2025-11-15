# Overview #

## Project Info ##

- Developed by: Sean Pritchard
- for: CSCA 5642: Introduction to Deep Learning
- URL: https://github.com/seanpritchard94/cancer-detection
- Data Source: https://www.kaggle.com/competitions/nlp-getting-started/data (Howard et al., 2019)
- Python version: 3.13

## Data Collection and Provenance ##

"This dataset was created by the company figure-eight and originally shared on their ‘Data For Everyone’ website" (Howard et al., 2019). The data represents tweets that may or may not be about a disaster. The training data has been hand-labeled. The data is now offered in relation to a Kaggle competition. The Kaggle competition uses the F1 metric to evaluate success of a submission.

## Deep Learning Problem Description ##

**Type of Learning and Task:** This is a **binary classification** deep learning problem. It relies on **natural language processing (NLP)** techniques to convert the tweets to vector data. I will build a **Recurrent Neural Network** deep learning model capable of classifying the tweets in the data set.

**Project Goal:** Build a deep learning model capable of classifying the tweets with **at least 90% validation accuracy**.

## Data Description ##

The dataset contains 7613 labeled tweets. 4342 are non-disaster (label 0), and 3271 are disasters (0). All rows contain text and a target. Almost all (7552) contain keywords, and most (5080) contain location.

## Notebook ##

All work is contained in **disaster-tweets.ipynb**

The notebook expects the dataset and twitter-trained GloVe model have been downloaded to the /data directory.