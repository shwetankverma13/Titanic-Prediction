# Titanic-Prediction
A very famous challenge present on kaggle named "Titanic" , has been implemented here . It's about real mishappening which occurred few decades back. Here we are given a data set in which all details on passengers are given ,i.e, whether they survived or not based upon various factors. Our task is to predict whether one person will survive or not based upon some factor.
A overview of the problem statement has been given .
Now , when it comes to the implementation .
First Exploratory Data Analysis is done which is followed by data cleaning. In this particular data set there are huge number of missing value which needs to be taggled smartly other wise our model would not be accurate enough. Hence I have calculated the percentage of missing values for each column and replaced that row with either the mean , mode or directly had dropped the column. This part is very cruicial .
Now when data is cleaned we split the data in training and test set.
Now implementing various ML algorithm and the one which is most accuracte is selected for the prediction.

You can find the training and testing data here. 


