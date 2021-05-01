# Test-Train-Split-Simulation-using-Python
Following previous Logistic Regression using python (click on this link-->) [Logistic-Regression-of-Inflation-Rate-towards-Economic-Growth](https://github.com/altheanabila/Logistic-Regression-of-Inflation-Rate-towards-Economic-Growth)
I try to do simulation of test-train-split afterwards. 

1. Using this line of code to start :

`from sklearn.model_selection import train_test_split`

2. Define the output, which are 4 of them, X_test, X_train, Y_train, Y_test. Define the percentage of test size and train size. This time we use test size at 20% and train size at 80%.

![text image1](https://github.com/altheanabila/Test-Train-Split-Simulation-using-Python/blob/main/trainsplit1.png)


3. Create the object and fit the test

![test image1](https://github.com/altheanabila/Test-Train-Split-Simulation-using-Python/blob/main/trainsplit2.png)


4. Create the values of predicted Y dataset using this line:

`Y_test_pred = clf_LR.predict(X_test)`


5. Create confusion matrix of actual Y test and predicted Y_test value:

![testimage](https://github.com/altheanabila/Test-Train-Split-Simulation-using-Python/blob/main/trainsplit3.png)

6. Create Accuracy score

![test image](https://github.com/altheanabila/Test-Train-Split-Simulation-using-Python/blob/main/trainsplit4.png)

