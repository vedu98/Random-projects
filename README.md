# SpamClassifier
Here Different types of vectorizing techniques for converting text into vectors. 
These include:-

1.Bag of words:-The bag-of-words model is a simplifying representation used in natural language processing and information retrieval (IR). In this model, a text (such as a sentence or a document) is represented as the bag (multiset) of its words, disregarding grammar and even word order but keeping multiplicity

2.TF-IDF vectorizer:-TF-IDF is a statistical measure that evaluates how relevant a word is to a document in a collection of documents. This is done by multiplying two metrics: how many times a word appears in a document, and the inverse document frequency of the word across a set of documents.

3.TFIDF-Word2vec:-in this method first, we will calculate tfidf value of each word. than follow the same approach as above section by multiplying tfidf value with the corresponding word and then divided the sum by sum tfidf value.

PreProcessing of the Data :-
Before applying the above techniques the data is first preprocessed and then vecotrized. The data is clean by removing stopwords and special characters and then it it lowercased  using regex expressions.
