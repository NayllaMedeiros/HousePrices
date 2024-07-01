# HousePrices
Repository created for Kaggle competition on house price prediction
## Introduction
This project was from a kaggle prediction competition. In this project, my objetive and my goal are to predict the sales price for each house. For each Id in the test set, I predicted the value of the SalePrice variable.
## Competition
The dataset from this playground competition proves that price negotiations influence much more than the number of bedrooms or a white picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenged us to predict the final price of each home.

* Training and testing data were available on the competition website, along with descriptions.

## Requirements
For this project I used:
* **Python, Notebook 3.6**
* **Pandas**
* **Numpy**
* For the graphics I imported:
* **(`import seaborn as srn`)**
* **('import matplotlib.pyplot as plt')**
* For forecast models:
* **from sklearn.model_selection ('import train_test_split')**
* **from sklearn.linear_model ('import LinearRegression')**
* **from sklearn.ensemble ('import RandomForestClassifier')**
* Finally, to calculate the errors I used:
* **from sklearn.metrics ('import mean_absolute_error')**
* **from sklearn.metrics ('import mean_squared_error')**

## Clean
For to clean the datas, I first imported the data, then visualized it, observed its types and then started cleaning.
1. Analyze data with empty values
2. Eliminate columns that have more than 10% of empty values 
3. Select only numeric columns as that was what mattered in this case 
4. Clear values ​​that were still empty in the base

## Models and Predictions
To create the training model, first I separated the variables, and then I chose 2 different types to test.
* I tested with Linear Regression and Random Forest
* I calculated the absolute error and the mean square error
* I applied the same training techniques for cleaning and prevision on the test base that was made available to predict house prices

## Conclusion
From my model created for house price predictions, I did linear regression training and with Random Forest, and according to the absolute and mean quadratic errors, we came to the conclusion that Linear Regression brought me in this case the lowest error. 
The graph used helps to visualize how the values ​​predicted by the model compare with the real values ​​and allows you to evaluate the accuracy of the model in predicting new data. When comparing the two models, it is clear that the linear regression predictions were better.
* I managed to reach an error of 0.25, and my goal now is to try to reduce this rate as much as possible.
