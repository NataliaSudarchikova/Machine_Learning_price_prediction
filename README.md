# Machine_Learning_price_prediction
Here I will predict the houses prices in the frame of Kaggle competition (Kaggle_competition_on_housing_prices.ipynb or Kaggle_competition_on_housing_prices.py).

First, I train the model on the dataset train.csv, splitting it before for two data sets. In the data pipepline I used numeric and categorical pipelines, and I used SimpleImputer and two encoders, OrdinalEncoder and OneHotEncoder.

I created the very simple model and checked the model performance with it to have a starting point. 

Then I checked the DecisionTreeRegressor, RandomForestRegressor, LinearRegression models, checked some features selection with SelectFromModel, found the best model parameters, first, with RandomizedSearchCV and then with GridSearchCV.   

The model with the best score in my case was RandomForestRegressor with best parameters found by RandomizedSearchCV and GridSearchCV.

I aplyed this trained model to the new data set called test.csv and saved result in result_Natalia_DataScientist_3.csv file.
