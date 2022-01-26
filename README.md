# Breast-Cancer-Detection Using Logistic regression EXPLANATION
Libraries used.
numpy : used for numerical python.
sklearn.datasets : 
pandas : https://pandas.pydata.org/docs/getting_started/overview.html
variable name breats_cancer = sklear.datasets.load_breast_cancer(). This is predefined function. 
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html
Print(breats_cancer)- this loads all the data with  0 and 1 values. 0 and 1 stands for 'malignant', 'benign'
taking 2 vaiables x and y and storing the data and target vaues in it.
print(X.shape, Y.shape) - o/p is (569, 30) itmeans we are training on 569 models means for 569 value and 30 columns
