# introML_project
Our Machine Learning project is to use Linear Regression/Ridge/Lasso to predict House Sale.

---
## First step
Firstly we download the data from www.kaggle.com in which it provides lots of different kinds of dataset. 
Our dataset includes two parts: train.csv and test.csv. The training part is used for fitting the models. The testing part is the testing data which does not contain HousePrice part and we need to use the models to predict the house sale of this part.

---
## Second step
At the second step, we need to preprocessing the data. Because both the training data and test data are not normal enough, we combine those two parts into one part, and transform the numeric feature into 'log' form and creat dummy variables for the categorical features after filtering the features with 'object' type. Then we replace the missing values NANs with the mean value of their column.

---
## Final step
Now we are able to set models. More details are in 'House Sale prediction Regression Model.ipynb'.
Final result:

|**Model**                                       |**Mean Square Error**|
|------------------------------------------------|-----------------|
|Linear Multi-Regression with no regularization  |                 |
|Linear Multi-Regression with Ridge L2-regression|                 |
|Linear Multi-Regression with Lasso L1-regression|                 |
