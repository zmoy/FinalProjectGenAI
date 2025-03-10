# Context

The following dataset was created and shared openly by Google Jigsaw to raise the bar regarding online hateful content moderation.

# Dataset Description

You are provided with a large number of Wikipedia comments which have been labeled by human raters for toxic behavior. The types of toxicity are:

* toxic
* severe_toxic
* obscene
* threat
* insult
* identity_hate

You must create a model which predicts a probability of each type of toxicity for each comment.
File descriptions

* train.csv - the training set, contains comments with their binary labels
* test.csv - the test set, you must predict the toxicity probabilities for these comments. To deter hand labeling, the test set contains some comments which are not included in scoring.
* sample_submission.csv - a sample submission file in the correct format
* test_labels.csv - labels for the test data; value of -1 indicates it was not used for scoring

# Licensing

The dataset under CC0, with the underlying comment text being governed by Wikipedia's CC-SA-3.0