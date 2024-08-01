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
![image](https://github.com/user-attachments/assets/45e2de05-dde4-431f-923c-a22013a235d4)
![image](https://github.com/user-attachments/assets/2f69efac-b909-4576-a9ac-2ae430628c51)
![Uploading image.png…]()



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
