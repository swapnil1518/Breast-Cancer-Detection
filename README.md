# Breast-Cancer-Detection Using Logistic regression EXPLANATION
Libraries used.
Numpy : Used for numerical python. It is used to generate some random numbers.
sklearn.datasets : 
sklearn for importing LogisticRegression
pandas : https://pandas.pydata.org/docs/getting_started/overview.html
variable name breats_cancer = sklear.datasets.load_breast_cancer(). This is predefined function. 
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html
Print(breats_cancer)- this loads all the data with  0 and 1 values. 0 and 1 stands for 'malignant', 'benign'
taking 2 vaiables x and y and storing the data and target vaues in it.
print(X.shape, Y.shape) - o/p is (569, 30) itmeans we are training on 569 models means for 569 value and 30 columns
train_test_split - https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html
Startify- stratify parameter makes a split so that the proportion of values in the sample produced will be the same as the proportion of values provided to parameter stra
random_state - when random_state set to an integer, train_test_split will return same results for each execution. when random_state set to an None, train_test_split will return different results for each execution. The random_state splits a randomly selected data but with a twist.13
