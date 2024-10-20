# ML-LAB_3-4-5
Here I have used logistic regression , Support Vector machine(SVM) and decision tree algorithm on two datasets -> 
1)The heart disease dataset(framingham.csv)
2)Iris dataset(Iris.csv)

1)Logistic Regression and SVM on Framingham Heart Study Dataset
Overview
This project involves building two machine learning models: Logistic Regression and Support Vector Machine (SVM), to predict the likelihood of a 10-year risk of coronary heart disease (CHD) using the Framingham Heart Study dataset.

The models are evaluated on their performance using metrics such as accuracy, precision, recall, and F1-score.

Steps Performed
a)Data Cleaning:
Handled missing values by replacing them with the column mean.
Removed outliers using the interquartile range (IQR) method.

b)Data Preprocessing:
Features were scaled using StandardScaler for normalization.
The dataset was split into training (70%) and testing (30%) sets.

c)Modeling:
Logistic Regression: Implemented to predict the 10-year CHD risk.
Support Vector Machine (SVM): Implemented with a linear kernel for classification.

d)Evaluation:
Confusion Matrix, Accuracy, Precision, Recall, and F1-Score were computed to evaluate both models.

e)Results
Logistic Regression:
Accuracy: 86.08%
Precision: 68.97%
Recall: 10.64%
F1-Score: 18.43%
Support Vector Machine (SVM):
Accuracy: 85.22%
Precision: 0.00%
Recall: 0.00%
F1-Score: 0.00%
Note: The SVM model failed to identify any positive cases, leading to a precision and recall of 0.

f)Visualization
The confusion matrices for both models were visualized using a heatmap for better interpretation of true positives, false positives, true negatives, and false negatives.

2)Iris Flower Classification Project
This project demonstrates the classification of Iris flower species using various machine learning models, such as:
Logistic Regression
Support Vector Machine (SVM)
Decision Tree Classifier

The goal of the project is to predict the species of an Iris flower based on its physical characteristics:
Sepal Length (cm)
Sepal Width (cm)
Petal Length (cm)
Petal Width (cm)

Dataset
The dataset used in this project is the classic Iris Dataset, which consists of 150 samples from each of three species of Iris flowers: Iris setosa, Iris versicolor, and Iris virginica. There are four features for each sample:
Sepal Length
Sepal Width
Petal Length
Petal Width

The dataset is split into:
70% Training Set
30% Testing Set

Models Implemented
a)Logistic Regression:
Logistic Regression is used to classify the Iris species based on the flower's characteristics.
Accuracy Achieved: 100%

b)Support Vector Machine (SVM):
SVM with a linear kernel is implemented to classify the species.
Accuracy Achieved: 97.78%

c)Decision Tree:
A simple decision tree classifier is implemented for classification.
Accuracy Achieved: 100%

Results
The performance of each model is measured using:

Accuracy: Overall correctness of the model.
Precision: Exactness of the model in classifying a specific class.
Recall: Completeness of the model in identifying all samples of a specific class.
F1-Score: Harmonic mean of precision and recall.
Confusion Matrix: A table showing the true vs predicted classifications.
