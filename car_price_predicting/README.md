## Car Price Prediction using Machine Learning
This project focuses on developing machine learning models to predict the prices of cars. The project uses several popular libraries such as pandas, numpy, and scikit-learn to preprocess and explore the data, build and train models, and evaluate their performance. In addition to traditional linear regression, the project also employs more advanced models like CatBoostRegressor, lightgbm, RandomForestRegressor, and DummyRegressor to enhance the prediction accuracy. The project uses the cross_val_score method to evaluate the performance of each model and compares the results to determine the best model.
### Requirements
In order to run this project, you will need the following libraries:
pandas
re
numpy
scikit-learn
catboost
lightgbm

### Model Building
The models are built using various algorithms such as LinearRegression, CatBoostRegressor, lightgbm, RandomForestRegressor, and DummyRegressor. The models are trained on the training data and their performance is evaluated using the mean squared error metric.

### Model Comparison
The performance of each model is compared using the cross_val_score method. The results are then used to determine the best model for predicting car prices.