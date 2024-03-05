# MachineLearning-practices
Machine learning course and implementation of its academic exercises (Tarbiat Modares University)

## Part1
* Q1: Examine and comment on the following data set related to Parkinson's patients in terms of data structure, data type, and characteristics. Convert this data set to a data table using “Panⅾas” and explain how you can select the label. Store the label in a variable and the data (samples) in a separate variable (table). In this case, how many data and features are there? Then find at least three papers from 2018 onwards that have done classification on this dataset. Without going into detail, explain what their method was and what accuracy they achieved.
  https://archive.ics.uci.edu/dataset/174/parkinsons

* Q2: Take 10 random points from the function (πx2(sin = y) in the interval [1 , 0]:  
a) Add noise to them and perform polynomial regression with degrees 1 to 9. (add noise to y_i's)    
b) Add 2 outlier points to the above 10 points and report the results of simple regression, lasso and Ridge. (Consider λ as appropriate)  
c) Report the sum of the distance between the predicted points and the original points as the error for each of the above cases (MAE).  
d) with the regularization values [10^-7, 10^-5] ∋ λ with a step length of 10^-7 for polynomial regression with degree 9, solve the problem of soft 1 and soft 2 regularization and the accuracy for λ to Plot as a graph. (Draw the graph as RMSE − λ)  

## Part2  
* Q1: Generate a synthetic dataset of 200 for analysis with a linear regression model.    
1. x_1: the first feature with values in the range of 0 to 5    
2. x_2: the second feature with values in the range of 5 to 10  
3. x_3: x_2^2*x_1  
4. y: dependent variable ⅼabeⅼ with values in the range 10 to 20 plus noise (the noise added to the data should be realistic, for example using a normal distribution with mean zero and variance 1)  

a) Divided the data into two parts of training and testing with a rate of 80%.  
b) Using linear regression models and polynomial kernel Φ(X) polynomial), teach from grades 1 to 9,  
c) Apply all kinds of regularizers on them and report the results (two soft1 and soft2 cases with appropriate parameters are enough)  
d) Evaluate all the models by the kfoⅼⅾ method (5) and report the best model (cost measure ⅯSE).  

* Q2: One of the famous datasets in the field of machine learning is Prices House Boston. The main goal is to estimate the price of houses based on features.  
a) train a linear regression model on this data (if the training and test data are not separate, separate them at 80% rate)  
b) Train two new regression models, Riⅾge and Ⅼasso, on the data. Consider regularization rates over a specific interval [10^-5 , 0] (check at least 5 regularization rates).  
c) Select the best model and regularizer by using the kfoⅼⅾ) method (5) and checking the performance of each model (the cost criterion is RⅯSE or ⅯSE)  
d) Analyze your results and check the effect of regularizers on the parameters.  

* Q3: Implement a logistic regression model using Heart Disease dataset.  
a) Check and clean the data. If there are missing data, fill them using the appropriate method. Convert ⅽategoriⅽaⅼ (ⅽategoriⅽaⅼ) to appropriate form and standardize features if needed  
b) Add a suitable regularizer with suitable parameters to the logistic regression to improve the prediction accuracy.  
c) Evaluate the model using accuracy criteria, ROⅭ curve, sensitivity, etc.  
d) Which features have the greatest effect on prediction. Analyze their role and regular function of instruments.  
https://archive.ics.uci.edu/dataset/45/heart+disease  
