# SGD-Classifier
## AIM:
To write a program to predict the type of species of the Iris flower using the SGD Classifier.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Import Libraries and Load Dataset: Import necessary libraries (pandas, sklearn, matplotlib, seaborn) and load the Iris dataset using load_iris().

2.Create DataFrame: Convert the loaded Iris dataset into a pandas DataFrame with feature names as columns and target values.

3.Split Data: Separate the dataset into feature variables (X) and target variable (y), then split the data into training and testing sets using train_test_split().

4.Train Classifier: Initialize an SGDClassifier with specified parameters (max_iter=1000, tol=1e-3), and fit the classifier on the training data.

5.Evaluate Model: Predict target values for the test set, calculate accuracy using accuracy_score(), and display the confusion matrix with seaborn heatmap for better visualization.

## Program:
```
/*
Program to implement the prediction of iris species using SGD Classifier.
Developed by: Sanjeev A
RegisterNumber:  212224230246
*/
```
![Screenshot 2025-03-27 202841](https://github.com/user-attachments/assets/259faba1-5ea3-4f35-aa97-84bfcae3163f)
![Screenshot 2025-03-27 202854](https://github.com/user-attachments/assets/866b3fe6-daa4-4ad7-8bf2-9c0c4daa34e0)
![Screenshot 2025-03-27 202905](https://github.com/user-attachments/assets/d2726dea-60e7-4b79-a5da-39e21ac6d49f)


## Output:
![Screenshot 2025-03-27 202922](https://github.com/user-attachments/assets/73b3cd6e-b912-4228-b2d6-b9935a0d6579)
![Screenshot 2025-03-27 202932](https://github.com/user-attachments/assets/c771cb0a-82c2-4922-ada3-2b9487085d6f)
![Screenshot 2025-03-27 202944](https://github.com/user-attachments/assets/a9c250a1-612a-45a3-8bd5-4e611c7b553b)


## Result:
Thus, the program to implement the prediction of the Iris species using SGD Classifier is written and verified using Python programming.
