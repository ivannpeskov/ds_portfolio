## Steel Temperature Prediction
A machine learning model that predicts the final temperature of steel after preparation process.

### Overview
The aim of this project is to develop a machine learning model that can predict the final temperature of steel after preparation process. The model is trained on a dataset containing various parameters such as time, temperature, and chemical composition of the steel. The performance of the model is evaluated based on the mean absolute error between the predicted and actual temperature values.

### Libraries used
The following libraries were used in this project:

pandas
datetime
matplotlib
scikit-learn
numpy
catboost
statsmodels
scipy
### Data Processing
The dataset was loaded into a pandas DataFrame and pre-processed to remove missing values and outliers. The data was then split into training and testing sets.

### Model Selection and Training
The project compares the performance of multiple regression models, including Linear Regression, Random Forest Regressor, and CatBoost Regressor. The best model is selected based on cross-validation scores and the mean absolute error.

### Hyperparameter Tuning
The GridSearchCV method was used to tune the hyperparameters of the selected model.