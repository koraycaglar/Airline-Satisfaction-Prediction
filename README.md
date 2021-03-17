# Airline-Satisfaction-Prediction
In this project, we will be using different machine learning algorithms to predict whether an airline customer will be satisfied or not according to the features such as wifi service, food and drink service, online booking ease etc...



Model | Accuracy
------------ | -------------
Logistic Regression | 86.8%
Support Vector Machine | 88.1%
Multilayer Perceptron | 88.1%
Random Forest | 96.3%
Gradient Boosting | 93.9%


# Data Used
These models were built using [data found on Kaggle](https://www.kaggle.com/teejmahal20/airline-passenger-satisfaction).

# Libraries Used
```
pandas
numpy
matplotlib
seaborn
scipy
sklearn
warnings
joblib
time
```
# Author
- Koray Çağlar - [koraycaglar](https://github.com/koraycaglar)

# Further Notes
Couldn't do cross validation while training SVM MLP and GB models as it takes so much time because of the huge data. Default hyperparameters were used. I might update the code if I find an alternative to cross validation.

Couldn't upload the Random Forest model to the repo because the file is huge for some reason.

# Files

- cleaning_the_data_Notebook includes the code for:
     - Second nested list item
     - finding and filling in the null data
     - enumerating non-numeral catagorial features
     - dropping the unnecessary features

- data_visualization_notebook includes the code for:
     - weeding out outliers
     - using cox-box transformation to reduce skewness
     - data visualization

- Building_Models_Notebook includes the code for:
     - Splitting the data to training,validation and test data
     - cross validation
     - Building Logistic Regression model
     - Building Support Vector Machine model
     - Building Multilayer Perceptron model
     - Building Random Forest model
     - Building Gradient Boosting model

- Final_Results_Notebook includes the code for:
     - Validating and comparing models against each other in terms of accuracy, precision, recall and latency
     - Testing the best Model on test data
     - Conclusion
     
- models folder include the models built during this project.
- csv folders include the data used during this project
