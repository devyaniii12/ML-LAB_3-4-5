# ML-LAB_3-4-5
Here I have used logistic regression , Support Vector machine(SVM) and decision tree algorithm on two datasets -> 
1)The heart disease dataset(framingham.csv)
2)Iris dataset(Iris.csv)

1)Logistic Regression and SVM on Framingham Heart Study Dataset
Overview
This project involves building two machine learning models: Logistic Regression and Support Vector Machine (SVM), to predict the likelihood of a 10-year risk of coronary heart disease (CHD) using the Framingham Heart Study dataset.

The models are evaluated on their performance using metrics such as accuracy, precision, recall, and F1-score.

Dataset
The dataset used is the Framingham.csv file, which contains data related to cardiovascular health and various risk factors, including:

Age, gender, smoking status, and other health indicators (cholesterol levels, blood pressure, BMI, glucose levels, etc.)
The target variable is TenYearCHD, which indicates if the patient will develop coronary heart disease within 10 years.
Features:
male: Gender of the participant (0 = Female, 1 = Male)
age: Age of the participant
education: Level of education (1 to 4)
currentSmoker: Whether the participant is a current smoker (1 = Yes, 0 = No)
cigsPerDay: Number of cigarettes smoked per day
BPMeds: Whether the participant is on blood pressure medication (1 = Yes, 0 = No)
prevalentStroke: History of stroke (1 = Yes, 0 = No)
prevalentHyp: History of hypertension (1 = Yes, 0 = No)
diabetes: Diabetes status (1 = Yes, 0 = No)
totChol: Total cholesterol level
sysBP: Systolic blood pressure
diaBP: Diastolic blood pressure
BMI: Body Mass Index
heartRate: Heart rate (beats per minute)
glucose: Glucose level
TenYearCHD: Target variable (0 = No CHD, 1 = CHD within 10 years)
Steps Performed
Data Cleaning:

Handled missing values by replacing them with the column mean.
Removed outliers using the interquartile range (IQR) method.
Data Preprocessing:

Features were scaled using StandardScaler for normalization.
The dataset was split into training (70%) and testing (30%) sets.
Modeling:

Logistic Regression: Implemented to predict the 10-year CHD risk.
Support Vector Machine (SVM): Implemented with a linear kernel for classification.
Evaluation:

Confusion Matrix, Accuracy, Precision, Recall, and F1-Score were computed to evaluate both models.
Results
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

Visualization
The confusion matrices for both models were visualized using a heatmap for better interpretation of true positives, false positives, true negatives, and false negatives.
