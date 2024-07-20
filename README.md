# classification-challenge
Module 13 Challenge
SPAM!!!!!!!!!!!!!!!!!!!!!!!
This module we will be using supervised learning to find spam.

RETRIEVE THE DATA
----------------------------------------------------------------------------------------------------
The first step into detecting spam is importing the CSV file into a workable dataframe. Look at the 
columns and see what the data is saying. 

SPLIT THE DATA INTO TRAINING AND TESTING SETS
----------------------------------------------------------------------------------------------------
We split the data into to two different variables, one with the prediction data and the other with 
the labels for the right answers. The variable y is our labeled dataset, aka the answers we check 
the answers to see if its balaanced or not biased. y.value_counts() shows that we have 0=2788,
1=1813. After we verify the labels then we do train_set_split and break our data. 

SCALE THE FEATURES
----------------------------------------------------------------------------------------------------
For this section we use the StandardScaler to standardize the data, we use .fit on X_train, and 
transform X_train and X_test. 

CREATE AND FIT A LOGISTIC REGRESSION MODEL
----------------------------------------------------------------------------------------------------
From the sklearn library we import LogisticRegression from sklearn.linear_model, then we fit the 
data X_train_scaled, y_train. Predict on on X_test_scaled. and print the accuracy score which is 
0.93 rounded. 

CREATE AND FIT THE A RANDOM FOREST CLASSIFIER MODEL
----------------------------------------------------------------------------------------------------
Here we call the RandomForestClassifier from sklearn.ensemble, we fit the model X_train_scaled, 
y_train. Once the function call is called and we fit the data, we use prdict on the X_test_scaled,
then print the accuracy score of .97 which is better than the LogisticRegression model.













































































































