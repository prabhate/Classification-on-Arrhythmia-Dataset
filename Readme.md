The purpose of this project is to predict the absence or presence of arrhythmia and classify them into 16 groups. The dataset has 453 instances and 279 attributes. various classification techniques like Naive Bayes,Decision Tree,Logistic Regression,SVM(linear kernel) and K-Nearest Neighbours have been used.

Pre-processing:
After going through the dataset one column was found which is filled with lot of null values and cannot be filled sensibly.So, it has been removed. all the other attributes with few null values have been dropped.
This is an imbalanced dataset, that means the class distribution is not uniform among the classes. one of the method to tackle it is to perform sampling. since already the number of instances is less, over sampling has been performed. over sampling is a condition where randomly examples from the minority classes are duplicated and added to the training set. Also since the number of attributes is also higher,PCA(Principal Components Analysis) has been used to reduced the number of dimensions.

Later various classification techniques have been applied.



Datasource:

https://archive.ics.uci.edu/ml/datasets/Arrhythmia

