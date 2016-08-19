# Consumer-Fraud-Detection-with-Tweets-

## Background
This is a capstone team project at NYU CUSP 2016.

This project is sponsored by the office of Attorney General in New York state (OAG).

The outcome of this project is being emplemented in reality by OAG.

This project won the first prize in the NYU CUSP capstone presentation 2016.

## Goal
Detect fraud situation (Most complained companies/industries, trend, location, topics) in New York state through multiple data sources (OAG internal data, Twitter data, CFPB financial complaint data) 

## Challange
Pick up fraud relevent tweets from general tweets

Build a concise visualization tool with interaction for attorneys in OAG to detect fraud

## Data
Labled OAG internal complaint data (Confidencial)

Consumer Financial Protection Bureau(CFPB) Database

General Tweets scraped through twitter api  

## Implemented method/algorithm
transformation: Bag of word/ Tf-transforation/ bigram

classification model: Support Vector Machine/ Random Forest/ Naive Bayes

topic model: LSI/ LDA

vector space model: Word2Vec

validation: n-fold cross validation

## Implemented python library
NLTK, Gensim, Lda, Sklearn, Numpy, Scipy, Pandas, Matplotlib

## Outcome
A classification model for labling general tweets with fraud relevent or not, and industry categoary if fraud relecent

A vector space model for recongizing relationship(distence) between words from fraud narratives

A fraud detection visualization tool showing most complained companies/industries, fraud trend, location and narratives. Find it here: https://vimeo.com/179412528

######## reach me by tj763@nyu.edu


