# Machine learning homework

In this homework we worked with a dataset of observations of the NASA Kepler telescope, where every row represents a different Kepler Object of Interest (koi) that could possibly represent an exoplanet.

I trained and compared three different models for classifying the objects into three possible categories of exoplanet (confirmed, false positive and candidate): Support Vector Machine (SVM), K-Nearest Neighbors (KNN) and Logistic regression.

Then I tunned the hyperparameters using GridSearch. The following table shows how the scores changed after the tunning:

<img src='https://github.com/lrondi/machine-learning/blob/master/results.png'>

KNN seems to be the best model, although the tunning seems to have overfitted the train data, because the score for the training data is 1 and the test data is actually lower than the non-tunned model.


