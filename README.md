



# News Headline Generator (Abstractive)
![Header](https://github.com/avithekkc/movie-reviews-sentiment-analysis/blob/main/images/p5-header.jpg?raw=true)
## Overview
This project seeks to create a model that creates one line abstractive summary of a given news article. This model will help to get a quick idea on what the article is all about without having to read all whole news.


## Business Problem
News/Media/Blogging Companies always wants a catchy headlines for the articles they post so that they can get maximum number of clicks. A machine learning algorithm can be used to create a headline based on the context of the article.

## Data
The data was collected from various sources like Kaggle and Github.
Because of the Computational resource limitation the model was trained on 100K News Article having with input length of 100 words and out length of 16 words.

## OSMEN Process
 1. Obtaining data
 2. Scrubbing data
 3. Exploring data
 4. Modeling data
 5. Interpreting results
 
 
## About Modeling Technique


##  Results
2 classification models were performed to determine best fit:
Logistic Regression and Multinomial Naive Bayes.
The Logistic Regression Model reported to be the best model for predicting Sentiment from given movie review using TFIDF Technique.

ACCURACY : 93%  ( TRAIN) and 91%  ( TEST)

The WebApp version of the project can be found here - [Github](https://github.com/avithekkc/news-headline-web-app)

##  Next Steps
-   Adding Attention Layer.
    
-   Using Bi-directional LSTM.
    
-   Using pre-trained Embeddings.


##   Repository Structure
```
├── datasets                            <- data used for the analysis.
├── images                              <- All images used throughout the project.
├── data-cleaning.ipynb                 <- Cleaning of data to create final dataset.
├── LSTM.ipynb                          <- Data Modeling.
├── presentation.pdf                    <- Non Technical Presentation.
└── readme.md                           <- README file for Quick overview on project.
```
