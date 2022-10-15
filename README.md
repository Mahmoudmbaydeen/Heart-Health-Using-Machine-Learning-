# Dataset Information:
The dataset consists of 303 rows and 14 columns with label Target. Data contains categorical as well as continuous data.
# Data Cleansing: 
There is only one column that contains null value in which only two rows have null value that can easily be dropped by removing NA function.
# Data Visualization:
Data Visualization is done by step by step process with critical analysis I use correlation matrix to find most dependent variable to the label which is Age. I plot graph of label (Target) to show the ratio of heart Disease.
# Methodology: 
Different data Science techniques that interpret medical goals have been adopted to diagnose cardiac disease and increase the success criteria of the algorithms for prediction in order to explain and identify the problem and address medical objectives. For the training and implementation in Python of the prediction model, suitable machine learning methods such as Random Forest, SVM (Support Vector Machine), Decision Tree, and Logistics Regression were chosen. These algorithms will aid medical experts in predicting and diagnosing heart attacks in the patient dataset. The primary goal is to determine which machine-learning algorithm has the highest accuracy in predicting cardiac disease from a patient dataset.
# Result:
Cross Validation is also done for all the models. The results are same but have some variance in accuracy. After Cross Validation the result become clear that Logistic regression is good for this problem

# Installation Guide:
->Install Anaconda Destribution <br>
->Install Jupyter Notebook <br>
->Copy Heart Health.ipynb to path C:\Users\xyz along with heart.csv <br>
->Run Jupyter Notebook and open file from its home page <br>
->Change the path of read_csv() as your file location <br>
