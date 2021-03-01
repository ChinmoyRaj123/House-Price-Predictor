![](https://i.ytimg.com/vi/1TnafLGm6UA/maxresdefault.jpg)

# House Price Prediction

## Table of content
  * [Overview]
  * [Project Details]
  * [Result]
  
## Overview
Buying a house is a stressful thing. Many problems are faced while buying a house. Since, real estate agents are trusted with the communication between buyers and sellers, this only increases the cost of the house. 
It is believe that the price of a house depends on features like- Square foot area, number of bedrooms and bathrooms, neighbourhood. While in reality, it depends on many factors like- Number of storeys, Rooms on the floor, outside view, basement area, etc.
Hence, this project is about a Machine Learning model that is built on a certain specific features of your home, which will predict the most accurate price of your house.

## Project Detail
This is a Machine Learning model based on certain predefined features of a house. Tha data used to build the model consists of several features like no. of bedrooms, bathrooms, living area, basement area, plot area, outside view etc. The complete dataset can be found here-(https://www.kaggle.com/shivachandel/kc-house-data)
At first, the dataset is loaded after which analysis and feature engineering is done. On the final dataset, three machine learning algorithms are applied(i.e Linear Regression, Decision Tree Regressor, Random Forest Regressor).
After building the three models on three different regressor algorithms, their accuracy are compared and the one with highest accuracy is selected as the best fit model to predict the house price accurately.

## Result
The final result obtained from the project is that, the model built on Random Forest Regressor is the best fit model in predicting the price of a house accurately. The model accurately predicted the given prices with an accuracy of 84%. Hence, new price can be predicted from unseen data quite accuratrely.
