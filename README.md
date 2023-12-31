# IMDB_sentiment_four_methods
## This is a personal repository for the Kaggle's IMDB sentiment analysis.

### These jupyter notebooks do sentiment analysis of IMDB reviews using the four different methods. Most solutions show one method over another, but these notebooks show the Kaggle challenge can be done using various methods. So, they provide practical examples of applying machine learning and deep learning methods to the same task.
Used methods are as follows: 
### 1. perceptron 
   I used both count and tfidf vectorizers and ran different models. When using all of the 1-, 2- ,3- , and 4-grams with the tfidf vectorizer, the accuracy reaches 91.3%.
### 2. logistic regression 
   Using 1,2, and 3-grams together with the count vectorizer yields the same accuracy of 91.3%
### 3. SequenceClassification model using the ELECTRA-small-discriminator checkpoint (IMDB NN.ipynb)
   I used the transformer library and fine-tuned the ELECTRA-small-discriminator by training it on the IMDB dataset. 
   The accuracy reached over 93% in the third epoch.
   The fine-tuned model can be downloaded at https://huggingface.co/knslee07/IMDB_sentiment_ELECTRA-small.
### 4. Hugging Face (HF) pipeline
  Lastly, I used a quick but powerful fix using the Hugging Face pipeline with bert and distilbert.


