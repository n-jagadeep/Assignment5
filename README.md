# Assignment5

PROBLEM 1:

Implementing Naïve Bayes method using scikit-learn library for this I'm first Loading the glass dataset using pd.read_csv,Splitting the data into training and testing sets then Creating a Gaussian Naïve Bayes classifier and Fitting the classifier on the training data. Making predictions on the test data using .predict() and calculating accuracy using score method, finally Evaluating the model using classification_report() and printing the results.

PROBLEM 2:

Implementing linear SVM method using scikit library this is done by first Loading the glass dataset to a variable named data and Splitting the data into x and y then the x and y data are split into training and testing sets and then Creating a Linear SVM classifier using kernel SVC and fitting the kernel svc classifier on the training data and Making predictions on the test data, calculating the accuracy using the score method.Finally the model is evaluated using classification_report() and printing the results.

CONCLUTION:

from the program we can see that the kernel svc has a better accuracy and this is because the kernel svc is better fitted to split the positive and negative data in any dimentions, whereas the Naïve Bayes method is better fitted to train simple binary data and has better speed. The given dataset is a moderately sized dataset with complex dicision boundaries so svc model performed better. 

VIDEO PRESENTATION: https://drive.google.com/file/d/1oANUocM4gtpHYxRtQSrfnxr9g4WAJB1k/view?usp=share_link
