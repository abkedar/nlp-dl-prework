### Project Overview

 In this project the dataset are news pages collected from an web aggregator in the period from 10-March-2014 to 10-August-2014. The resources are grouped into categories that represent pages discussing the same story. News categories included in this dataset include business(b); science and technology(t); entertainment(e); and health(h).

The goal is to predict which class a particular resource belongs to given the title of the resource.


### Learnings from the project

 The NLP technique and algorithm used to complete this project are :

- Preprocess text data with tokenization, stopword removal 

- Vectorize data using Bag-of-words and TF-IDF approaches. 

- Split the data into Train and Test set.(Train,Test)

- Apply classifiers (Logistic and Multinomial Naive Bayes) to perform multi-class classification


### Approach taken to solve the problem

 The data has 422937 resources as mention above from where it was collected. This data was too messey and has unwanted data too. So First task was toconvert into small chunks, as we can't remove it completely or randomly. Then remove data wich we can't use in our project to classify the data category and again join all data with important keyword data together. This data was needed to categorize according to our required Classification category. For that It was necessary to identify those keywords so we can classify them accordingly or number of time a words occured in whole document. Thus to solve this above problem I used above mentioned technique where ever it was needed.


