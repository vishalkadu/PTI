## TCR-Innovation
## ML-With-Python-Internship



### Final Project 1:

#### 1.Liquor Quality Prediction

![image](https://user-images.githubusercontent.com/86619476/139601676-2c6b50a0-95c8-434e-b215-603eff9a7c02.png)

#### Features

volatile acidity : Volatile acidity is the gaseous acids present in wine. fixed acidity : Primary fixed acids found in wine are tartaric, succinic, citric, and malic

residual sugar : Amount of sugar left after fermentation.

citric acid : It is weak organic acid, found in citrus fruits naturally.

chlorides : Amount of salt present in wine.

free sulfur dioxide : So2 is used for prevention of wine by oxidation and microbial

spoilage. total sulfur dioxide

alcohol : Percent of alcohol present in wine. 

sulphates : Added sulfites preserve freshness and protect wine from oxidation, and
bacteria.

pH : In wine pH is used for checking acidity
density.

The primary extend is to find out the quality of Wine based on the components given within the dataset.
here we have 11 independent variables and 1 dependant/Target variable that's quality. 
by using EDA, the relationship between the quality of wine with its chemical compositions can be found out.
After that, we partition the wine into two categories, i.e., Good and Bad.
after applying different machine learing algorithms we get different model accuracies such as,
Logistic regression with 87.30%, Decision Tree Classifier with 86.98%, Support Vector Machine with 89.20% and  k-nearest neighbors (KNN) with 89.52% accuracy.

![image](https://user-images.githubusercontent.com/86619476/139458329-b5b25ddd-c814-4814-bdd5-ce616bf1724c.png)

![image](https://user-images.githubusercontent.com/86619476/139458817-b48a36f2-2f4e-4896-b5c9-d4001ebb41a8.png)

![image](https://user-images.githubusercontent.com/86619476/139458446-a32299e0-8703-4b17-9e62-0dda2ab189ea.png)





### Final Project 2: 
#### 2.prediction of the price of the Gold.
![goldprice-1610094551](https://user-images.githubusercontent.com/86619476/139431892-6240297f-c9bb-477d-9640-07130f5b8237.jpg)


The dataset data file is a Comma separated value file format with 2290 rows and 7 columns.

It contains 5 columns which are numerical in datatype and one column in Date format.

Clearly the data shows value of the variables SPX,GLD,USO,SLV,EUR/USD
against the dates in the date column

We predicted the price of Gold based on the 4 independent variables(SPX, USO, SLV, EUR/USD) provided in the dataset and GLD  is Target/Dependent variable.

Exploratory data analysis tells us that the price of GLD  is positively related to SLV and SPX and negatively related to USO, and does not have a significant correlation with the last variable EUR/USD.

we used for Random Forest Algorithm for Regression and got almost 98% accuracy.

![image](https://user-images.githubusercontent.com/86619476/139462276-a33627c2-f241-4987-bf3b-2835773e2c41.png)




### Final Project 3: 
#### 3.Prediction Of Credit Card Fraud.


![image](https://user-images.githubusercontent.com/86619476/139601498-238bc35a-170a-43eb-9ccd-b576b4ba6669.png)

We are having the dataset containing transaction records of credit cards transactions, the dataset contains 492 frauds out of 284,807 transactions.

The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

Dataset contains only numerical input variables, due to confidentiality issues, the dataset provided that doesn't show the original features and more background information about the data, the variables V1, V2, ... V28 are the principal components.

Variable 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset.

The Variable 'Amount' is the transaction Amount.

Variable 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

we used Logistic Regression Algorithm and got almost 95% Accuracy score,also we succesfully predicted whether the credit card trasnsaction is Legal or Fraud.

![image](https://user-images.githubusercontent.com/86619476/139601247-0734ad11-8772-416c-9d9d-38362a620885.png)









