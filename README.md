# Sentiment Analysis For Mental Health
This repository contains the code used for a natural language processing (NLP) project I undertook as part of my Master's Degree. The project explored several approaches to detecting and flagging mental health problems within social media comments and posts.

The two primary approaches explored were:
* PCA-transformed TF-IDF vectors within a support vector machine.
* Pre-trained BERT embeddings within a multi-layer perceptron.

Both achieved reasonably good F1 scores with averages of 0.75 and 0.7 respectively across the seven different classes. Further work could be done exploring fine-tuned BERT embeddings, allowing for more granularity to be captured between the different classes. 
