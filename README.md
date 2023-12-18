# IMDB_sentiment_four_methods
## This is a personal repository for the Kaggle's IMDB sentiment analysis.

### These jupyter notebooks do sentiment analysis of IMDB reviews using the four different methods. Most solutions show one method over another, but these notebooks show the Kaggle challenge can be done using various methods. So, they provide practical examples of applying machine learning and deep learning methods to the same task.
Used methods are as follows: 
### 1. perceptron with count and tfidf vectorizers
   When using all of the 1-, 2- ,3- , and 4-grams with the tfidf vectorizer, the accuracy reaches 91.3%.
### 2. logistic regression with count and tfidf vectorizers
   Using 1,2, and 3-grams together with the count vectorizer yields the same accuracy of 91.3%
### 3. SequenceClassification model using the ELECTRA-small-discriminator checkpoint (IMDB NN.ipynb)
   I used the transformer library and fine-tuned the ELECTRA-small-discriminator with training on the dataset. 
   The accuracy reached over 93% in the thrid epoch.
### 4. Hugging Face (HF) pipeline
  Lastly, I used a quick but powerful fix using the Hugging Face pipeline with bert and distilbert with truncation.


