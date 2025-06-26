1. At first we imported necessary libraries such as pandas, sklearn and necessary classes from sklearn.
2. We imported the dataset.
3. Using labelencoder we encoded all the categorical variables
4. Using Standard scalar we scaled all the independent variables
5. Then I split the data to 2 halves xtrain,xtest and ytrain, ytest. And we train model with 80% of data and test it with remaining 20%
6. Then we fit the data to the Linear regression model
7. Using mean squared and r1 error we estimate how the model is performing. 
