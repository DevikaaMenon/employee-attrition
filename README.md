# Employee Attrition Prediction 
Employee attrition refers to an employee’s voluntary
or involuntary resignation from a workforce. Organizations spend many resources in hiring talented employees
and training them. Every employee is critical to a company’s success. My goal was to predict employee attrition
and identify the factors contributing to an employee leaving a workforce. I trained various classification models on our dataset and assessed their performance using different metrics such as accuracy, precision, recall and F1 Score. I
also analyzed the dataset to identify key factors contributing
to an employee leaving a workforce. This project will assist organizations in gaining fresh insights into what drives
attrition and thus enhance retention rate.

#### Machine Learning Models

I trained and evaluated 9 supervised machine learning classification models.

1. Logistic Regression
2. Naive Bayes
3. Decision Tree
4. Random Forest
5. AdaBoost
6. Support Vector Machine
7. Linear Discriminant Analysis
8. Multilayer Perceptron
9. K-Nearest Neighbors

#### Datasets
We trained our models on 5 different datasets
1. Undersampled
2. Oversampled
3. PCA
4. Undersampling With PCA
5. Oversampling With PCA

Further, to get the best performance, hyperparameter tuning was carried out using RandomSearchCV and GridSearchCV. K-fold cross-validation with 5 folds was also
performed on the training set. To handle model interpretability, appropriate graphs and figures were used.Accuracy for the attrition decision is a biased metric, and hence I evaluated the model on all the
following classification metrics: accuracy, precision, recall
and F1 Score.

## Dataset
I used the [IBM Employee Attrition dataset from Kaggle](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset). It contains 35 columns and 1470 rows and has a mix of
numerical and categorical features. 

#### Best Performing Model
The best performance was obtained in Random Forest Model
with PCA and Oversampling with an accuracy of 99.2%,
the precision of 98.6%, recall of 99.8% and F1 Score of
99.2%.

