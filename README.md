# phishing_classification
performing various classification models in phishing data with multiple features

Built a classification model for classifying whether a website is a phishing website or not.

### About Data
The Phishing dataset for creating the model have 30 variables and 1 target variable to be predicted. 
There are 2456 records in total.

### Contains 2 class
> 0 indicating website is not phishing
> 1 indicationg is a phishing website

### Approach

1.Dividing dataset into 2 parts as feature variables and target variable
2.Splitting into train test and validation sets
3.Applying various machine learning classification models to predict
4.Using metrics to find the accuracy score

### Classication models

1.Logistic Regression 
2.Support Vector Classification
3.Random Forest 
4.XGBOOST

### Packages used

1.pandas
2.nummpy
3.sklearn
4.metrics
5.seaborn
6.matplotlib


#### Observation

As we see through model accuracy on validation XGBOOST gave is the best accuracy of 95.84. As well give us better performance
Due to which we select this model for our classification problem.
