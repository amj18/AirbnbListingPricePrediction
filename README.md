# Airbnb Listing Price Prediction

**Description:**

This Data Science project attempts to predict the listing price of Airbnb rentals of the London area during October 2019 using Python 3.7 jupyter notebooks. After data cleaning and feature engineering, Stochastic Gradient Descent Linear Regression and Gradient Boosting Regression models were applied. The GB Regressor model outperformed the SDG Regressor, and an R^2 score of 0.56 on test data and RMSE of 68.68 was obtained. Due to the large file sizes, the raw data used to train the model has not been provided in this repo, however the URL is provided.

The Jupyter notebooks are organised as follows. HTML versions are also included in this repo for convenience.

1. **ExtractTransformLoad.ipynb**

- This notebook extracts the data from the Airbnb API / URL, unzips it, and stores the raw dataframe to disk. 
  
2. **DataExploratoryAnalysis.ipynb**

- The raw data was explored, corrected for missing values and around 11 key business questions about the dataset were answered with some commonly used statistical methods.

3. **FeatureEngineering.ipynb**

- A baseline model was first implemented using a simple linear regression model. After this, features were engineered based on the data exploration above.

4. **ModelTrainTest.ipynb**

- Statistical transformations were implemented sequentially on a Stochastic Gradient Descent Linear Regression model with corresponding learning curves to visualise the bias and variance in the model. Finally, a Gradient Boosting Regression model was implemented. PCA was also briefly looked into to analyse which feature components explained the most variance in the data.
