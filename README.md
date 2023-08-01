# Naive-Bayes-Classifier
 To predict whether or not a patient has diabetes or not using Naive Bayes classifier

The Naive Bayes classifier is a widely used machine learning algorithm for classification tasks. It is based on Bayes' theorem and assumes that the features are conditionally independent, given the class label. This "naive" assumption simplifies the calculations, making the classifier efficient and effective, especially in text classification and spam filtering.

The Naive Bayes classifier calculates the probability of each class given the observed features and assigns the class with the highest probability as the predicted label. It can handle both binary and multi-class classification problems. 

The datasets nine columns, the first eight are features and the last one (Outcome) is the label. Outcome has two types of labels 0 (Non-Diabetic) and 1 (Diabetic)

Accuracy is the overall performance metric that measures the proportion of correct predictions (both true positives and true negatives) out of all instances. It is calculated as the ratio of the total number of correct predictions to the total number of instances.

Precision measures the accuracy of the positive predictions made by the model. It is calculated as the ratio of true positives (correctly predicted positive instances) to the sum of true positives and false positives (instances predicted as positive but are actually negative). A higher precision indicates fewer false positives.

Recall measures the model's ability to identify positive instances correctly out of all the actual positive instances. It is calculated as the ratio of true positives to the sum of true positives and false negatives (instances that are actually positive but predicted as negative). A higher recall indicates fewer false negatives.

True Positives (TP): The number of instances correctly predicted as class 1. In this case, there are 29 true positives.

True Negatives (TN): The number of instances correctly predicted as class 0. Here, there are 93 true negatives.

False Positives (FP): The number of instances incorrectly predicted as class 1 when the actual class is 0. In this case, there are 14 false positives.

False Negatives (FN): The number of instances incorrectly predicted as class 0 when the actual class is 1. There are 18 false negatives.
