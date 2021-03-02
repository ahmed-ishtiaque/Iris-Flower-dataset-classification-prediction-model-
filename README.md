# Iris-Flower-dataset-classification-prediction-model-
Project Name: The Iris Flower dataset classification prediction model using Support Vector Machine (SVM) algorithm.
Dataset:  Source: UCI Repository: https://archive.ics.uci.edu/ml/datasets/iris . The Iris dataset contains: 4 attributes (Sepal Length, Sepal Width, Petal Length and Petal Width), 150 instances with 3 different classes (Sentosa, Versicolour, and Virginica) 
Summary:  Grid Search Cross validation approach is used to tune the regularization parameter C and kernel. SVC classifier with the best C value from grid search cv was used for training. The test also compared with another classifier called LinearSVC, which is also a linear classifier the minimizes the squared hinge loss and uses the One-vs-All (also known as One-vs-Rest) multiclass reduction while SVC minimizes the regular hinge loss and uses the One-vs-One multiclass reduction. The confusion matrix shows SVC performs better than LinearSVC classifier. The extreme regularized C also considered, and the confusion matrix shows poor its performance.
