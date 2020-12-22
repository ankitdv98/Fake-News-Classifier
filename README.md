# Fake-News-Classifier
Link to Dataset: https://www.kaggle.com/c/fake-news/overview

Dataset imported from Kaggle
Task: Build a Fake News Classifier using Natural Language Processing techniques
      Problem is Supervise Learning where text data of News Titles and News Body is labelled as {0: "Reliable", 1: "Unreliable"} 
      Class labels are balanced 
Text Preprocessing: Removed Missing Data
                    Tokenized sentences into words
                    Removed Stopwords using NLTK library
                    Applied Stemming on words
                    Joined words back to sentences
                    Created Corpus of cleaned text
Classifier: 
1. Created bag of words using CountVectorizer and transformed words in terms of frequency of occurance
   Build Naive Bayes Classifier and performed Hyperparameter Tuning
2. Vectorized text in terms of tf-idf score of words
   Build Naive Bayes Classifier
3. Represented text into vectors with Word Embedding
   Created Recurrant Neural Network with Long Short Term Memory
   
Acheived Accuracy of 92% with good precision and recall
