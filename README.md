# multinomial_bayes_classifier
Python library to perform multidocument classification
# How to use?
from multinomial_naive_bayes_classifier import MultinomialNaiveBayesClassifier

classifier = MultinomialNaiveBayesClassifier({'class_1': 'class_1_documents', 'class_2' : 'class_2_documents', ..})

classifier.train()

classifier.classify('document_to_predict')

