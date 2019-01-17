# This is the project assignement for the Coursera Practical Machine Learning Mooc

This report uses data from http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har.
This is sensor data from wearable devices and the goal is to predict a class of human behaviour from this sensor data.
After loading and cleaning the data we evaluate several models with a 5-fold cross validation, select the models with the best accuracy and combine their predictions with a majority vote to make our final prediction on the test data.
