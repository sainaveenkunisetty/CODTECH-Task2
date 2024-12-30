Name: KUNISETTY SAI NAVEEN

Company: CODTECH IT SOLUTIONS

ID: CT12DHZ

Domain: Machine Learning

Duration: 12-Dec-2024 to 12-feb-2024

OVERVIEW OFTHE PROJECT:

Project: CREDIT CARD FRAUD DETECTION

Objective: Develop a fraud detection model to identify: fraudulent credit card transactions. Use techniques like anomaly detection or supervised learning with imbalanced data.

1.Data Loading and Exploration: The dataset is Taken from a kaggle.Initial analysis includes displaying the dataset structure and examining the class distribution, which reveals significant class imbalance (fraudulent transactions are a small fraction).

2.Feature Scaling: The Amount and Time features are normalized using StandardScaler to standardize the range of values.

3.Handling Class Imbalance: The SMOTE (Synthetic Minority Oversampling Technique) algorithm is applied to generate synthetic examples for the minority class, balancing the dataset for training.

4.Data Splitting: The resampled data is split into training (80%) and testing (20%) sets using train_test_split.

5.Model Training: A Random Forest Classifier is used as the predictive model:

  1.Class Weighting: The class_weight='balanced' parameter is included to further mitigate class imbalance during training.
  
  2.The model is trained on the balanced training dataset.

6.Predictions: The trained model predicts outcomes on the testing dataset:

  Class Labels: Predicted classifications (fraud or non-fraud).
    
  Probabilities: The likelihood of a transaction being fraudulent, used for metrics like ROC-AUC.

7.Model Evaluation: 

  Confusion Matrix: Summarizes the model's performance in detecting true positives, true negatives, false positives, and false negatives.
    
  Classification Report: Includes precision, recall, F1-score, and support for each class.
    
  ROC-AUC Score: Evaluates the model's ability to discriminate between fraudulent and non-fraudulent transactions.

Key features:

  The code effectively handles imbalanced data using SMOTE and class weighting.

  The Random Forest Classifier provides robust performance with interpretable metrics.

  The evaluation metrics focus on recall and ROC-AUC, critical for fraud detection tasks where minimizing false negatives (missed frauds) is essential.

Output:

![image](https://github.com/user-attachments/assets/041f9142-2fb9-4b86-895b-9c09351af1bc)
