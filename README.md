# Predictive-Analytics-Lab-Exam-2
Objective:
The objective of this project is to perform a classification task using machine learning techniques to predict the target variable based on given features.
The dataset containes the following columns;
feature1,feature2,target
The target variable was converted into numerical format:
Yes → 1
No → 0

Exploratory Data Analysis (EDA)
The following steps were performed:
Checked for missing values and handled them appropriately
Analyzed statistical summary of the dataset
Visualized feature relationships using:
Correlation heatmap
Scatter plots
Observed class distribution

Data Preprocessing
Removed rows with missing target values
Converted categorical target variable into numerical format
Split data into training and testing sets
Applied feature scaling for better model performance

Model Used
Decision Tree Classifier
The model learns decision rules based on feature values to classify data points

Decision Boundary
Decision boundary was plotted using Feature1 and Feature2
It shows how the model separates the two classes in feature space

Model Evaluation
Accuracy
93.5%

Confusion Matrix
[[147   6]
 [  7  40]]
 
Classification Report

Class 0 (No):
Precision: 0.95
Recall: 0.96
F1-score: 0.96

Class 1 (Yes):
Precision: 0.87
Recall: 0.85
F1-score: 0.86

Results
The model performs well with high accuracy
It correctly classifies most instances of both classes
Unlike simpler models, it successfully identifies the minority class

Conclusion
The Decision Tree model achieved strong performance with balanced precision and recall across both classes. It effectively handles the classification task and provides reliable predictions.
