# Paradigm-Classifier

This is a program that extracts features from a dataset and uses the Scikit-Learn SVM to classify different words according to their word classes.

Data consists of:
- German nouns (de_n.txt), German verbs (de_v.txt)
- Finnish nouns/adjectives (fi_na.txt), Finnish verbs (fi_v.txt)
- Spanish verbs (es_v.txt)

The format of each .txt file is:
word class - word

Example from de_n.txt:
0	Abbau
