# Prediction of House Sale Prices in New York
Built this project in R.

* Took a dataset containing 81 attributes of a house where sale Price is the Response variable.
* Preprocessed the data by handling missing values, duplicates, skewness, categorical variables, outliers, correlation, feature engineering and feature selection for every attribute individually.
* Divided the new data into train and test datasets.
* Built an XGBoost model and trained the model with train dataset. Later, valuated the trained model on test dataset to predict sale prices with visualizations.
* The evaluated model performance resulted with an accuracy of 94%.
* To evluate the performance of XGBoost with other models. I implemented Linear and Lasso Regression where accuracy of these models resulted lesser than XGBoost. 
