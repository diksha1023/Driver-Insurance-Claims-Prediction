# -dikshaDriver-Insurance-Claims-Prediction
# Driver Insurance Claims Prediction

## About the project :
Driver insurance claims prediction is a project which uses data mining techniques to predict if a customer of an auto insurance is going to file a claim in a year.
The dataset of customers used is from the Kaggle competition - https://www.kaggle.com/competitions/porto-seguro-safe-driver-prediction/data?select=train.csv
(As the dataset was bigger than the allowed limit it could not be uploaded and can be downloaded from the above link)
### We have performed data preprocessing involving steps like :
1. Removing NAN values
2. Removing uncorrelated and zero correlated features
3. One hot encoding on categorical features
4. Splitting dataset into train and test data.
5. Feature scaling.
6. Upsampling of minority class and down sampling of majority class.


### We have used several machine learning models like :
1. Logistic Regression
2. Linear SVC
3. XGBoost
4. AdaBoost (Decision Tree)
5. AdaBoost (Random Forest)
6. K-Nearest Neighbours
7. Naive Bayes
8. Bagging Classifier (Decision Tree)
9. Artificial Neural Network

### Evaluation of the models :
We have used F1 score and ROC score as metric of evaluation for our models.

### How to run the code :
The code is written in Python 3.
We have used Google Colab as our IDE.

1. Upload the train.csv file to google colab
2. Run all the cells

Once all the cells have finished execution, under each models section ROC curve and other evaluation metrics are printed.
