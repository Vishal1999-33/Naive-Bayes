# Naive Bayes
Naive Bayes classifiers are a collection of classification algorithms based on Bayes’ Theorem. It is not a single algorithm but a family of algorithms where all of them share a common principle, i.e. every pair of features being classified is independent of each other.

#  Text Classification
Text Classification is an automated process of classification of text into predefined categories. We can classify Emails into spam or non-spam, news articles into different categories like Politics, Stock Market, Sports, etc.

This can be done with the help of Natural Language Processing and different Classification Algorithms like Naive Bayes, SVM and even Neural Networks in Python.

# Natural Language Processing
Short for natural language processing, NLP is a branch of artificial intelligence which is focused on the enabling the computers to understand and interpret the human language. The problem with interpreting the human language is that it is not a set of rules or binary data that can be fed into the system and understanding the context of a conversation or reading between the lines is altogether a different ball game.

However, with the recent advancement in Machine Learning, Deep Learning with the help of Neural Networks and easy to use models in python has opened the doors for us to code our way into making computers understand the complex human Language.

# Data Pre-Processing
Short for natural language processing, NLP is a branch of artificial intelligence which is focused on the enabling the computers to understand and interpret the human language. The problem with interpreting the human language is that it is not a set of rules or binary data that can be fed into the system and understanding the context of a conversation or reading between the lines is altogether a different ball game.

However, with the recent advancement in Machine Learning, Deep Learning with the help of Neural Networks and easy to use models in python has opened the doors for us to code our way into making computers understand the complex human Language.

# Below are some of the techniques involved in pre-processing:-

# Tokenization: 
This is a process of breaking a stream of text up into words, phrases, symbols, or other meaningful elements called tokens. The list of tokens becomes input for further processing. NLTK Library has word_tokenize and sent_tokenize to easily break a stream of text into a list of words or sentences, respectively.

# Word Stemming/Lemmatization: 
The aim of both processes is the same, reducing the inflectional forms of each word into a common base or root. Lemmatization is closely related to stemming. The difference is that a stemmer operates on a single word without knowledge of the context, and therefore cannot discriminate between words which have different meanings depending on part of speech. However, stemmers are typically easier to implement and run faster, and the reduced accuracy may not matter for some applications.

Here’s the complete script which performs the aforementioned data pre-processing steps:-

1)Remove Blank rows in Data, if any

2)Change all the text to lower case

3)Word Tokenization

4)Remove Stop words

5)Remove Non-alpha text

6)Word Lemmatization

# Word Vectorization
It is a general process of turning a collection of text documents into numerical feature vectors.Their are many methods to convert text data to vectors which the model can understand but by far the most popular method is called TF-IDF. This is an acronym than stands for “Term Frequency — Inverse Document” Frequency which are the components of the resulting scores assigned to each word.

Term Frequency: This summarizes how often a given word appears within a document.

Inverse Document Frequency: This down scales words that appear a lot across documents.

Without going into the math, TF-IDF are word frequency scores that try to highlight words that are more interesting, e.g. frequent in a document but not across documents.
