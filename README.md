# CSCE 4143 Practice Project

This practice project focuses on one of mostly studied dataset --- [Adult dataset](http://archive.ics.uci.edu/ml/datasets/Adult), and involves the use of data mining software (and/or your own codes) for the following specific tasks.

1) Download the data and read the descriptions in the file adult.names. Remove records with unknown (?) values from both train and test data sets and remove all continuous attributes. For each multi-domain categorical attribute, you can use one-hot encoding to transform data (this step is needed if you choose scikit-learn to build decision tree and naïve classifier; it is optional if you choose Weka). In your report, describe briefly how you develop your algorithm or apply software on the following two tasks and include 2-4 screenshots about your algorithm settings and output.  (4 points) 

    a) Build a decision tree classifier (single tree) and report accuracy by class including (TP rate, FP rate, precision, recall, F1) on the test data. 

    b) Build a naïve Bayesian classifier and report accuracy by class including (TP rate, FP rate, precision, recall, F1) on the test data. 

2) Remove records with unknown (?) values from both train and test data sets. For each multi-domain categorical attribute, use one-hot encoding to transform data; for each numerical attribute, use the mean value to transform into binary attribute. (4 points) 

    a) Build k-means clustering algorithm over train data with varied k values (3, 5, 10) based on your chosen distance function and report the centroids of the clusters. 

    b) Use the last 10 records from test data and use kNN algorithm (with varied k values, 3, 5, 10)  to report the prediction accuracy. 

3) Continue using the train datasets from step 2, build a SVM classifier and report the predicted accuracy of the test data. (2 points)   

4) Continue using the train datasets from step 2, build a neural network classifier and report the predicted accuracy of the test data. (2 points as bonus)   
