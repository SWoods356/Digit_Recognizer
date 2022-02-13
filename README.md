# Digit_Recognizer


# Overview
This repository features EDA and classification on the [Digit_Recognizer](https://www.kaggle.com/c/digit-recognizer/overview) kaggle data set.

# Bankruptcy Distribution
The mean bankruptcy rate of this data set is 3.15%.

# EDA and Preparation for Modeling

No null data is present. Principal component analysis was used to reduce the dataset form 784 features to 154 features, retaining 95% of the variation of the original data. Random forests were fitted to the original features and the pca reduced data set mease any time savings from pca reduction.

# Modeling - Logistric Regression, Naive Bayes, and SVM.

Random Forests and K-means clustering were performed to assign a given row the correct label. Random forest models had superior performance, with the test set accuracy score and the number of seconds it took to fit each model below. Note that it took longer to fit random forests to pca reduced data (indexes 1 and 3) than the original data (index 0). K means clustering was the most efficient at 2.95 seconds.


![image](https://user-images.githubusercontent.com/85903905/153773717-0f279bb7-9e6f-4d26-848b-b56d8c5ce879.png)

