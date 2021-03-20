# Machine-Learning-Regression

I have to make clear that this project is for training reasons and to help me understand better how to treat a classification problem. There may exist mistakes, thus if you notice anything let me know.

My porpose was to use the dataset which contains many characteristics of BMW cars in order to train some models that can predict the price of the car only by taking as inputs the other characteristics of the car. After that choose the best for use.

In this project i used a dataset from Kaggle.com that concerns the cars of BMW company.
The dataset i chose was cleaned.The cleaned data set contains information of:
1) price
2) transmission
3) mileage
4) fuel type
5) road tax
6) miles per gallon (mpg)
7) engine size. 

Duplicate listings were removed and the columns cleaned.There were no missing values.

In the end my best model was XgBoostRegressor. It reached a R2 score: 0.949. This means that the 94.9% of the variability of the price depends on the other characteristics and the rest 5.1% from other factors.  
