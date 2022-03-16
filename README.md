# dataScienceLabEval
In this lab evaluation we have to do Amazon pet product reviews classification .

These are the steps to be done -

1)Load data

2)Perform preprocessing

3)Apply suitable Model and compare results



Summary

--Importing the libraries


--Reading the dataset

 We'll be validating with train + validation files.
 
 
--DATA PREPROCESSING

 check null values
 
 apply label encoding
 
 do visualisation
 
 
--text preprocessing

 Steps-

1.Remove Punctuations

2.Remove HTML Tags

3.Convert text to lowercase

4.Remove all special characters

5.Remove stopwords

6.Perform Stemming

7.Join back after stemming


--Machine Learning models CUML

I have used the following models -

1.logistic regression - In one-vs-rest logistic regression (OVR) a separate model is trained for each class predicted whether an observation is that class or not (thus making it a binary classification problem).

2.Random Forests - As the name suggests, "Random Forest is a classifier that contains a number of decision trees on various subsets of the given dataset and takes the average to improve the predictive accuracy of that dataset."

3.Naive Bayes - Naïve Bayes Classifier is one of the simple and most effective Classification algorithms which helps in building the fast machine learning models that can make quick predictions. It is a probabilistic classifier, which means it predicts on the basis of the probability of an object.


--conclusion

cu_score_naive_bayes=0.1135

cu_score_random_forest=0.5155

cu_score_log_reg=0.5384


--What we can try next

tune hyperparams, those of TfIdfVectorizers as well

add Word2Vec/GloVE/Fasttext embeddings, at least for titles

switch to ULMFiT and other heavy stuff

We can try to use BERT Keras
