The original, immutable data dump


## Raw Data

You are provided with a large number of [Wikipedia comments](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data) which have been labeled by human raters for toxic behavior. The types of toxicity are:

* `toxic`
* `severe_toxic`
* `obscene`
* `threat`
* `insult`
* `identity_hate`

You must create a model which predicts a probability of each type of toxicity for each comment.

## File descriptions

* [train.csv](https://github.com/estebanangelm/vjex/blob/master/data/raw/train.csv)* - the training set, contains comments with their binary labels
* [test.csv](https://github.com/estebanangelm/vjex/blob/master/data/raw/test.csv)* - the test set, you must predict the toxicity probabilities for these comments. To deter hand labeling, the test set contains some comments which are not included in scoring.
* [sample_submission.csv](https://github.com/estebanangelm/vjex/blob/master/data/raw/sample_submission.csv)* - a sample submission file in the correct format
