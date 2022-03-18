# Confusion-matrix
Testing model's accuracy
CONFUSION MATRIX

• The confusion matrix is one of the most powerful tools for predictive analysis in machine learning. • A confusion matrix gives you information about how your machine classifier has performed, pitting properly classified examples against misclassified examples • In the machine learning context, a confusion matrix is a metric used to quantify the performance of a machine learning classifier. • The confusion matrix is used when there are two or more classes as the output of the classifier.

Actual vs predicted

• A confusion matrix presents a table layout of the different outcomes of the prediction and results of a classification problem and helps visualize its outcomes. • It plots a table of all the predicted and actual values of a classifier.

2x2 Confusion matrix Accuracy vs confusion matrix

• Confusion matrices are useful because they give direct comparisons of values like True Positives, False Positives, True Negatives and False Negatives.

• In contrast, other machine learning classification metrics like “Accuracy” give less useful information, as Accuracy is simply the difference between correct predictions divided by the total number of predictions.

Confusion matrix

• Confusion matrices are used to visualize important predictive analytics like

Recall
Accuracy
Precision.
F1-Score
Recall

• The term recall refers to the proportion of genuine positive examples that a predictive model has identified. • Recall is also sometimes called the hit rate, while sensitivity describes a model’s true positive prediction rate or the recall likelihood.

Recall=TP/TP+FN

Precision

• Precision is similar to recall, in the respect that it’s concerned with your model’s predictions of positive examples • Precision is interested in the number of genuinely positive examples your model identified against all the examples it labeled positive

Precision= TP/TP+FN

Accuracy

• Accuracy is the simplest. It defines your total number of true predictions in total dataset. • It is represented by the equation of true positive and true negative examples divided by true positive, false positive, true negative and false negative examples.

Accuracy= TP+TN/TP+TN+FP+FN

F1-Score

• It is the harmonic mean of Recall and Precision. It is useful when you need to take both Precision and Recall into account. F1-SCORE = 2PRECISIONRECALL/PRECISION+RECALL

Confusion Matrix

EXAMPLE: We'll build a logistic regression model using a heart attack dataset to predict if a patient is at risk of a heart attack

First, we import all the necessary libraries to create the model, and then read the dataset using pandas

