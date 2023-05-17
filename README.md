# Credit Risk Classification (Mod 20)
## Purpose
- In this assignment, various techniques are used to train and create a model to evaluate loan risk. 
## Steps
* Split Data into Training/Testing Sets
* Create a Logistic Regression model with the Original Data
* Predict a Logistic Regression model with Resampled Training Data
* Evaluate the uses of both and write a risk analysis report

# Splitting Data
- Read in historical lending data and split into sets using the train_test_split from sklearn 
- ![Screenshot 2023-05-16 205054](https://github.com/IPadaJT/creditrisk-classification/assets/117694350/b510f981-00e1-400e-9a9b-9a04e63e7d99)

# Original Data Model
- Train and test model using original data using LogisticRegression module from sklearn
- ![Screenshot 2023-05-16 205248](https://github.com/IPadaJT/creditrisk-classification/assets/117694350/d962d277-edfd-4988-872f-e723c7cc8c15)

# Prediction with Resampled Data
- Use imblearn library and RandomOverSampler module to resample dataset with equal number of datapoints. Then use the same LogisticRegression from sklearn. 
- ![Screenshot 2023-05-16 205445](https://github.com/IPadaJT/creditrisk-classification/assets/117694350/46793c25-0e61-4118-814d-8f76f1df480b)

# Evaluate 
- ![Screenshot 2023-05-16 205531](https://github.com/IPadaJT/creditrisk-classification/assets/117694350/5ec1b1e1-a6b1-40f4-816d-20f2bacd22b6)
