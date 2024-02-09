# Logistic-Regression-2
In this project, we'll work on fake advertisement dataset, indicating whether or not aparticular internet user clicked on the advertisement. We'll create a model that will predict whether or not they will click on an ad based on features of that user.

For data, we are using Advertising dataset wherein we are going to write algorithms based on Logistic Regression. The data contains 1000 rows and 10 columns. Steps used--- a) Importing the dependencies like numpy, pandas, matplotlib and seaborn b) Importing the data to read what's contained in the dataset. c) Basic data exploration using head, info. d) EDA using jointplot, histplot,pairplot 
e) The null values in Age column are filled with the median values while some column will be removed from the analysis 
f) Now we'll encode the categorical columns since machine understands numbers 
g) Train Test split the datset. 
h) Importing Logistic regression model 
i) Predictions to be done on testing dataset. 
j) Using classification report we try and find out the accuracy 
j) Conclusion: The model is performing with the 90% accuracy which means that there are only 10 instances out of 100 when user won't click to see the ad but there are 90% chances that user will visit that ad. Though more tuning of the model can be done which may further lead to accuracy score.
