# Risky Business

## MACHINE LEARNING HOMEWORK

In this assignment, I have built and evaluated several machine learning models to predict credit risk using data from peer-to-peer lending services.

Using the imbalanced learn library to resample data, I was able to conclude that:

- The model with the best balanced accuracy score is the Naive Random Oversampling model with a balanced accurancy score of 0.99482799.

- All of the models used, Random Oversampling, SMOTE Oversampling, Cluster Centroids Uncersampling and combination sampling SMOTEENN resulted in an average recall score of 0.99.

- Likewise, all of the models used, Random Oversampling, SMOTE Oversampling, Cluster Centroids Uncersampling and combination sampling SMOTEENN resulted in a geometric mean score of 0.99.

On the other hand, I have also compared 2 different ensemble classifiers to predict loan risk and evaluate each model.  On this exercise, I have found that:

- The model that had the better balanced accuracy score is the Balanced Random Forest Classifier with 0.72223 , compared to Easy Ensemble Classifier with 0.72175.

- The model that had the better recall score is the Balanced Random Forest Classifier with 0.84, compared to 0.77 of the Easy Ensemble Classifier.

- The model that had the better geometric mean score is the Easy Ensemble Classifier with 0.72, compared to 0.71 of the Balances Random Forest Classifier.

- The top three features are the Total Received Principal, Last Payment Amount and Total Received Interest.