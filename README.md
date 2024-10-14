# iris-binary-classification
1) Description:
    The project performs binary classification on the Iris dataset by combining classes to create binary targets and comparing the performance of logistic and linear regression models.

2) Key Features:
  Class Grouping:
  Class 1 (original class 0) vs. Class 2 (combined original classes 1 & 2).
  One-vs-All classification for classes 2 and 3.
  Models: Logistic Regression and Linear Regression.
  Performance:
  Class 1 vs. Class 2:
    Logistic Accuracy: 63.33%, Loss: 0.589
    Linear Accuracy: 100%, Loss: 0.007
  Class 2 vs. All:
    Logistic Accuracy: 33.33%, Loss: 0.731
    Linear Accuracy: 83.33%, Loss: 0.076
  Class 3 vs. All:
    Logistic Accuracy: 66.67%, Loss: 0.618
    Linear Accuracy: 96.67%, Loss: 0.035

3) Programming Tools:
   Python, NumPy, Scikit-learn.
