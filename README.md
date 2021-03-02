# Iris-Flower-dataset-classification-prediction-model-
Project Name: The Iris Flower dataset classification prediction model using Support Vector Machine (SVM) algorithm.
Dataset:  Source: UCI Repository: https://archive.ics.uci.edu/ml/datasets/iris . The Iris dataset contains: 4 attributes (Sepal Length, Sepal Width, Petal Length and Petal Width), 150 instances with 3 different classes (Sentosa, Versicolour, and Virginica) 
Summary:  Grid Search Cross validation approach is used to tune the regularization parameter C and kernel. SVC classifier with the best C value from grid search cv was used for training. The test also compared with another classifier called LinearSVC, which is also a linear classifier the minimizes the squared hinge loss and uses the One-vs-All (also known as One-vs-Rest) multiclass reduction while SVC minimizes the regular hinge loss and uses the One-vs-One multiclass reduction. The confusion matrix shows SVC performs better than LinearSVC classifier. The extreme regularized C also considered, and the confusion matrix shows poor its performance.
![4](https://user-images.githubusercontent.com/4210955/109723946-cc60f700-7b7c-11eb-80ae-a20269600b3c.png)
![1](https://user-images.githubusercontent.com/4210955/109723955-cf5be780-7b7c-11eb-9598-b4033cf60610.png)
![2](https://user-images.githubusercontent.com/4210955/109723959-d08d1480-7b7c-11eb-9f36-adf996c07f27.png)
![3](https://user-images.githubusercontent.com/4210955/109723966-d256d800-7b7c-11eb-838a-94841b80abc3.png)
