# TCR-Innovation ML-With-Python-Internship

## Final Project 1:

### In this we will do Liquor Quality Prediction

!![image](https://user-images.githubusercontent.com/86619476/139455456-4f1e32c8-7f51-4c0c-b3a5-fd730f73ab79.png)

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
#### In this, We will predict the price of the Gold.
![goldprice-1610094551](https://user-images.githubusercontent.com/86619476/139431892-6240297f-c9bb-477d-9640-07130f5b8237.jpg)

##### Features:

This data file is a Comma separated value file format with 2290 rows and 7 columns.

It contains 5 columns which are numerical in datatype and one column in Date format.

Clearly the data shows value of the variables SPX,GLD,USO,SLV,EUR/USD
against the dates in the date column

We predicted the price of Gold based on the 4 independent variables(SPX, USO, SLV, EUR/USD) provided in the dataset and GLD  is Target/Dependent variable.

Exploratory data analysis tells us that the price of GLD  is positively related to SLV and SPX and negatively related to USO, and does not have a significant correlation with the last variable EUR/USD.

we used for Random Forest Algorithm for Regression and got almost 98% accuracy.





