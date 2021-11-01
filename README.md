## TCR-Innovation
## ML-With-Python-Internship



### Final Project 1:
#### Wine Quality Prediction
![image](https://user-images.githubusercontent.com/86619476/139601676-2c6b50a0-95c8-434e-b215-603eff9a7c02.png)

The primary extend is to find out the quality of Wine based on the components given within the dataset.
here we have 11 independent variables and 1 dependant/Target variable that's quality. 

1. Volatile acidity is the gaseous acid present in wine.

2. fixed acidity: Primarily fixed acids found in wine are tartaric, succinic, citric, and malic.

3. residual sugar is the amount of sugar left after fermentation.

4. acid is a weak organic acid, found in citrus fruits naturally.

5. chlorides are the Amount of salt present in wine.

6. free sulfur dioxide i.e. So2 is used for the prevention of wine by oxidation and microbial spoilage.

7. total sulfur dioxide

8. alcohol is the Percent of alcohol present in wine. 

9. sulphates are Added sulfites that preserve freshness and protect wine from oxidation, and bacteria. 

10. pH is used for checking acidity.

11. density.

By using Exploratory Data Analysis, the relationship between the quality of wine with its chemical compositions can be found out.
After that, we partition the wine into two categories, i.e., Good and Bad.
after applying different machine learning algorithms we get different model accuracies such as,
Logistic regression with 87.30%, Decision Tree Classifier with 86.98%, Support Vector Machine with 89.20%, and k-nearest neighbors (KNN) with 89.52% accuracy.

![image](https://user-images.githubusercontent.com/86619476/139458329-b5b25ddd-c814-4814-bdd5-ce616bf1724c.png)

![image](https://user-images.githubusercontent.com/86619476/139458817-b48a36f2-2f4e-4896-b5c9-d4001ebb41a8.png)

![image](https://user-images.githubusercontent.com/86619476/139458446-a32299e0-8703-4b17-9e62-0dda2ab189ea.png)





### Final Project 2: 
#### prediction of the price of the Gold.
![goldprice-1610094551](https://user-images.githubusercontent.com/86619476/139431892-6240297f-c9bb-477d-9640-07130f5b8237.jpg)


The dataset data file is a comma-separated value file format with 2290 rows and 7 columns.

It contains 5 columns which are numerical in datatype and one column in Date format.
1)Date, 2)SPX, 3)GLD, 4) USO, 5)SLV, 6)EUR/USD .

Clearly, the data shows the value of the variables SPX, GLD, USO, SLV, EUR/USD against the dates in the date column.

We predicted the price of Gold based on the 4 independent variables(SPX, USO, SLV, EUR/USD) provided in the dataset and GLD  is Target/Dependent variable.

Exploratory data analysis tells us that the price of GLD  is positively related to SLV and SPX and negatively related to USO, and does not have a significant correlation with the last variable EUR/USD.

we used for Random Forest Algorithm for Regression and got almost 98% accuracy.

![image](https://user-images.githubusercontent.com/86619476/139462276-a33627c2-f241-4987-bf3b-2835773e2c41.png)




### Final Project 3: 
#### Prediction Of Credit Card Fraud.


![image](https://user-images.githubusercontent.com/86619476/139601498-238bc35a-170a-43eb-9ccd-b576b4ba6669.png)

We are having the dataset containing transaction records of credit cards transactions, the dataset contains 492 frauds out of 284,807 transactions.

The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

The dataset contains only numerical input variables, due to confidentiality issues, the dataset provided that doesn't show the original features and more background information about the data, the variables V1, V2, ... V28 are the principal components.

Variable 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset.

The Variable 'Amount' is the transaction Amount.

Variable 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

we used Logistic Regression Algorithm (95% Accuracy score).

we successfully predicted whether the credit card transaction is Legal or Fraud.

![image](https://user-images.githubusercontent.com/86619476/139601247-0734ad11-8772-416c-9d9d-38362a620885.png)


### Thanks.





