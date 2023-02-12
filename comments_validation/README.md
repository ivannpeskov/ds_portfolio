## Toxic Comment Validation Model
This project focuses on creating a machine learning model that can classify a given comment as toxic or not. The model has been trained on a dataset of comments and their corresponding toxicity labels.

### Technologies used:
Pandas
NLTK
TQDM
Sklearn
CatBoost

### Data Processing
The data processing involved the following steps:

Loading the data using pandas
Removing stop words and punctuation
Lemmatizing the words
Converting the text data into numerical data using either CountVectorizer or TfidfVectorizer

### Model Training
The following machine learning models were trained and evaluated on the processed data:

Logistic Regression
CatBoost Classifier
The best performing model was selected based on the cross-validation score and the F1 Score.

### Evaluation
The performance of the final model was evaluated based on the F1 Score. The F1 Score is a measure of a model's accuracy that takes into account both precision and recall.