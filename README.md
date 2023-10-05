# Spam Ham Classifier

Applying classical ML models to classifying ham and spam of varying difficulties.

Thi

This is my solution to Exercise 3.4 from _Hands on Machine Learning (Third Edition) by Auélien Géron (O'Reilly)_. This is taken from my [handson-ml](https://github.com/jreaso/handson-ml) repository with some refinements made.

There are some improvements that could be made to this classifier:
- Include a HTML indicator
- Include the subject in the word count
    - include a constant weight multiplier for subject word importance (e.g. subject words count for $C$ words in body)
- Integrate a contant instream of new emails (online learning)