# CreditCardFraudDetection
     Machine learning models to automatically predict credit card frauds
# Dataset
     The dataset for this project was obtained from kaggle website.
       [https://www.kaggle.com/mlg-ulb/creditcardfraud]
# Requirements

    Python 3.6
    Pandas and Numpy
    Sklearn Library 0.19.1
    Python's Matplotlib (2.2.2) for Visualization
    Seaborn
    Imblearn

# Data Preprocessing

    Feature Elimination
    Data Standaristaion using Robust Scaler
    Balancing the skewed dataset using
    3.1 Oversampling using SMOTE technique

# Machine Learning Models
    
    Random Forest
    
 # Procedure Used:
    Importing requires libraries.
    Importing the dataset file.
    Displaying the amount and transaction time using seaborn library.
    Scaling amount and transaction time using robust scaler.
    Spliting the dataset into train and test.
    Balancing the skewed dataset using Oversampling using SMOTE technique.
    Applying the random forest classifier on training dataset and predicting the fraud on testing dataset.
    Finding accuracy of the trained model.
    
 # Result:
    
      Mean Absolute Error: 0.0035743126996945337
      Mean Squared Error: 0.0013077724330840443
      Root Mean Squared Error: 0.03616313638339524
      
      

