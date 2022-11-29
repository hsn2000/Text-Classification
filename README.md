# Text-Classification
This repository contains Text Classification using Naive Bayes Algorithm and comparison between three different methods for feature selection.

# Method 1: Using all words in the document
Results:

 Accuracy of the classifier is 0.930379746835443

 Confusion matrix
[[117   6]
 [  5  30]]

 The value of Precision 0.8333333333333334

 The value of Recall 0.8571428571428571
 
 # Method 2: Using only Nouns from the dataset
 Results:
 
 Accuracy of the classifier is 0.9113924050632911

 Confusion matrix
[[114   9]
 [  5  30]]

 The value of Precision 0.7692307692307693

 The value of Recall 0.8571428571428571
 
 # Method 3: Using only Top Frequent terms in each class
 Results:
 
 Accuracy of the classifier is 0.810126582278481

 Confusion matrix
[[118   5]
 [ 25  10]]

 The value of Precision 0.6666666666666666

 The value of Recall 0.2857142857142857

# Conclusion
Using all the data as features used in method 1 seems to be the best approach with this dataset using Naive Bayes Algorithm
