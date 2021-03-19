# Machine-Learning-Regression

My porpose was to use the dataset which contains many characteristics of BMW cars in order to train many models and eventually choose the best. It can predict the price of the car only by taking as inputs the other characteristics of the car.

In this project i used a dataset from Kaggle.com that concerns the cars of BMW company.
The dataset i chose was cleaned.The cleaned data set contains information of price, transmission, mileage, fuel type, road tax, miles per gallon (mpg), and engine size. Duplicate listings were removed and the columns cleaned.There were no missing values.

In the end my best model was XgBoostRegressor. It reached a R2 score: 0.949. This means that the 94.9% of the variability of the price depends on the other characteristics and the rest 5.1% from other factors.  
