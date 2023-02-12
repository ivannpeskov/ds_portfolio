## Taxi orders predicting
In this project, I have created a machine learning model for predicting the number of taxi orders at different hours of the day. The model is trained on a dataset of taxi orders and the goal is to accurately predict the number of orders for a given hour.

### Libraries Used
The following libraries were used in this project:

pandas
matplotlib
statsmodels.tsa.seasonal
sklearn
numpy
catboost
### Data
The data used in this project consists of the number of taxi orders at different hours of the day. The data was pre-processed and analyzed to understand the patterns and trends in the number of orders.

### Modeling
To predict the number of taxi orders, I used the following machine learning algorithms:

Linear Regression
CatBoost Regressor
The model was trained and tested on a portion of the data, and the accuracy was evaluated using the mean squared error metric.

Additionally, I also used grid search cross-validation to find the best hyperparameters for the model.

### Results
The results showed that the Linear Regression model performed better than the CatBoost Regressor model in terms of accuracy. The model was able to accurately predict the number of taxi orders for a given hour with a low mean squared error.