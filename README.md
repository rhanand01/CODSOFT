# CODSOFT
DATA SCIENCE PROJECT

#CODSOFT

<B><head><u>Titanic-survival-prediction<u></head><br>

<b>TECH USED<b>
- python
- jupyter Notebook
- Kaggle dataset
- pandas, numpy, seaborn, matplotlib, sklearn
- Visual Studio Code

The Titanic dataset is a well-known dataset used for machine learning and data science practice. It contains information about passengers on the Titanic, such as their age, gender, class, fare, and whether they survived the sinking of the ship.

To build a predictive model, we can follow these steps:

   1. Data Loading and Exploration: 
        Load the dataset and explore the data to understand the features and their distributions.

   2. Data Preprocessing: 
        Handle missing values, encode categorical variables, and scale numerical features as necessary.

   3. Feature Selection: 
        Choose the most relevant features for the model and create new features if needed.

   4. Model Building: 
        Train different machine learning models to predict survival.

   5. Model Evaluation: 
        Evaluate the performance of the models using appropriate metrics like accuracy, precision, recall, and F1-score.

   6. Model Tuning: 
        Fine-tune the model parameters to improve performance.

   7. Prediction: 
        Use the final model to make predictions on new data.



# Data visualization
![ceebe3a7-c83a-430f-a8fb-c8b237bf49aa](https://github.com/user-attachments/assets/e4726d81-f807-4f9a-9964-9d9f1a66dea8)

![896f6bf7-ba10-4331-90d5-04bd3c781782](https://github.com/user-attachments/assets/78fb05d5-9dd8-42d8-ae19-050494457bb9)

![0dde23a6-f863-4f43-8b5e-aa6cd110bfcd](https://github.com/user-attachments/assets/afb1fdb3-0917-4a86-aa04-e937de5a0428)

# Model Evaluation

Accuracy: 0.8212290502793296
Classification Report:
               precision    recall  f1-score   support

           0       0.83      0.88      0.85       105
           1       0.81      0.74      0.77        74

    accuracy                           0.82       179
   macro avg       0.82      0.81      0.81       179
weighted avg       0.82      0.82      0.82       179

Confusion Matrix:
 [[92 13]
 [19 55]]

# Final Model Evaluation

Tuned Model Accuracy: 0.8491620111731844
Tuned Model Classification Report:
               precision    recall  f1-score   support

           0       0.84      0.91      0.88       105
           1       0.86      0.76      0.81        74

    accuracy                           0.85       179
   macro avg       0.85      0.84      0.84       179
weighted avg       0.85      0.85      0.85       179

Tuned Model Confusion Matrix:
 [[96  9]
 [18 56]]
